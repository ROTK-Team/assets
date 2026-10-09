# Crosshair, weapon slots and official menu cameras

Deliver the owner-tested combined client: complete per-weapon Crosshair profiles and eleven translations, durable weapon-slot preferences in Gameplay before and during a match, and the original helicopter lobby with official menu views and ATV poses.

The shared Gameplay panels preserve all three features. Every other entry in the rebuilt live 1.13.36 packs, including spectator and death-screen fixes, remains unchanged. Stock LoginZone resources restore the authored scene.

Requires the coordinated server release 1.5.8 for nonce-correlated slot saves and official camera projections. The prior camera-only 1.13.37 draft is superseded by this complete candidate; no existing tag or published release is replaced.

Experimental four/five-member fixtures and native DLLs are excluded. Production party capacity remains Solo/Duo/Trio. The authored framing retains the known crop on the rightmost ATV.

Publish the draft release before merging its distribution PR, then publish the matching integrity policy according to the repository workflow.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,628,097 bytes, sha256 `d33cd7c747390404e350edd4390b8c2f2ae1f54f9d88dea1c489157e95c95d78`)
  - `Resources/Assets/assets_x64_0.pack2`: 2 changed
    - changed: `gfx/back/BackgroundWindow.gfx`, `gfx/hudr/HudReticleWindow.gfx`
- `assets_x64_1` -> `assets_x64_1.payload` (128,031,563 bytes, sha256 `236f8312c567cee0ba80001016d6f7709cfaf4bd779e85fa3f0719556556ab3a`)
  - `Resources/Assets/assets_x64_1.pack2`: 1 changed
    - changed: `gfx/hudr/HudReticleWindow.gfx`
- `loginzone_x64_0` -> `loginzone_x64_0.payload` (27,026,147 bytes, sha256 `c7f11c2fec629de3a3a7bb93204e67f935d235b196e343539a070ec35f9a24e8`)
  - `Resources/Assets/LoginZone_x64_0.pack2`: 38 changed, 43 removed
    - changed: `cnk/LoginZone_-4_-8_1.cnk`, `cnk/LoginZone_-8_-8_2.cnk`, `cnk/LoginZone_-8_-8_3.cnk`, `cnk/LoginZone_-8_4_1.cnk`, `cnk/LoginZone_0_0_1.cnk`, `cnk/LoginZone_0_0_2.cnk`, `cnk/LoginZone_0_4_0.cnk`, `cnk/LoginZone_4_-4_0.cnk`, `cnk/LoginZone_4_-4_1.cnk`, `cnk/LoginZone_4_-8_0.cnk`, `cnk/LoginZone_4_-8_1.cnk`, `cnk/LoginZone_4_0_0.cnk`, `cnk/LoginZone_4_0_1.cnk`, `cnk/LoginZone_4_4_0.cnk`, `cnk/LoginZone_4_4_1.cnk`, `ctg_pc/LoginZone_-4_-8_0.ctg_pc`, `ctg_pc/LoginZone_-4_-8_1.ctg_pc`, `ctg_pc/LoginZone_-4_0_0.ctg_pc`, `ctg_pc/LoginZone_-4_4_0.ctg_pc`, `ctg_pc/LoginZone_-4_4_1.ctg_pc`, `ctg_pc/LoginZone_-8_-4_1.ctg_pc`, `ctg_pc/LoginZone_-8_-8_0.ctg_pc`, `ctg_pc/LoginZone_-8_-8_2.ctg_pc`, `ctg_pc/LoginZone_-8_-8_3.ctg_pc`, `ctg_pc/LoginZone_-8_0_1.ctg_pc`, `ctg_pc/LoginZone_-8_4_0.ctg_pc`, `ctg_pc/LoginZone_-8_4_1.ctg_pc`, `ctg_pc/LoginZone_0_-4_0.ctg_pc`, `ctg_pc/LoginZone_0_-8_2.ctg_pc`, `ctg_pc/LoginZone_0_0_0.ctg_pc`, `ctg_pc/LoginZone_0_0_1.ctg_pc`, `ctg_pc/LoginZone_4_-4_0.ctg_pc`, `ctg_pc/LoginZone_4_-4_1.ctg_pc`, `ctg_pc/LoginZone_4_4_1.ctg_pc`, `tome/LoginZone_-1_0.tome`, `tome/LoginZone_0_-1.tome`, `zone/LoginZone.zone`, `{NAMELIST}`
    - removed: `cnk/LoginZone_-4_-4_0.cnk`, `cnk/LoginZone_-4_-4_1.cnk`, `cnk/LoginZone_-4_-8_0.cnk`, `cnk/LoginZone_-4_0_0.cnk`, `cnk/LoginZone_-4_0_1.cnk`, `cnk/LoginZone_-4_4_0.cnk`, `cnk/LoginZone_-4_4_1.cnk`, `cnk/LoginZone_-8_-4_0.cnk`, `cnk/LoginZone_-8_-4_1.cnk`, `cnk/LoginZone_-8_-8_0.cnk`, `cnk/LoginZone_-8_-8_1.cnk`, `cnk/LoginZone_-8_0_0.cnk`, `cnk/LoginZone_-8_0_1.cnk`, `cnk/LoginZone_-8_0_2.cnk`, `cnk/LoginZone_-8_4_0.cnk`, `cnk/LoginZone_0_-4_0.cnk`, `cnk/LoginZone_0_-4_1.cnk`, `cnk/LoginZone_0_-8_0.cnk`, `cnk/LoginZone_0_-8_1.cnk`, `cnk/LoginZone_0_-8_2.cnk`, `cnk/LoginZone_0_0_0.cnk`, `cnk/LoginZone_0_4_1.cnk`, `ctg_pc/LoginZone_-4_-4_0.ctg_pc`, `ctg_pc/LoginZone_-4_-4_1.ctg_pc`, `ctg_pc/LoginZone_-4_0_1.ctg_pc`, `ctg_pc/LoginZone_-8_-4_0.ctg_pc`, `ctg_pc/LoginZone_-8_-8_1.ctg_pc`, `ctg_pc/LoginZone_-8_0_0.ctg_pc`, `ctg_pc/LoginZone_-8_0_2.ctg_pc`, `ctg_pc/LoginZone_0_-4_1.ctg_pc`, `ctg_pc/LoginZone_0_-8_0.ctg_pc`, `ctg_pc/LoginZone_0_-8_1.ctg_pc`, `ctg_pc/LoginZone_0_0_2.ctg_pc`, `ctg_pc/LoginZone_0_4_0.ctg_pc`, `ctg_pc/LoginZone_0_4_1.ctg_pc`, `ctg_pc/LoginZone_4_-8_0.ctg_pc`, `ctg_pc/LoginZone_4_-8_1.ctg_pc`, `ctg_pc/LoginZone_4_0_0.ctg_pc`, `ctg_pc/LoginZone_4_0_1.ctg_pc`, `ctg_pc/LoginZone_4_4_0.ctg_pc` and 3 more
