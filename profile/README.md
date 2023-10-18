# Lynx
###### Currently in early development

Lynx Anticheat is an advanced all-in-one anti-cheat solution for Minecraft servers, offering support for versions 1.8.x to 1.20.x. Our anti-cheat is made for all to enjoy and features diffrent tiers allowing you the server owner to pitch and choose the tier best suited for your situation. Our anti-cheat incorporates advanced techniques rarely found in other free solutions, including MultiThreading, Plugin Hiding and AntiVPN.

## Features
| Feature | Description | Status |
| ------------- |:-------------:| :-----:|
| [Multi Threading](https://towardsdatascience.com/multithreading-and-multiprocessing-in-10-minutes-20d9b3c6a867) | By leveraging multi threading we can minimize impact of server performance | ✔️ |
| [Anti-VPN](https://en.wikipedia.org/wiki/Proxy_server) | Prevent any cheaters trying to bypass ip bans using proxies | ❌ |
| [bStats](https://bstats.org/) | Collect usage data | ❌ |
| [Redis](https://redis.io/) | Cross-server alerts | ✔️ |
| Hider | Hide the plugin completely | ✔️ |
| Config | Easily customize Lynx to your needs | ✔️ |
| [Cheat Detection](https://github.com/Lynx-Anticheat#Checks) | Easily detect and mitigate cheats reliabily | ✔️ |

## Checks
<details> 
    <summary><h3>Combat</h3></summary>

| Check      | Description                          | Status |
|------------|--------------------------------------|:-------:|
| Aim        | Detect suspicous aiming patterns or flaws in a players rotations | ✔️ |
| Reach      | Detect anyone reaching above the hard coded limit of 3.0 | ✔️ |
| Hitbox     | Detect anyone not hitting inside the correct hitbox | ✔️ |
| Killaura   | Detect flaws in hacked clients killauras | ✔️ |
| Analysis   | Heuristic combat analysis (clicking, rotations, movement and accuracy) | ❌ |
| AutoClicker | Detect suspicous or impossible clicking patterns | ❌ |
</details>

<details> 
    <summary><h3>Movement</h3></summary>

| Check      | Description                          | Status |
|------------|--------------------------------------|:-------:|
| Simulation | Detect any movements that violate vanilla protocol | ✔️ |
| Velocity   | Checks if the player received velocity properly | ✔️ |

</details>
<details> 
    <summary><h3>Player</h3></summary>

| Check      | Description                          | Status |
|------------|--------------------------------------|:-------:|
| Scaffold   | Detect unusual block-placing activity  | ✔️ |
| FastBreak  | Detect unusual block-breaking activity  | ✔️ |
| Interact   | Detect impossible player interactions (raytrace, fast use, etc)  | ✔️ |

</details>


<details> 
    <summary><h3>Misc</h3></summary>

| Check      | Description                          | Status |
|------------|--------------------------------------|:-------:|
| Inventory  | Detect unusual inventory activity (too fast or moving)  | ✔️ |
| Packet     | Detect players sending impossible packets (ping spoof, etc)  | ✔️ |

</details>

## Developers
-  [Cyanade](https://github.com/Cyanade/)
-  [FinalBoolean](https://github.com/FinalBoolean)
-  [EpicCatto (Pat)](https://github.com/EpicCatto)
-  [Preceding](https://github.com/Precedingxd)
-  [Hunter171](https://github.com/Hunter-171/)

## Credits
- Soon™️
<img src='https://svgshare.com/i/xjT.svg' />
