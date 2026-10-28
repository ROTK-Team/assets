# Assets 1.13.54 — Batch 10 cosmetics

Adds cosmetic wave 42: 32 skins and the 2Tap Me Pickup Truck vehicle skin from the designer's batch10 delivery.

- **T-shirts:** Boys Don't Cry, More Kill More Win, No Spray, Smile Pink, No Aim, Real Madrid ROTK, MMS, and the animated 20K Elite T-Shirt.
- **ROTK League:** Red, Ghost and Pink Ghost hoodies, pants and backpacks.
- **Armor:** Carbon Makeshift Armor and COSM Body Armor, the first ROTK laminated armor.
- **Helmets:** AyeZee Championship Tactical Helmet, Petit Boo Helmet, and the animated Elite MotoCross Helmet.
- **More gear:** Cory polo and shorts, Born to Cry polo and pants, Hellstar Pants, Shadowfang Backpack, and the new 3D Coffin Backpack and Glow Sunglasses.
- **Weapons:** animated Petit Boo AR-15 and AyeZee Champion Edition II AR-15.
- **Updated:** new icon for the Kick AR-15.

Rarities come from the rarity panel. Built on the live assets 1.13.53 and validated in game in the isolated two-client harness.

Pairs with the server release that applies migrations 0211/0212 of ROTK-Team/returnoftheking. Publish this release and its feed first, then tag the server.

## Changed assets

- `data_x64_0` -> `data_x64_0.payload` (229,300,139 bytes, sha256 `6159879d298056de59126723a58630206414cd73a5f7cc7e9cb81cd87e190856`)
  - `Resources/Assets/data_x64_0.pack2`: 16 changed, 93 added
    - changed: `dds/Icon_Weapons_Kotk_KickAR15.dds`, `txt/AcctItemConversionGroupMappings.txt`, `txt/AcctItemConversionInputItems.txt`, `txt/AcctItemConversions.txt`, `txt/ClientItemDefinitions.txt`, `txt/ImageSetMappings.txt`, `txt/ImageSets.txt`, `txt/Images.txt`, `txt/ItemClassMappings.txt`, `txt/ItemDatasheetPropertyMap.txt`, `txt/ItemIdUseOptionGroupId.txt`, `txt/ItemSourceLookup.txt`, `txt/Models.txt`, `txt/PropertySetMapping.txt`, `txt/VehicleSkinMods.txt`, `xml/ActorModelMaterialDefinitions.xml`
    - added: `adr/SurvivorFemale_Back_Backpack_Kotk_Coffin.adr`, `adr/SurvivorFemale_Chest_Shirt_TintTshirt_KotkPrint.adr`, `adr/SurvivorFemale_Eyes_Glasses_Kotk_GlowSunglasses.adr`, `adr/SurvivorFemale_Head_Helmet_MotoCross_KotkPrint.adr`, `adr/SurvivorMale_Back_Backpack_Kotk_Coffin.adr`, `adr/SurvivorMale_Chest_Shirt_TintTshirt_KotkPrint.adr`, `adr/SurvivorMale_Eyes_Glasses_Kotk_GlowSunglasses.adr`, `adr/SurvivorMale_Head_Helmet_MotoCross_KotkPrint.adr`, `dds/ArmorKotk_Carbon_DT.dds`, `dds/ArmorKotk_Cosm_DT.dds`, `dds/BackpackKotk_Coffin_DT.dds`, `dds/BackpackKotk_GhostRotkLeague_DT.dds`, `dds/BackpackKotk_PinkGhostRotkLeague_DT.dds`, `dds/BackpackKotk_RedRotkLeague_DT.dds`, `dds/BackpackKotk_Shadowfang_DT.dds`, `dds/GlassesKotk_GlowSunglasses_DT.dds`, `dds/HelmetKotk_AyeZeeChampion_DT.dds`, `dds/HelmetKotk_MotoCrossElite_DT.dds`, `dds/HelmetKotk_MotoCrossElite_Print.dds`, `dds/HelmetKotk_ParaMilitaryPetitBoo_DT.dds`, `dds/HoodieKotk_GhostRotkLeague_DT.dds`, `dds/HoodieKotk_PinkGhostRotkLeague_DT.dds`, `dds/HoodieKotk_RedRotkLeague_DT.dds`, `dds/Icon_Vehicle_PickupTruck_Kotk_TwoTapMe.dds`, `dds/Icon_Weapons_Kotk_AyeZeeChampion2AR15.dds`, `dds/Icon_Weapons_Kotk_PetitBooAR15.dds`, `dds/Icon_Wear_SurvivorMale_Armor_BMX_Kotk_Carbon.dds`, `dds/Icon_Wear_SurvivorMale_Armor_Kevlar_Basic_Velcro_Kotk_Cosm.dds`, `dds/Icon_Wear_SurvivorMale_Back_Backpack_Kotk_Coffin.dds`, `dds/Icon_Wear_SurvivorMale_Back_Backpack_Kotk_GhostRotkLeague.dds`, `dds/Icon_Wear_SurvivorMale_Back_Backpack_Kotk_PinkGhostRotkLeague.dds`, `dds/Icon_Wear_SurvivorMale_Back_Backpack_Kotk_RedRotkLeague.dds`, `dds/Icon_Wear_SurvivorMale_Back_Backpack_Kotk_Shadowfang.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Hoodie_Kotk_GhostRotkLeague.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Hoodie_Kotk_PinkGhostRotkLeague.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Hoodie_Kotk_RedRotkLeague.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Shirt_Kotk_BoysDontCry.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Shirt_Kotk_Elite20k.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Shirt_Kotk_Mms.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Shirt_Kotk_MoreKillMoreWin.dds` and 53 more
- `locale_rotk` -> `locale_rotk.payload` (5,052,714 bytes, sha256 `82d88dd0970ec8bdec0e3ec071c8bf0b28b5f7a925fc6cdc02549d70ecc5469a`)
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
