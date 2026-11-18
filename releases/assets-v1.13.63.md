# Assets 1.13.63 — Batch 12 cosmetics

Adds cosmetic wave 43: 115 skins, the Christmas Offroader vehicle skin and two emotes from the designer's batch12 delivery.

- **Helmets:** Dark Blue, Green, Pink and Red Camo, AyeZee Championship Helmet 2, Kylio, Red / Ghost / Pink Ghost ROTK League, sLoth and Grail Camo Tactical Helmets; Dino Helmet, Krampus Helmet, Holographic and Patriotic MotoCross Helmets, and the animated Magma Skull Mask.
- **T-shirts:** Real Madrid ZEY, JobLife, JobLife EMEA, Ghost and Pink Ghost ROTK League, ABTS Spray, ABTS Stucks, Craked ROTK, Skin Creator, X, and the animated Fana Akatsuki T-Shirt.
- **Clothing:** Nexus, Scream, Ensou1 and SmokeyZ sets, Scoot and Skin Creator Pants, Frowzer White Baggy Pants, Lebergus Boonie Hat, SapeKing Hat; on new bases: AngA Cargo Pants and Sleeveless Hoodie, Santa Claus Cargo Pants and Parka, Green Slacks, Pink Police Shirt and Slacks, Pink Suit Jacket, Christmas Wrestling Shoes, Croco Shoes, Pink Bunny Slippers and Trainer Shoes.
- **Gloves and backpacks:** Croco, Fire, Unicorn, Pink Fade, Press M1 Faster, Skin Creator, Viking Bone and Black Viking Bone Gloves; AngA, Pokeball, Grail Camo, Blue Crown Military, Flamingo Man Sport, Heaven Unicorn, Sakura Assassin and the animated Twincy Backpack.
- **Armor:** AyeZee Championship, ROTK Blood, Bone and Patriotic Makeshift Armor; AyeZee Championship and Grail Camo Tactical Body Armor, Pink Unicorn and Gorilla Body Armor (laminated); Red ROTK PL Satchel, Prestige Monkey King Mask.
- **3D accessories:** Connected, Jacob & Co. Roulette, Patek Nautilus, Rolex Pepsi, Rolex Sprite, Royal Oak and Spider-Man Watches; Ivory Mask, Smoking Pipe, Red Rose, America Neck Warmer.
- **Weapons:** Alchemy, Dragonfire, Holographic and the animated Dark Matter, Toxic Rift and Sakura AK-47s; Havachi, Panda, Sakura, Nexus Fade, Iconographic and the animated France, Ippo, Shooting Stars, Soulfire, Hearts and Hardline Gold AR-15s; Frostbite M24; Grail Camo, Red / Ghost / Pink Ghost ROTK League, Frostbite (ice animated on the barrel only) and Sakura Riot Shotguns. The 24 new firearms join the Custom Crosshair weapon families.
- **Vehicle:** Christmas Offroader.
- **Crate:** ROTK Season 2 Crate, with its My Crates tab and hero images.
- **Emotes:** Strangled and One Hand (animations by SkullH1; icons adapted from SkullH1's: silhouettes redrawn in the ROTK emote style, music notes removed; CC BY 4.0), in place of the Cold and Listen animations that no item plays. Each clip is completed to the length of the animation it replaces with a short return to its end pose, so the character no longer spins at the end.
- **Repainted retail items:** Starry Night, Infernal, Soulfire and Patriotic Riot Shotguns, Patriotic AK-47 and Patriotic Military Backpack.
- **Updated:** new texture and icon for the Real Madrid ROTK T-Shirt, new icon for the Carbon Makeshift Armor; both now show the neutral source banner, without text. The ROTK Warpaint Gorilla Helmet is rebuilt on its proper model: no sunglasses, and the whole helmet is painted. The YouTubeable T-Shirt and Pro Military Backpack are renamed Youtubable.

Rarities come from the rarity panel. Built on assets main (live 1.13.62 plus the Fives client). Not yet validated in game.

`data_x64_0`, `assets_x64_10` (emotes), `assets_x64_0`, `assets_x64_1` and `ui_x64_3` (crosshair families) and the locales ship together: a client with the new `data_x64_0` but the old `assets_x64_10` plays Cold and Listen for the two emotes. The server must not go live before this release: the ROTK Warpaint Gorilla Helmet, already owned, now points at models that only this release ships.

Pairs with the server release that applies migrations 0237/0238 of ROTK-Team/returnoftheking. Publish this release and its feed first, then tag the server.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,328,394,401 bytes, sha256 `dbe53967dc0f70d20d50caa633189d0337fc4b38e19e9ed3b0e22fe96181cc3f`)
  - `Resources/Assets/assets_x64_0.pack2`: 5 changed
    - changed: `gfx/huda/HudActionTimerWindow.gfx`, `gfx/hudr/HudReticleWindow.gfx`, `gfx/huds/HudSystemMessagesWindow.gfx`, `gfx/uiro/UIRoot.gfx`, `xml/acto/ActorSockets.xml`
