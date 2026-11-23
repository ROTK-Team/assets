# Assets 1.13.65 — Nexus Fade AR-15: flowing glow and NEXUS wordmark

The Nexus Fade AR-15 (wave 43, shipped in 1.13.63 with a still texture) gets a subtle flowing glow and the NEXUS wordmark. Cyan light flows over its colour fade and the barrel, and violet light trails run from the stock to the muzzle. The receiver, the grip and the front sight stay matte. Its icon shows the glow.

- **Effect:** new Multiscroll effect 1389 `Skin_Kotk_NexusFadeAR15`, on stock textures only (`Material_Smoke_01`, `Material_Streaks_01`, `FlowMap_01`, `White_Mask`), brightness 4.8 / 6 (toned down twice in game tests).
- **Model:** the skin gets its own copy of the stock AR-15 model (models 30198 / 30199, first and third person). Its normal maps are the stock ones with the blue channel set to the colour fade and the barrel, so the glow stays there.
- **Texture:** the NEXUS neon wordmark, 12 cm wide, high on the receiver of both sides, read upright from each side, in first person and on every third-person LOD.
- **Icon:** the designer's icon with one still frame of the glow.
- **Normal maps:** the "PROPERTY OF U.S. GOVT" engraving of the left magwell flat is flattened.
- `data_x64_0` (tables, effect, model, texture, normal maps, icon) and `assets_x64_0` / `assets_x64_1` (the new model's sockets in `ActorSockets.xml`) change; they ship together.

The server must not go live before this release: the Nexus Fade AR-15, already owned, now points at a model that only this release ships. Between the two releases the Nexus Fade AR-15 already shows the NEXUS wordmark and its new icon, on the stock model and without the glow, and its Customize preview shows the glow on the stock model's metal parts instead of the fade: tag the server right after this release.

Pairs with the server release 1.5.36, which sends effect 1389 and model 30199 for the Nexus Fade AR-15 (ROTK-Team/returnoftheking, no migration). Publish this release and its feed first, then tag the server. Validated in game on 2026-11-23 (two-client harness).

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,328,394,821 bytes, sha256 `07ecda0af04b0acc7508a815228eecaf892654bde3e12ad0a1fbba0dac02f500`)
  - `Resources/Assets/assets_x64_0.pack2`: 1 changed
    - changed: `xml/acto/ActorSockets.xml`
- `assets_x64_1` -> `assets_x64_1.payload` (128,078,276 bytes, sha256 `1093636b9680549167dcb3c517dc2b1c7edca45931c1c5f8f0e680c4fd09c8bb`)
  - `Resources/Assets/assets_x64_1.pack2`: 1 changed
    - changed: `xml/acto/ActorSockets.xml`
- `data_x64_0` -> `data_x64_0.payload` (368,999,994 bytes, sha256 `34daa51d02dd6127489c293d24a8d54a46ef0f2082d2aef2c3d98691465b287d`)
  - `Resources/Assets/data_x64_0.pack2`: 7 changed, 12 added
    - changed: `dds/Icon_Weapons_Kotk_NexusFadeAR15.dds`, `dds/WeaponKotk_NexusFadeAR15_DT.dds`, `txt/AcctItemConversions.txt`, `txt/FirstPersonAttachments.txt`, `txt/Models.txt`, `xml/ActorModelMaterialDefinitions.xml`, `xml/ActorSockets.xml`
    - added: `adr/Weapons_AR15_KotkNexusFade.adr`, `adr/Weapons_AR15_KotkNexusFade_3P.adr`, `dds/WeaponKotk_NexusFadeAR15_N.dds`, `dds/WeaponKotk_NexusFadeAR15_N3P.dds`, `dma/Weapons_M16A4_KotkNexusFade_3P_Lod0.dma`, `dma/Weapons_M16A4_KotkNexusFade_3P_Lod1.dma`, `dma/Weapons_M16A4_KotkNexusFade_3P_Lod2.dma`, `dma/Weapons_M16A4_KotkNexusFade_Lod0.dma`, `dme/Weapons_M16A4_KotkNexusFade_3P_LOD0.dme`, `dme/Weapons_M16A4_KotkNexusFade_3P_LOD1.dme`, `dme/Weapons_M16A4_KotkNexusFade_3P_LOD2.dme`, `dme/Weapons_M16A4_KotkNexusFade_LOD0.dme`