- `loginzone_x64_1` -> `loginzone_x64_1.payload` (27,828,148 bytes, sha256 `087f512273017663fa2d5affb1206487b0836eefd4d8f64f232dd948829d27b0`)
  - `Resources/Assets/LoginZone_x64_1.pack2`: 60 changed, 37 removed
    - changed: `cel/LoginZone_cell_0_-1_-1.cel`, `cel/LoginZone_cell_0_-1_-2.cel`, `cel/LoginZone_cell_0_-1_0.cel`, `cel/LoginZone_cell_0_-1_1.cel`, `cel/LoginZone_cell_0_-2_-1.cel`, `cel/LoginZone_cell_0_-2_-2.cel`, `cel/LoginZone_cell_0_-2_0.cel`, `cel/LoginZone_cell_0_-2_1.cel`, `cel/LoginZone_cell_0_0_-1.cel`, `cel/LoginZone_cell_0_0_-2.cel`, `cel/LoginZone_cell_0_0_0.cel`, `cel/LoginZone_cell_0_0_1.cel`, `cel/LoginZone_cell_0_1_-1.cel`, `cel/LoginZone_cell_0_1_-2.cel`, `cel/LoginZone_cell_0_1_0.cel`, `cel/LoginZone_cell_0_1_1.cel`, `cnk/LoginZone_-4_-4_0.cnk`, `cnk/LoginZone_-4_-4_1.cnk`, `cnk/LoginZone_-4_-8_0.cnk`, `cnk/LoginZone_-4_0_0.cnk`, `cnk/LoginZone_-4_0_1.cnk`, `cnk/LoginZone_-4_4_0.cnk`, `cnk/LoginZone_-4_4_1.cnk`, `cnk/LoginZone_-8_-4_0.cnk`, `cnk/LoginZone_-8_-4_1.cnk`, `cnk/LoginZone_-8_-8_0.cnk`, `cnk/LoginZone_-8_-8_1.cnk`, `cnk/LoginZone_-8_0_0.cnk`, `cnk/LoginZone_-8_0_1.cnk`, `cnk/LoginZone_-8_0_2.cnk`, `cnk/LoginZone_-8_4_0.cnk`, `cnk/LoginZone_0_-4_0.cnk`, `cnk/LoginZone_0_-4_1.cnk`, `cnk/LoginZone_0_-8_0.cnk`, `cnk/LoginZone_0_-8_1.cnk`, `cnk/LoginZone_0_-8_2.cnk`, `cnk/LoginZone_0_0_0.cnk`, `cnk/LoginZone_0_4_1.cnk`, `ctg_pc/LoginZone_-4_-4_0.ctg_pc`, `ctg_pc/LoginZone_-4_-4_1.ctg_pc` and 20 more
    - removed: `cnk/LoginZone_-4_-8_1.cnk`, `cnk/LoginZone_-8_-8_2.cnk`, `cnk/LoginZone_-8_-8_3.cnk`, `cnk/LoginZone_-8_4_1.cnk`, `cnk/LoginZone_0_0_1.cnk`, `cnk/LoginZone_0_0_2.cnk`, `cnk/LoginZone_0_4_0.cnk`, `cnk/LoginZone_4_-4_0.cnk`, `cnk/LoginZone_4_-4_1.cnk`, `cnk/LoginZone_4_-8_0.cnk`, `cnk/LoginZone_4_-8_1.cnk`, `cnk/LoginZone_4_0_0.cnk`, `cnk/LoginZone_4_0_1.cnk`, `cnk/LoginZone_4_4_0.cnk`, `cnk/LoginZone_4_4_1.cnk`, `ctg_pc/LoginZone_-4_-8_0.ctg_pc`, `ctg_pc/LoginZone_-4_-8_1.ctg_pc`, `ctg_pc/LoginZone_-4_0_0.ctg_pc`, `ctg_pc/LoginZone_-4_4_0.ctg_pc`, `ctg_pc/LoginZone_-4_4_1.ctg_pc`, `ctg_pc/LoginZone_-8_-4_1.ctg_pc`, `ctg_pc/LoginZone_-8_-8_0.ctg_pc`, `ctg_pc/LoginZone_-8_-8_2.ctg_pc`, `ctg_pc/LoginZone_-8_-8_3.ctg_pc`, `ctg_pc/LoginZone_-8_0_1.ctg_pc`, `ctg_pc/LoginZone_-8_4_0.ctg_pc`, `ctg_pc/LoginZone_-8_4_1.ctg_pc`, `ctg_pc/LoginZone_0_-4_0.ctg_pc`, `ctg_pc/LoginZone_0_-8_2.ctg_pc`, `ctg_pc/LoginZone_0_0_0.ctg_pc`, `ctg_pc/LoginZone_0_0_1.ctg_pc`, `ctg_pc/LoginZone_4_-4_0.ctg_pc`, `ctg_pc/LoginZone_4_-4_1.ctg_pc`, `ctg_pc/LoginZone_4_4_1.ctg_pc`, `tome/LoginZone_-1_0.tome`, `tome/LoginZone_0_-1.tome`, `zone/LoginZone.zone`
