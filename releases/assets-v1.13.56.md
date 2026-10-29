# Assets 1.13.56 — Image Settings menu, Exit game label and crosshair families

Three changes on top of the live assets 1.13.55.

Adds the **Image Settings** menu to Settings > Graphics (#78): an ON/OFF row with EDIT in `SettingsGraphicsPreGameWindow.gfx` and `SettingsGraphicsInGameWindow.gfx` of `ui_x64_2`, an editor with presets (None, Vivid, Contrast, Soft, Custom), five sliders, the colour-blind modes and RESET. Every change is written to `UserOptions.ini [UI] rotk_img_*`, read by the launcher's gameplay DLL (rotk-launcher 2.0.48). 24 strings (99016000–99016023) in the eleven locales and `CodeStringMappings.txt` of `data_x64_0`.

Labels the bottom menu button **Exit game** instead of EXIT Z1BR (#79): row 201718409 in the eleven locale tables, uppercase like the original. Checked in game in English, French and Chinese.

Covers the wave 41 and 42 firearm skins in the HUD weapon families (#80): the 13 skinned firearms added since 1.13.43 (Halloween, Royal Dragon, RizaaR, Kick, lets, Petit Boo and AyeZee Champion II AR-15s, Tempest and AyeZee AK-47s, AyeZee and Phantom shotguns, Imperial M24, hunting rifle 1899) take their own custom crosshair again instead of the ALL WEAPONS one. `HudReticleWindow.gfx` in `assets_x64_0`, `assets_x64_1` and `ui_x64_3`; only the seven family string constants change.

Ships with rotk-launcher 2.0.48 (image settings DLL, player fonts) and server 1.5.28.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,328,388,290 bytes, sha256 `e449b2f3ec25c5a4ecf8c826102b2d56a6eaf4ce2b4f5aad64206baf270b96c2`)
  - `Resources/Assets/assets_x64_0.pack2`: 1 changed
    - changed: `gfx/hudr/HudReticleWindow.gfx`
- `assets_x64_1` -> `assets_x64_1.payload` (128,077,509 bytes, sha256 `b7925245be6aea581c2343acb104450e91c3d20004f95fae4e015db5180ba048`)
  - `Resources/Assets/assets_x64_1.pack2`: 1 changed
    - changed: `gfx/hudr/HudReticleWindow.gfx`
- `data_x64_0` -> `data_x64_0.payload` (229,300,392 bytes, sha256 `2d5fdeb7a85a3e04196452c016cd9f7d21c9491e7b5265a9c26b4af2f832090c`)
  - `Resources/Assets/data_x64_0.pack2`: 1 changed
    - changed: `txt/CodeStringMappings.txt`
- `locale_rotk` -> `locale_rotk.payload` (5,059,154 bytes, sha256 `c3908a09896c9defc718b868a0666527d43ff48456447d08b2edee0e20eabe46`)
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
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,249,399 bytes, sha256 `9dfe6c9d77f6e196c6801fa7710ea96b152fca246c75c6b52d1ec5d426a762c3`)
  - `Resources/Assets/ui_x64_0.pack2`: no entry changed (rebuilt with its payload)
  - `Resources/Assets/ui_x64_2.pack2`: 2 changed
    - changed: `gfx/SettingsGraphicsInGameWindow.gfx`, `gfx/SettingsGraphicsPreGameWindow.gfx`
- `cz_death_ui` -> `cz_death_ui.payload` (42,008,466 bytes, sha256 `0cea0e878927a729f5b6107620029c54ae463261b76b072f81fd2801358e6c5b`)
  - `Resources/Assets/ui_x64_3.pack2`: 1 changed
    - changed: `gfx/HudReticleWindow.gfx`
