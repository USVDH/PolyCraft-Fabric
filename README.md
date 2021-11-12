# Polycraft

Version 2.0 of the private Minecraft survival server Polycraft. Check the releases page for the configurations for specific versions of Minecraft.

## Getting Started

This repo will include everything that is needed to reproduce a similar server, with the exception of sensitive data such as the whitelist, API keys etc. as well as the mod loaders and mods used, please download them yourself from their respective owners.

## Background

PolyCraft V1 officially started in 2016 at Minecraft version 1.10 (Java), but has had numerous predecessors dating back to 2010. With the codebase for PolyCraft V1 becoming 5 years old, I thought I'd be a good idea to make a V2 from scratch in preperation for Minecraft version 1.18. 

## How to use 

This repo is provided without the server .jar file and plugin .jar files, please download them from their respective creators. To get a working Minecraft server use the next steps: 
1. Download [Fabric](https://fabricmc.net/use/) and run the .jar (or .exe) file to get the fabric .jar and vanilla .jar files.
2. Download all the mods and put them into /mods
3. Download the datapacks and put them into /world/datapacks
4. Start the server once and then shut it down
5. Adjust the configs in /config to your liking. The most important ones are config/disfabric.json5 and config/textile_backup.json5

And you're done! Now you (should) have a fully working server.

### Mod loader

In this release (v1.0.0) [Fabric Loader v0.11.6](https://fabricmc.net/use/) is used for Minecraft 1.18-pre1.

### Mods

Below is a list of the mods used for this release (v1.0.0) with their respective versions. However, if there is a newer version available I suggest using that instead. Click on the mod name for the CurseForge page, and click on the version number to go directly to the version download.

- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) [0.42.2](https://www.curseforge.com/minecraft/mc-mods/fabric-api/download/3522624/file)
- [LengthyLadders](https://www.curseforge.com/minecraft/mc-mods/lengthy-ladders) [1.0.5](https://www.curseforge.com/minecraft/mc-mods/lengthy-ladders/download/3522416/file)
- [LapisReserve](https://www.curseforge.com/minecraft/mc-mods/lapis-reserve) [1.0.8](https://www.curseforge.com/minecraft/mc-mods/lapis-reserve/download/3345208/file)

### Datapacks