- `locale_rotk` -> `locale_rotk.payload` (4,099,670 bytes, sha256 `a3a1a737f2df7d78eac2390b216e3fa390f248072812057ebc6bb2428358297d`)
  - `Locale/de_de_data.dat`: changed
  - `Locale/de_de_data.dir`: changed
  - `Locale/en_us_data.dat`: changed
  - `Locale/en_us_data.dir`: changed
  - `Locale/es_es_data.dat`: changed
  - `Locale/es_es_data.dir`: changed
  - `Locale/fr_fr_data.dat`: changed
  - `Locale/fr_fr_data.dir`: changed
  - `Locale/ja_jp_data.dat`: changed
  - `Locale/ja_jp_data.dir`: changed
  - `Locale/ko_kr_data.dat`: changed
  - `Locale/ko_kr_data.dir`: changed
  - `Locale/pt_br_data.dat`: changed
  - `Locale/pt_br_data.dir`: changed
  - `Locale/ru_ru_data.dat`: changed
  - `Locale/ru_ru_data.dir`: changed
  - `Locale/th_th_data.dat`: changed
  - `Locale/th_th_data.dir`: changed
  - `Locale/tr_tr_data.dat`: changed
  - `Locale/tr_tr_data.dir`: changed
  - `Locale/zh_cn_data.dat`: changed
  - `Locale/zh_cn_data.dir`: changed
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,193,201 bytes, sha256 `415b3a9029c6c1f9812e0543ace7ee1d080aa1e9f1538f1a5e3dbdebc835e4c7`)
  - `Resources/Assets/ui_x64_0.pack2`: no entry changed (rebuilt with its payload)
  - `Resources/Assets/ui_x64_2.pack2`: 7 changed
    - changed: `gfx/BackgroundWindow.gfx`, `gfx/SettingsAudioPreGameWindow.gfx`, `gfx/SettingsGameplayInGameWindow.gfx`, `gfx/SettingsGameplayPreGameWindow.gfx`, `gfx/SettingsGraphicsPreGameWindow.gfx`, `gfx/SettingsKeybindingsPreGameWindow.gfx`, `gfx/SettingsRegionSelectionPreGameWindow.gfx`
- `cz_death_ui` -> `cz_death_ui.payload` (41,996,175 bytes, sha256 `0d64117be6e2290b2bf832a113aca376da74a76652d6703a1614ffe44f651ab3`)
  - `Resources/Assets/ui_x64_3.pack2`: 1 changed
    - changed: `gfx/HudReticleWindow.gfx`
