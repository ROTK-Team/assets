# fix(assets): restore stock controls and repair menu visuals

Restore the stock console and Shift-only item quantity selection. Correct customization selection, emote previews and hover descriptions.

Include the existing AK compatibility and muzzle fixes, and keep the removal of the red background behind Back. Defer the Solo replay/lobby change and do not add custom reticles or weapon-slot settings.

Existing skins and unrelated menu changes are preserved. This asset release must be coordinated with launcher 2.0.29 and matching server integrity policies.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,617,451 bytes, sha256 `b2bcf55985dda3bc7f09d6ac079fd7c062a7b32f7383c5dc5468a12ea0fed4f1`)
  - `Resources/Assets/assets_x64_0.pack2`: 12 changed, 1 added
    - changed: `adr/weap/Weapons_AK47.adr`, `adr/weap/Weapons_AK47_3P.adr`, `dx11efb/fog/fog.dx11efb`, `dx11efb/zone/ZoneVisualization.dx11efb`, `fxd/mzl_/Mzl_AK47.fxd`, `fxd/mzl_/Mzl_AK47_Ironsights_02.fxd`, `fxd/shel/ShellCasing_AK47.fxd`, `gfx/back/BackgroundWindow.gfx`, `gfx/butt/ButtonLegendWindow.gfx`, `gfx/cust/CustomizationWindow.gfx`, `gfx/uiro/UIRoot.gfx`, `xml/acto/ActorSockets.xml`
    - added: `mrn/ak47/AK47ClassicROTKX64.mrn`
- `data_x64_0` -> `data_x64_0.payload` (60,927,248 bytes, sha256 `cdf712ce8258a61fc6a4fc4e7522ac0e823fc73fd5507a1c4f853b5d55b3ce64`)
  - `Resources/Assets/data_x64_0.pack2`: 23 changed, 68 added
    - changed: `dds/BackpackKotk_Uncat_DT.dds`, `dds/HelmetKotk_SkullBlack_DT.dds`, `dds/HoodieKotk_AkerBlack_DT.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Hoodie_Kotk_AkerBlack.dds`, `dds/Icon_Wear_SurvivorMale_Legs_Pants_Kotk_AkerBlack.dds`, `dds/PantsKotk_AkerBlack_DT.dds`, `dds/TshirtKotk_PleasantValleyEagle_DT.dds`, `txt/AcctItemConversionGroupMappings.txt`, `txt/AcctItemConversionInputItems.txt`, `txt/AcctItemConversions.txt`, `txt/ClientItemDefinitions.txt`, `txt/CodeStringMappings.txt`, `txt/ImageSetMappings.txt`, `txt/ImageSets.txt`, `txt/Images.txt`, `txt/ItemClassMappings.txt`, `txt/ItemDatasheetPropertyMap.txt`, `txt/ItemIdUseOptionGroupId.txt`, `txt/ItemSourceLookup.txt`, `txt/MenuItem.txt`, `txt/PropertySetMapping.txt`, `txt/VehicleSkinMods.txt`, `xml/ActorModelMaterialDefinitions.xml`
    - added: `dds/BackpackKotk_AkerPink_DT.dds`, `dds/BackpackKotk_ManSportGold_DT.dds`, `dds/BackpackKotk_ManSportShark_DT.dds`, `dds/BackpackKotk_PunkMilitary_DT.dds`, `dds/BandanaKotk_Sakura_DT.dds`, `dds/EyePatchKotk_KickBlack_DT.dds`, `dds/GlovesKotk_BlueCamo_DT.dds`, `dds/GlovesKotk_Inferno_DT.dds`, `dds/HatKotk_AviatorBlack_DT.dds`, `dds/HatKotk_AviatorWhite_DT.dds`, `dds/HelmetKotk_KickRotk_DT.dds`, `dds/HelmetKotk_MotoCrossInferno_DT.dds`, `dds/HelmetKotk_MotoCrossPink_DT.dds`, `dds/HoodieKotk_Bone_DT.dds`, `dds/HoodieKotk_Eryc_DT.dds`, `dds/HoodieKotk_Inferno_DT.dds`, `dds/Icon_Vehicle_Offroader_Kotk_Kick.dds`, `dds/Icon_Vehicle_Parachute_Kotk_Kick.dds`, `dds/Icon_Weapons_Kotk_AyeZeeChampionAR15.dds`, `dds/Icon_Weapons_Kotk_ScarletCloudsAR15.dds`, `dds/Icon_Wear_SurvivorMale_Back_Backpack_Kotk_AkerPink.dds`, `dds/Icon_Wear_SurvivorMale_Back_Backpack_Kotk_ManSportGold.dds`, `dds/Icon_Wear_SurvivorMale_Back_Backpack_Kotk_ManSportShark.dds`, `dds/Icon_Wear_SurvivorMale_Back_Backpack_Kotk_PunkMilitary.dds`, `dds/Icon_Wear_SurvivorMale_Back_Satchel_Kotk_SpkbTurret.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Hoodie_Kotk_Bone.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Hoodie_Kotk_Eryc.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Hoodie_Kotk_Inferno.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Jacket_Kotk_TacticalMotocross.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Shirt_Kotk_Card.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Shirt_Kotk_UmiChucky.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Shirt_Kotk_Wave.dds`, `dds/Icon_Wear_SurvivorMale_Eyes_EyePatch_Kotk_KickBlack.dds`, `dds/Icon_Wear_SurvivorMale_Face_Bandana_Kotk_Sakura.dds`, `dds/Icon_Wear_SurvivorMale_Hands_Gloves_Kotk_BlueCamo.dds`, `dds/Icon_Wear_SurvivorMale_Hands_Gloves_Kotk_Inferno.dds`, `dds/Icon_Wear_SurvivorMale_Head_Hat_Kotk_AviatorBlack.dds`, `dds/Icon_Wear_SurvivorMale_Head_Hat_Kotk_AviatorWhite.dds`, `dds/Icon_Wear_SurvivorMale_Head_Helmet_Kotk_KickRotk.dds`, `dds/Icon_Wear_SurvivorMale_Head_Helmet_Kotk_MotoCrossInferno.dds` and 28 more
- `locale_rotk` -> `locale_rotk.payload` (4,088,438 bytes, sha256 `7dd5d4943e7a11f2e50fc1416234dd76ab7d3ddb86b0cf1694634001aa9249f8`)
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
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,142,995 bytes, sha256 `8084e9f9105b3d8cb6b38e0caa1679e4e2b62efac0a6050528cce1f3a3093501`)
  - `Resources/Assets/ui_x64_0.pack2`: 2 changed
    - changed: `gfx/MapWindow.gfx`, `gfx/UIRoot.gfx`
  - `Resources/Assets/ui_x64_2.pack2`: 9 changed
    - changed: `gfx/CustomizationWindow.gfx`, `gfx/SettingsAudioInGameWindow.gfx`, `gfx/SettingsAudioPreGameWindow.gfx`, `gfx/SettingsGameplayInGameWindow.gfx`, `gfx/SettingsGameplayPreGameWindow.gfx`, `gfx/SettingsGraphicsInGameWindow.gfx`, `gfx/SettingsGraphicsPreGameWindow.gfx`, `gfx/SettingsKeybindingsInGameWindow.gfx`, `gfx/SettingsKeybindingsPreGameWindow.gfx`
- `rotk_input_default` -> `InputProfile_Default.xml` (48,083 bytes, sha256 `15e75673e394df2a6c2db82d0ee5a347a1d577d82f27bf2222d8992be3abbde4`)
  - `InputProfile_Default.xml`: changed
