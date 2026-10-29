# Assets 1.13.55 — Police siren hitbox, Chinese taxi and daylight again

Three changes on top of the live assets 1.13.54.

Restores the police car siren collision in `Common_Vehicle_PoliceCar01_COL.apx` of `assets_x64_2`: bullets no longer go through the light bar on the roof. The `siren` shape comes from the old client; the other 19 shapes are unchanged and windows stay passable.

Gives the police car its taxi roof sign back for players whose game is in Chinese (`assets_x64_0`). `Common_Vehicle_PoliceCar_Tintable_01.CN.adr` now points at the old sedan that still has the "CABco" sign, added as `Common_Vehicle_PoliceCar_Tintable_01_CN_*`, and the taxi is seen at the same distance as the police car. The siren collision covers the sign. Other languages keep the police car. The launcher still starts the game in English when it is set to Chinese.

Reverts the Z1BR night of 1.13.53 (#69) in `Lighting_Z2_PS3.txt` of `assets_x64_0`. Public lobbies at the default hour looked washed out, and street lamps, car boosts and animated skins bloomed at night. Every hour is full daylight again, as before 1.13.53. Night comes back later with its own exposure.

Validated in game in the isolated two-client harness, one client in English and one in Chinese: police car and taxi, bullets stopped by the siren and the sign, full daylight.

Assets only: no server release goes with it.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,328,395,588 bytes, sha256 `1f9bbdf4f47109afc36666d4fb42458a3550856a055f353625c3d5290ff74fb8`)
  - `Resources/Assets/assets_x64_0.pack2`: 2 changed, 8 added
    - changed: `adr/comm/Common_Vehicle_PoliceCar_Tintable_01.CN.adr`, `txt/ligh/Lighting_Z2_PS3.txt`
    - added: `dma/comm/Common_Vehicle_PoliceCar_Tintable_01_CN_Lod0.dma`, `dma/comm/Common_Vehicle_PoliceCar_Tintable_01_CN_Lod1.dma`, `dma/comm/Common_Vehicle_PoliceCar_Tintable_01_CN_Lod2.dma`, `dma/comm/Common_Vehicle_PoliceCar_Tintable_01_CN_Lod3.dma`, `dme/comm/Common_Vehicle_PoliceCar_Tintable_01_CN_LOD0.dme`, `dme/comm/Common_Vehicle_PoliceCar_Tintable_01_CN_LOD1.dme`, `dme/comm/Common_Vehicle_PoliceCar_Tintable_01_CN_LOD2.dme`, `dme/comm/Common_Vehicle_PoliceCar_Tintable_01_CN_LOD3.dme`
- `data_x64_0` -> `data_x64_0.payload` (229,300,149 bytes, sha256 `aa5d1900193d2486998d9dc91af134fb05d2dec7d334ad2fef1dd5003a94eb95`)
  - `Resources/Assets/data_x64_0.pack2`: 1 changed
    - changed: `txt/ClientItemDefinitions.txt`
- `assets_x64_2` -> `assets_x64_2.payload` (475,929,888 bytes, sha256 `19d1ae23c119efc015863a88628418a9fe1f821cc66fb661adbf1546fe69932c`)
  - `Resources/Assets/assets_x64_2.pack2`: 1 changed
    - changed: `apx/comm/Common_Vehicle_PoliceCar01_COL.apx`
