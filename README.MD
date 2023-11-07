# OoT Reloaded (SoH)
Ocarina of Time Reloaded is an Ultra HD texture pack for [GLideN64](https://github.com/GhostlyDark/OoT-Reloaded), [Dolphin](https://github.com/GhostlyDark/OoT-Reloaded-Dolphin) and Ship of Harkinian.

![](/oot-reloaded-soh.jpg)


## How to use OTR files
Requires SoH `v8.0.0` or newer. OTR files go into the `mods` directory. The order in which mods are loaded can be modified by changing files names. Current release files have the `alt/` path is prepended, which requires unhiding the menu with F1 and enabling `Enhancements -> Graphics -> Use Alternate Assets` while in-game.


## OTR releases
- `Link Eyes`: Remove it to fix potential eye issues using custom Link models
- `L Button`: Remove it if you prefer having Z button textures
- `New Gerudo Symbol`: Remove it if you prefer the old Crescent Moon symbol


## Generate from PNG source
1. Install SoH by generating as many `.otr` files as possible using supported ROMs. Check the SoH readme for supported versions.
2. Download [retro](https://github.com/GhostlyDark/retro/releases) (v0.0.5 or newer). Use the one linked here with disabled compression to avoid stuttering issues.
3. Click `Create OTR -> Replace Textures -> No`, then select all available `.otr` files at the same time. This will extract the textures from all archives and generates a `manifest.json`.
4. The compiled `manifest.json` needs to be copied into the directory that contains HD textures, mirroring the file structure of the extracted files. Overwrite any `.json` files included in this repository.
5. Choose `Create OTR -> Replace Textures -> Yes` and select the folder containing HD textures.
6. It is recommended to prepend `alt/` before staging textures. This allows assets to be toggled on-the-fly.
7. `Finalize OTR` as the final step.
