# Assets 1.13.51 — Batch 9 cosmetics and ROTK crates

Adds cosmetic waves 40 and 41: 57 texture skins, 16 animated weapon skins and 3D garments, and updated retail looks. Includes the wrist watch and No Watch selection, Satchel customization, Imperial reflections, RizaaR frost effects, and Scarlet Clouds V5 materials.

Adds the Halloween 2026 Crate and ROTK Season 1 Crate with their icons, menu tabs and localized labels. Updates ROTK and retail rarities and restores PC visibility for the supported crate rewards.

Restores Solo Play Again: the native menu waits for mode availability, tutorial qualification and the world list, then launches the ordinary Solo action once. Exit match keeps returning to the menu. The replay change from review PR #65 is ported onto both current menu variants.

Built on the current live assets 1.13.50. The cosmetics and crate flows were validated in the isolated two-client harness during preparation.

Release preparation only: keep this release and the launcher feed pull request in draft until the coordinated client/server rollout is approved. Server migrations, activation and production attestation remain pending.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,707,593 bytes, sha256 `04f6127051ecb107a777ae75060786b5bc1827e2292a3746c2da524ee8a8e7ee`)
  - `Resources/Assets/assets_x64_0.pack2`: 3 changed
    - changed: `gfx/uiro/UIRoot.gfx`, `xml/acto/ActorCompositeEffectDefinitions.xml`, `xml/acto/ActorSockets.xml`
- `assets_x64_1` -> `assets_x64_1.payload` (128,071,546 bytes, sha256 `c6d716a504503dd27f17874a29a15ace54fdef8ac9e48572fc97269cc93e0581`)
  - `Resources/Assets/assets_x64_1.pack2`: 1 changed
    - changed: `xml/acto/ActorSockets.xml`
- `data_x64_0` -> `data_x64_0.payload` (198,342,414 bytes, sha256 `d1c6a6fe513d69230556ed4d04969b13130a1a47da3675be7ce377442d5dbd86`)
  - `Resources/Assets/data_x64_0.pack2`: 27 changed, 349 added
    - changed: `dds/WeaponKotk_ScarletCloudsAR15_DT.dds`, `txt/AcctItemConversionGroupMappings.txt`, `txt/AcctItemConversionInputGroups.txt`, `txt/AcctItemConversionInputItems.txt`, `txt/AcctItemConversions.txt`, `txt/ClientItemDefinitions.txt`, `txt/EmoteAnimations.txt`, `txt/EquipmentSlotDefinitions.txt`, `txt/FirstPersonAttachments.txt`, `txt/ImageSetMappings.txt`, `txt/ImageSets.txt`, `txt/Images.txt`, `txt/ItemClassMappings.txt`, `txt/ItemClasses.txt`, `txt/ItemDatasheetPropertyMap.txt`, `txt/ItemIdUseOptionGroupId.txt`, `txt/ItemSourceLookup.txt`, `txt/Models.txt`, `txt/PropertySetMapping.txt`, `txt/SkinItemSlot.txt`, `txt/SkinItemSlotItem.txt`, `txt/VehicleSkinMods.txt`, `xml/ActorCompositeEffectDefinitions.xml`, `xml/ActorFxDefinitions.xml`, `xml/ActorModelMaterialDefinitions.xml`, `xml/ActorSockets.xml`, `xml/materials_3.xml`
    - added: `adr/SurvivorFemale_Back_Backpack_Kotk_Sacoche.adr`, `adr/SurvivorFemale_Face_Mask_Kotk_Clown.adr`, `adr/SurvivorFemale_Feet_Kotk_Running.adr`, `adr/SurvivorFemale_Feet_Kotk_Skate.adr`, `adr/SurvivorFemale_Hands_Kotk_WatchSteel.adr`, `adr/SurvivorFemale_Head_Helmet_Kotk_Umi.adr`, `adr/SurvivorMale_Back_Backpack_Kotk_Sacoche.adr`, `adr/SurvivorMale_Face_Mask_Kotk_Clown.adr`, `adr/SurvivorMale_Feet_Kotk_Running.adr`, `adr/SurvivorMale_Feet_Kotk_Skate.adr`, `adr/SurvivorMale_Hands_Kotk_WatchSteel.adr`, `adr/SurvivorMale_Head_Helmet_Kotk_Umi.adr`, `adr/Weapons_AK47_KotkAyeZee.adr`, `adr/Weapons_AK47_KotkAyeZee_3P.adr`, `adr/Weapons_AK47_KotkPrint.adr`, `adr/Weapons_AK47_KotkPrint_3P.adr`, `adr/Weapons_AR15_KotkAyeZee.adr`, `adr/Weapons_AR15_KotkAyeZee_3P.adr`, `adr/Weapons_AR15_KotkPrint.adr`, `adr/Weapons_AR15_KotkPrint_3P.adr`, `adr/Weapons_AR15_KotkRizaar.adr`, `adr/Weapons_AR15_KotkRizaar_3P.adr`, `adr/Weapons_AR15_KotkScarlet.adr`, `adr/Weapons_AR15_KotkScarlet_3P.adr`, `adr/Weapons_M40Sniper_KotkPrint.adr`, `adr/Weapons_M40Sniper_KotkPrint_3P.adr`, `adr/Weapons_RiotShotgun_KotkAyeZee.adr`, `adr/Weapons_RiotShotgun_KotkAyeZee_3P.adr`, `adr/Weapons_RiotShotgun_KotkImperial.adr`, `adr/Weapons_RiotShotgun_KotkImperial_3P.adr`, `adr/Weapons_RiotShotgun_KotkNautilus.adr`, `adr/Weapons_RiotShotgun_KotkNautilus_3P.adr`, `adr/Weapons_RiotShotgun_KotkSnowGlobe.adr`, `adr/Weapons_RiotShotgun_KotkSnowGlobe_3P.adr`, `dds/ArmorKotk_Kitsune_DT.dds`, `dds/BackpackKotk_AyeZeeChampion_DT.dds`, `dds/BackpackKotk_Bob_DT.dds`, `dds/BackpackKotk_Dfg_DT.dds`, `dds/BackpackKotk_Kiddy_DT.dds`, `dds/BackpackKotk_Pat_DT.dds` and 309 more
- `locale_rotk` -> `locale_rotk.payload` (4,127,935 bytes, sha256 `55106d7e0fa5430164d3048a8d8757d25b9b223d43ae0a2dee0787e32f7c25d8`)
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
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,221,827 bytes, sha256 `cd4d030705ee46dfdab767168394daff95748431e133d967f7b6585dc06413f1`)
  - `Resources/Assets/ui_x64_0.pack2`: 1 changed
    - changed: `gfx/UIRoot.gfx`
  - `Resources/Assets/ui_x64_2.pack2`: no entry changed (rebuilt with its payload)