- `assets_x64_1` -> `assets_x64_1.payload` (128,078,182 bytes, sha256 `0afe5ade67f3c1c0eaef3d099dd023ab91bd02dc53aa21f72af8b958eb33c6ad`)
  - `Resources/Assets/assets_x64_1.pack2`: 4 changed
    - changed: `gfx/huda/HudActionTimerWindow.gfx`, `gfx/hudr/HudReticleWindow.gfx`, `gfx/huds/HudSystemMessagesWindow.gfx`, `xml/acto/ActorSockets.xml`
- `assets_x64_10` -> `assets_x64_10.payload` (85,555,534 bytes, sha256 `25f6e1294647b00af5fdf5c71aa41519ea307f37f87a77d139e6195cf521bc79`)
  - `Resources/Assets/assets_x64_10.pack2`: 1 changed
    - changed: `mrn/ThirdPersonMalePhysicsX64.mrn`
- `data_x64_0` -> `data_x64_0.payload` (364,613,706 bytes, sha256 `cc25e5a6645d58f19dbae631578bde9f16f70d5a7281b7416c2ea6204ef9ef20`)
  - `Resources/Assets/data_x64_0.pack2`: 24 changed, 448 added
    - changed: `dds/Icon_Wear_SurvivorMale_Armor_BMX_Kotk_Carbon.dds`, `dds/Icon_Wear_SurvivorMale_Chest_Shirt_Kotk_RealMadridRotk.dds`, `dds/TshirtKotk_RealMadridRotk_DT.dds`, `txt/AcctItemConversionGroupMappings.txt`, `txt/AcctItemConversionInputItems.txt`, `txt/AcctItemConversions.txt`, `txt/ClientColorDefinitions.txt`, `txt/ClientItemDefinitions.txt`, `txt/CodeStringMappings.txt`, `txt/EmoteAnimations.txt`, `txt/FirstPersonAttachments.txt`, `txt/GroupMemberColorMappings.txt`, `txt/ImageSetMappings.txt`, `txt/ImageSets.txt`, `txt/Images.txt`, `txt/ItemClassMappings.txt`, `txt/ItemDatasheetPropertyMap.txt`, `txt/ItemIdUseOptionGroupId.txt`, `txt/ItemSourceLookup.txt`, `txt/Models.txt`, `txt/PropertySetMapping.txt`, `txt/VehicleSkinMods.txt`, `xml/ActorModelMaterialDefinitions.xml`, `xml/ActorSockets.xml`
    - added: `adr/SurvivorFemale_Back_Backpack_ProMilitary_KotkPrint.adr`, `adr/SurvivorFemale_Face_Kotk_AmericaNeckWarmer.adr`, `adr/SurvivorFemale_Face_Mask_Kotk_IvoryMask.adr`, `adr/SurvivorFemale_Face_Mask_Kotk_Pipe.adr`, `adr/SurvivorFemale_Face_Mask_Kotk_Rose.adr`, `adr/SurvivorFemale_Feet_Kotk_PinkBunny.adr`, `adr/SurvivorFemale_Feet_Kotk_Trainer.adr`, `adr/SurvivorFemale_Hands_Kotk_ConnectedWatch.adr`, `adr/SurvivorFemale_Hands_Kotk_JacobCoRoulette.adr`, `adr/SurvivorFemale_Hands_Kotk_PatekNautilus.adr`, `adr/SurvivorFemale_Hands_Kotk_RolexPepsi.adr`, `adr/SurvivorFemale_Hands_Kotk_RolexSprite.adr`, `adr/SurvivorFemale_Hands_Kotk_RoyalOak.adr`, `adr/SurvivorFemale_Hands_Kotk_SpiderManWatch.adr`, `adr/SurvivorFemale_Head_Hat_Kotk_SapeKing.adr`, `adr/SurvivorFemale_Head_Helmet_Kotk_Dino.adr`, `adr/SurvivorFemale_Head_Helmet_Kotk_Krampus.adr`, `adr/SurvivorFemale_Head_Mask_Kotk_GorillaWarpaint.adr`, `adr/SurvivorMale_Back_Backpack_ProMilitary_KotkPrint.adr`, `adr/SurvivorMale_Face_Kotk_AmericaNeckWarmer.adr`, `adr/SurvivorMale_Face_Mask_Kotk_IvoryMask.adr`, `adr/SurvivorMale_Face_Mask_Kotk_Pipe.adr`, `adr/SurvivorMale_Face_Mask_Kotk_Rose.adr`, `adr/SurvivorMale_Feet_Kotk_PinkBunny.adr`, `adr/SurvivorMale_Feet_Kotk_Trainer.adr`, `adr/SurvivorMale_Hands_Kotk_ConnectedWatch.adr`, `adr/SurvivorMale_Hands_Kotk_JacobCoRoulette.adr`, `adr/SurvivorMale_Hands_Kotk_PatekNautilus.adr`, `adr/SurvivorMale_Hands_Kotk_RolexPepsi.adr`, `adr/SurvivorMale_Hands_Kotk_RolexSprite.adr`, `adr/SurvivorMale_Hands_Kotk_RoyalOak.adr`, `adr/SurvivorMale_Hands_Kotk_SpiderManWatch.adr`, `adr/SurvivorMale_Head_Hat_Kotk_SapeKing.adr`, `adr/SurvivorMale_Head_Helmet_Kotk_Dino.adr`, `adr/SurvivorMale_Head_Helmet_Kotk_Krampus.adr`, `adr/SurvivorMale_Head_Mask_Kotk_GorillaWarpaint.adr`, `adr/Weapons_AK47_KotkDarkMatter.adr`, `adr/Weapons_AK47_KotkDarkMatter_3P.adr`, `adr/Weapons_AK47_KotkToxicRift.adr`, `adr/Weapons_AK47_KotkToxicRift_3P.adr` and 408 more
- `locale_rotk` -> `locale_rotk.payload` (5,098,885 bytes, sha256 `4c4a8a41da3c2f30009768e67618ebc911fc5b16c9312313f110f592aa88ea00`)
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
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,257,244 bytes, sha256 `42bc3dc538344700739cbebb3f03a26236c9477994e0b01ff757afba263f354b`)
  - `Resources/Assets/ui_x64_0.pack2`: 3 changed
    - changed: `gfx/HudSystemMessagesWindow.gfx`, `gfx/MapWindow.gfx`, `gfx/UIRoot.gfx`
  - `Resources/Assets/ui_x64_2.pack2`: no entry changed (rebuilt with its payload)
- `cz_death_ui` -> `cz_death_ui.payload` (42,008,710 bytes, sha256 `27dc92234c87f03fdfbec9ef5a085cb1b9bac9d5cd343b1c5b0d27da3669a6ca`)
  - `Resources/Assets/ui_x64_3.pack2`: 2 changed
    - changed: `gfx/HudActionTimerWindow.gfx`, `gfx/HudReticleWindow.gfx`
