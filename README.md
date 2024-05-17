# Disclaimer
> [!CAUTION]
> ## Modifying Guild Wars 2 through any third party software is not supported by ArenaNet nor by any of its partners.
> ## You are using this addon at your own risk.

> [!IMPORTANT]
> This addon was built with appropriate limitations to ensure that it is within the official [Third Party Program Policy](https://help.guildwars2.com/hc/en-us/articles/360013625034-Policy-Third-Party-Programs).
> If you believe this addon is violating the third party policy, please [create an issue](../../issues) here on this repository voicing your concerns.
> 
> Portions or the entirety of the codebase remain closed-source in compliance with requests by ArenaNet.

## To ArenaNet
### Please reach out to us by [creating an issue](../../issues) for concerns, takedown requests or review requests for the codebase.

---

![](https://img.shields.io/github/v/release/RaidcoreGG/GW2-FastLoad-Releases?style=for-the-badge&labelColor=%23131519&color=%230F79AA)
![](https://img.shields.io/github/downloads/RaidcoreGG/GW2-FastLoad-Releases/total?style=for-the-badge&labelColor=%23131519&color=%230F79AA)

# GW2-FastLoad-Releases
Public repository for releases of loading screen skip.

## Installation
Install via the [Nexus](https://raidcore.gg/Nexus) Addon Library or download the latest `fastloadingscreen.dll` from the [Releases](https://github.com/RaidcoreGG/GW2-FastLoad-Releases/releases) and place in `<Guild Wars 2>/addons`.

## How it works
This addon makes runtime modifications to patch the timeout of loading models &amp; players from 60 seconds down to 150 milliseconds.

## Limitations
- Loading screens aren't skipped entirely but on average take 2 seconds.
- Disabled in PvP and WvW gamemodes. Exceptions are Armistice Bastion and Obsidian Sanctum.
- Spamming lots of loading screens will result in longer ones, as you will spam the server with requests and you will be limited by the server, way before any skipping takes place.
