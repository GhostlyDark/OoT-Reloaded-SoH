# OoT Reloaded (SoH)
Ocarina of Time Reloaded is an Ultra HD texture pack for [GLideN64](https://github.com/GhostlyDark/OoT-Reloaded), [Dolphin](https://github.com/GhostlyDark/OoT-Reloaded-Dolphin) and Ship of Harkinian.

![](/oot-reloaded-soh.jpg)


## How to use OTR files
Requires SoH `v8.0.0` or newer. OTR files go into the `mods` directory. The order in which mods are loaded can be modified by changing file names. Current release files have the `alt/` path is prepended, which requires unhiding the menu with F1 and enabling `Enhancements -> Graphics -> Use Alternate Assets` while in-game.


## Generate from PNG source
1. Install SoH by generating as many `.otr` files as possible using supported ROMs. Check the SoH readme for supported versions.
2. Download [retro](https://github.com/HarbourMasters/retro/releases/latest).
3. Click `Create OTR / O2R -> Replace Textures -> No`, then select all available `.otr` files at the same time. This will extract the textures from all archives and generates a `manifest.json`.
4. The compiled `manifest.json` needs to be copied into the directory that contains HD textures, mirroring the file structure of the extracted files. Overwrite any `.json` files included in this repository.
5. Choose `Create OTR / O2R -> Replace Textures -> Yes` and select the folder containing HD textures.
6. Keep files uncompressed to reduce stuttering. It is recommended to prepend `alt/` before staging textures, which allows assets to be toggled on-the-fly. Click `Stage Textures` to continue.
7. Click `Finalize OTR / O2R` and `Generate OTR / O2R` as the final step.
