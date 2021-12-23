# Dupe Plugin

Created by Creative0708#1593

## Installation

Download the [jar file](https://github.com/MinerServer-Host/Plugins/releases/download/plugin/MinerserverDupePlugin.jar) and put it in your plugins folder (you need to be using spigot or paper with 1.18.1).

## Config

```yaml
# Config for Minerserver Dupe Plugin

world-dupe:
   world-list-file: "world-list.json"
   world-list-is-blacklist: true
   auto-write: true
blacklisted-items:
   - "BEDROCK"
   - "COMMAND_BLOCK"
   - "REPEATING_COMMAND_BLOCK"
   - "CHAIN_COMMAND_BLOCK"
   - "COMMAND_BLOCK_MINECART"
   - "BARRIER"
```

## Commands
### /dupe
Dupes the item you are holding.
Usable by everyone.
### /toggledupeable
Makes the item you are holding dupeable or undupeable. If an item is undupeable it can only be made dupeable by the person that made it undupeable (undupeable items can be duped by players with OP). This command can by used by everyone.
### /worlddupe
Makes /dupe not work in the current world you are in. Only players with OP can use this.
