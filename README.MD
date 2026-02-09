# OoT Reloaded (SoH)
Ocarina of Time Reloaded is an Ultra HD texture pack for [GLideN64](https://github.com/GhostlyDark/OoT-Reloaded), [Dolphin](https://github.com/GhostlyDark/OoT-Reloaded-Dolphin) and Ship of Harkinian.

![](/oot-reloaded-soh.jpg)


## How to use O2R files
Requires SoH `v9.0.1` or newer. O2R files go into the `mods` directory. The order in which mods are loaded can be modified by changing file names. Release files have the `alt/` path prepended, which requires unhiding the menu pressing `Escape` and enabling `Use Alternate Assets` while in-game. Alternatively, press `Tab` to toggle the textures.


## Convert textures from PNG source

Only for advanced users. If you simply want to install the pack, grab it from [here](https://github.com/GhostlyDark/OoT-Reloaded-SoH/releases/latest) instead.
If you wish to generate ready to use textures from source, you are required to download an run [retro](https://github.com/HarbourMasters/retro/releases/latest).


### Update manifest.json
This repo contains a `manifest.json`, which may be required to be updated when a new SoH build is released.

1. Install SoH by generating as many `.o2r` files as possible using supported ROMs. Check the SoH readme for supported versions.
2. Using retro, click `Create OTR / O2R -> Replace Textures -> No`, then select all available `.o2r` files at the same time. This will extract the textures from all archives and generates a `manifest.json`.
3. The compiled `manifest.json` needs to be copied into the directory that contains HD textures, mirroring the file structure of the extracted files.


### Convert textures

1. Inside retro, choose `Create OTR / O2R -> Replace Textures -> Yes` and select the folder containing HD textures.
2. Keep files uncompressed to reduce stuttering. It is recommended to prepend `alt/` before staging textures, which allows assets to be toggled on-the-fly. Click `Stage Textures` to continue.
3. Click `Finalize OTR / O2R` and `Generate OTR / O2R` as the final step.
