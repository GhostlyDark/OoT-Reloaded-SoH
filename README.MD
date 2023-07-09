# OoT Reloaded (SoH)
Ocarina of Time Reloaded is an Ultra HD texture pack for [GLideN64](https://github.com/GhostlyDark/OoT-Reloaded) and Ship of Harkinian.


## Use OTR file
Requires at least SoH `v7.0.0`. The OTR file goes into the `mods` directory.


## Generate from PNG source
1. Install SoH by generating as many `.otr` files as possible using supported ROMs. Check the SoH readme for supported versions.
2. Download [retro](https://github.com/GhostlyDark/retro/releases) (v0.0.5 or newer). Use the one linked here with disabled compression to avoid stuttering issues.
3. Click `Create OTR -> Replace Textures -> No`, then select all available `.otr` files at the same time. This will extract the textures from all archives and generates a `manifest.json`.
4. The compiled `manifest.json` needs to be copied into the directory containing HD textures. Overwrite the one that is included in this repository.
5. Choose `Create OTR -> Replace Textures -> Yes` and select the folder containing both HD textures and the manifest.
6. One may prepend `alt/` before staging textures. This allows assets to be toggled on-the-fly, but may cause issues when used in conjunction with custom models.
7. `Finalize OTR` as the final step.

If `alt/` path was prepended, unhide the menu with F1 and click `Enhancements -> Graphics -> Use Alternate Assets` while in-game.
