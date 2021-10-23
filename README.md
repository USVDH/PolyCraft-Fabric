# Polycraft

Version 2.0 of the private Minecraft survival server Polycraft. Check the releases page for the configurations for specific versions of Minecraft.

## Getting Started

This repo will include everything that is needed to reproduce a similar server, with the exception of sensitive data such as the whitelist, API keys etc. as well as the mod loaders and mods used, please download them yourself from their respective owners.

## Background

PolyCraft V1 officially started in 2016 at Minecraft version 1.10 (Java), but has had numerous predecessors dating back to 2010. With the codebase for PolyCraft V1 becoming 5 years old, I thought I'd be a good idea to make a V2 from scratch in preperation for Minecraft version 1.18. 

<!---
## Key Features

* Quality of life features such as /spawn, /home and /tpa.
* Crossplay with Java and Bedrock thanks to [GeyserMC](https://geysermc.org/) 
* Full-fledged integration with Discord (i.e. Chat Relay) thanks to [DiscordSRV](https://www.spigotmc.org/resources/discordsrv.18494/) and [RelayItToDiscord](https://www.spigotmc.org/resources/relayittodiscord.34615/) 
* Numerous anti-lag measures thanks to [FarmControl](https://www.spigotmc.org/resources/farmcontrol-1-15-1-17.86923/) and [LagMonitor](https://www.spigotmc.org/resources/lagmonitor.21348/), as well as [PaperMC](https://papermc.io/)
* Anti-grief measures with [CoreProtect](https://www.spigotmc.org/resources/coreprotect.8631/) and [InventoryRollback](https://www.spigotmc.org/resources/inventory-rollback.48074/)
--->
## How to use 

This repo is provided without the server .jar file and plugin .jar files, please download them from their respective creators. To get a working Minecraft server use the next steps: 
1. Download [Fabric](https://fabricmc.net/use/) and run the .jar (or .exe) file to get the fabric .jar and vanilla .jar files.
2. Download all the mods and put them into /mods
3. Download the datapacks and put them into /world/datapacks
4. Start the server once and then shut it down
5. Adjust the configs in /config to your liking. The most important ones are config/disfabric.json5 and config/textile_backup.json5

And you're done! Now you (should) have a fully working server.

### Mod loader

In this release (v1.0.0) [Fabric Loader v0.11.6](https://fabricmc.net/use/) is used for Minecraft 1.17.1.

### Mods

Below is a list of the mods used for this release (v1.0.0) with their respective versions. However, if there is a newer version available I suggest using that instead. Click on the mod name for the CurseForge page, and click on the version number to go directly to the version download.

- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) [0.41.0](https://www.curseforge.com/minecraft/mc-mods/fabric-api/download/3494349)
- [Fabric Language Kotlin](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin) [1.6.5](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin/download/3477154)
- [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) [0.7.4](https://www.curseforge.com/minecraft/mc-mods/lithium/download/3438799)
- [BedrockWaters](https://www.curseforge.com/minecraft/mc-mods/bedrockwaters) [1.5.0](https://www.curseforge.com/minecraft/mc-mods/bedrockwaters/download/3466383)
- [LengthyLadders](https://www.curseforge.com/minecraft/mc-mods/lengthy-ladders) [1.0.4](https://www.curseforge.com/minecraft/mc-mods/lengthy-ladders/files/3346108)
- [LapisReserve](https://www.curseforge.com/minecraft/mc-mods/lapis-reserve) [1.0.8](https://www.curseforge.com/minecraft/mc-mods/lapis-reserve/files/3345208)
- [TheLovedOnes](https://www.curseforge.com/minecraft/mc-mods/the-loved-ones) [1.2.0](https://www.curseforge.com/minecraft/mc-mods/the-loved-ones/files/3361467)
- [WanderingCollector](https://modrinth.com/mod/wandering-collector) [1.0.2](https://modrinth.com/mod/wandering-collector/version/zSsKV0tr)
- [Notchify](https://www.curseforge.com/minecraft/mc-mods/notchify) [0.4.1](https://www.curseforge.com/minecraft/mc-mods/notchify/files/3346344)
- [TextileBackup](https://www.curseforge.com/minecraft/mc-mods/textile-backup) [2.2.0](https://www.curseforge.com/minecraft/mc-mods/textile-backup/download/3412941)
- [ModsCommand](https://modrinth.com/mod/mods-command) [1.0.4](https://modrinth.com/mod/mods-command/version/bScsJIDd)
- ["Player has moved too fast!" Server Warning Fix/Patch](https://www.curseforge.com/minecraft/mc-mods/player-has-moved-too-fast-server-warning-fix-patch) [1.0.0](https://www.curseforge.com/minecraft/mc-mods/player-has-moved-too-fast-server-warning-fix-patch/files/3383833)
- [DisFabric](https://www.curseforge.com/minecraft/mc-mods/disfabric) [1.3.3](https://www.curseforge.com/minecraft/mc-mods/disfabric/files/3347232)
- [Ledger](https://github.com/QuiltServerTools/Ledger) [1.1.1](https://github.com/QuiltServerTools/Ledger/releases/tag/1.1.1)
<!--- - [DimentionalThreading](https://github.com/WearBlackAllDay/DimensionalThreading) [1.2.5](https://github.com/WearBlackAllDay/DimensionalThreading/releases/tag/v1.2.5) --->

### Datapacks

- [Vanilla Tweaks Player Head Drops & More Mob Heads](https://vanillatweaks.net/share#ctCn0s)
- [Voodoo Packs AFK Detection, PvP Player Heads & Trader Notify](http://mc.voodoobeard.com/#datapacks)
