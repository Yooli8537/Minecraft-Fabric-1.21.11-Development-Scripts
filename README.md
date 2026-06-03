# Minecraft-Fabric-1.21.11-Development-Scripts

This Repository includes three scripts to make developing in 1.21.11 fabric easier.

The Scripts were made to work with the [1.21.11 Fabric Example Mod](https://github.com/FabricMC/fabric-example-mod/tree/1.21.11) but may work outside of it.

## Requirements

Make sure you have Modrinth installed with an **Instance Folder** named "ModTest" to run the `deploy.ps1` script.

## Installation

### Releases

1. Download the newest [release](https://github.com/Yooli8537/Minecraft-Fabric-1.21.11-Development-Scripts/releases).
2. Unzip the file, setting your **project's root folder** as the target folder.

### Git

1. Run these commands in an IDE's (preferrably Intellij IDEA as it is standard for Minecraft Modding) CLI.
``` PowerShell
git clone https://github.com/FabricMC/fabric-example-mod/tree/1.21.11
git clone https://github.com/Yooli8537/Minecraft-Fabric-1.21.11-Development-Scripts
```
2. Open the folder in your File Explorer.
3. Delete the `.git` folder. May require turning on "Hidden items".

## How to run

To run the scripts, simply run them in your IDE's CLI at the root directory like this:
``` PowerShell
./scripts/build.ps1

./scripts/deploy.ps1

./scripts/runClient.ps1
```
