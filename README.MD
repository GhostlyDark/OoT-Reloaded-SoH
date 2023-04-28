# OoT Reloaded (SoH)
Ocarina of Time Reloaded texture pack for the Ocarina of Time PC port: Ship of Harkinian.


## Use OTR file
Requires at least SoH `v7.0.0`. The OTR file goes into the `mods` directory.

While in-game, unhide the menubar with F1 and activate `Enhancements -> Graphics -> Use Alternate Assets`.

Prebuilt OTR files may not work using other than the targeted SoH releases, in which case generating a new OTR is required.


## Generate from PNG source
1) Install SoH by generating both `oot.otr` and `oot-mq.otr` using:

```
Legend of Zelda, The - Ocarina of Time (Europe) (GameCube).z64 (MD5: 2c27b4e000e85fd78dbca551f1b1c965)
Legend of Zelda, The - Ocarina of Time - Master Quest (USA) (Debug Version).z64 (MD5: 8ca71e87de4ce5e9f6ec916202a623e9)
```

2. Use [retro](https://github.com/HarbourMasters64/retro/releases) (v0.0.5 or newer) to extract the original textures.
3. Click `Create OTR -> Replace Textures -> No`, then select all of `oot.otr`, `oot-mq.otr` and `soh.otr` at the same time. 
4. The extracted `manifest.json` needs to be copied into the directory containing HD textures.
5. Choose `Create OTR -> Replace Textures -> Yes` and select the folder containing both HD textures and the manifest.
6. If desired, activate `Prepend 'alt/'` before staging textures to be able to toggle assets on-the-fly.
7. `Finalize OTR` as the final step.
