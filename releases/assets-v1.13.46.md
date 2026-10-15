# Assets 1.13.46 — Spider-Man, native FPS, Trio recovery and kill feed

Adds the Spider-Man hoodie, SkinnyStraightLeg pants and Zodiac mask with dedicated textures, icons and localized names. Combines native rendered FPS, centered binocular reticles and Trio reboot map recovery, retaining the yellow pulsing knocked-teammate HUD shipped in 1.13.45.

The kill feed no longer retains removed pool nodes (both copies of `HudKillFeedWindow.gfx`). This fixes a reproduced memory-retention defect; a native Solo/Duos/Trios frametime A/B test is still needed before calling the stutter fixed.

Requires the coordinated launcher 2.0.39 and server 1.5.15. Built by the release workflow from the live 1.13.45 baseline; every unrelated packed entry and all other payload references are preserved. Sources: ROTK-Team/assets-unpacked#56 and ROTK-Team/assets-unpacked#57.

Replaces the privately built 1.13.46 draft (same changes without the kill feed fix) and the unpublished 1.13.43 draft, whose armor indicators shipped in 1.13.44.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,663,378 bytes, sha256 `f54fe909c0955b7b1c5bc132afd1e857937b928346575396db976ece6a15a8ec`)
  - `Resources/Assets/assets_x64_0.pack2`: 2 changed
    - changed: `gfx/hudr/HudReticleWindow.gfx`, `gfx/uiro/UIRoot.gfx`
- `assets_x64_1` -> `assets_x64_1.payload` (128,034,899 bytes, sha256 `8000d6265480413722eebb602f8f3f1332566031f5fdcf468e9ad0e0938891a2`)
  - `Resources/Assets/assets_x64_1.pack2`: 2 changed
    - changed: `gfx/hudk/HudKillFeedWindow.gfx`, `gfx/hudr/HudReticleWindow.gfx`
- `data_x64_0` -> `data_x64_0.payload` (69,218,627 bytes, sha256 `5390931248da77de5e1429574a194f9c324ab94e035ffbab6f25437dedf73e1b`)
  - `Resources/Assets/data_x64_0.pack2`: 12 changed, 6 added
    - changed: `txt/AcctItemConversionGroupMappings.txt`, `txt/AcctItemConversionInputItems.txt`, `txt/AcctItemConversions.txt`, `txt/ClientItemDefinitions.txt`, `txt/ImageSetMappings.txt`, `txt/ImageSets.txt`, `txt/Images.txt`, `txt/ItemClassMappings.txt`, `txt/ItemDatasheetPropertyMap.txt`, `txt/ItemIdUseOptionGroupId.txt`, `txt/ItemSourceLookup.txt`, `txt/PropertySetMapping.txt`
    - added: `dds/HoodieKotk_SpiderMan_DT.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Hoodie_Kotk_SpiderMan.dds`, `dds/Icon_Wear_SurvivorMale_Head_Mask_Kotk_SpiderMan.dds`, `dds/Icon_Wear_SurvivorMale_Legs_Pants_Kotk_SpiderMan.dds`, `dds/MaskKotk_SpiderMan_DT.dds`, `dds/PantsKotk_SpiderMan_DT.dds`
- `locale_rotk` -> `locale_rotk.payload` (4,101,012 bytes, sha256 `b6d233aebebca37d53dea8f76ef14a759644fb8bad355a40d81c845b7d0a6129`)
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
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,173,258 bytes, sha256 `9ea92e214183207b54e52d4c12d6214c38514f7f02aa22b222e8449797bd80ef`)
  - `Resources/Assets/ui_x64_0.pack2`: 3 changed
    - changed: `gfx/HudKillFeedWindow.gfx`, `gfx/MapWindow.gfx`, `gfx/UIRoot.gfx`
  - `Resources/Assets/ui_x64_2.pack2`: no entry changed (rebuilt with its payload)
- `cz_death_ui` -> `cz_death_ui.payload` (42,006,685 bytes, sha256 `58542ae08af8ae350d24ef8749f495b66237ace28bfe92a715ac3193d4be7595`)
  - `Resources/Assets/ui_x64_3.pack2`: 1 changed
    - changed: `gfx/HudReticleWindow.gfx`
