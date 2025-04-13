# OoT Reloaded (SoH)
Ocarina of Time Reloaded is an Ultra HD texture pack for [GLideN64](https://github.com/GhostlyDark/OoT-Reloaded), [Dolphin](https://github.com/GhostlyDark/OoT-Reloaded-Dolphin) and Ship of Harkinian.

![](/oot-reloaded-soh.jpg)


## How to use OTR/O2R files
Requires SoH `v9.0.1` or newer. O2R files go into the `mods` directory. The order in which mods are loaded can be modified by changing file names. Release files have the `alt/` path prepended, which requires unhiding the menu pressing `Escape` and enabling `Use Alternate Assets` while in-game. Alternatively, press `Tab` to toggle the textures.


## Generate from PNG source
1. Install SoH by generating as many `.otr` files as possible using supported ROMs. Check the SoH readme for supported versions.
2. Download [retro v0.0.5](https://github.com/HarbourMasters/retro/releases/tag/0.0.5) for `.otr` extraction purposes.
3. Click `Create OTR / O2R -> Replace Textures -> No`, then select all available `.otr` files at the same time. This will extract the textures from all archives and generates a `manifest.json`.
4. The compiled `manifest.json` needs to be copied into the directory that contains HD textures, mirroring the file structure of the extracted files. Overwrite any `.json` files included with this repository.
5. Download [retro v0.2.0](https://github.com/HarbourMasters/retro/releases/tag/0.2.0) for creating an `.o2r` file.
5. Choose `Create OTR / O2R -> Replace Textures -> Yes` and select the folder containing HD textures.
6. Keep files uncompressed to reduce stuttering. It is recommended to prepend `alt/` before staging textures, which allows assets to be toggled on-the-fly. Click `Stage Textures` to continue.
7. Click `Finalize OTR / O2R` and `Generate OTR / O2R` as the final step.
