# Assets 1.13.44 — Armor, spectator reticle, vehicle cargo and optional FPS estimate

Combined candidate on the imported live 1.13.42 baseline and Berga's armor UI change (#49).

- Preserve worn helmet/vest cracks and the armor HUD indicators. The server candidate must include returnoftheking#966.
- Restore the native reticle while spectating; restore the saved custom crosshair when playing resumes (#48).
- Add the default-OFF FPS estimate and persistent toggle in both Gameplay menus (#50).
- Restore native wheel/scrollbar access to the complete vehicle cargo provider and remove empty rows after withdrawals. This completes the UI side of returnoftheking#944 while preserving the existing 4x4 layout.

The FPS option counts GFx timer callbacks, not rendered presentations. It can under-report high frame rates or throttled UI updates. The native settings-reset button does not reset this custom preference. Keep this candidate in draft until the combined native acceptance pass is complete.

Required native checks: intact/worn armor in equipped inventory, ground, bags and cargo; cargo with more than 16 rows and withdrawals while several occupants inspect it; spectator target changes and reboot; FPS ON/OFF in both menus, resolution changes and repeated matches. Qualify the server voice fix (#943) together with launcher#157 (2.0.36).

Publish rebuilt payloads before merging the distribution feed. Preserve every unchanged feed entry and publish the matching attestation policy before enforcing the new client combination. This source change does not publish a release or modify an installed game.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,658,761 bytes, sha256 `3814a9cb65625e9c9cfddfe9df32eea8312709417b9c4d11b46825c663e9241c`)
  - `Resources/Assets/assets_x64_0.pack2`: 5 changed
    - changed: `dds/img1/img12569630311499027349.dds`, `dds/img3/img3862987726949368029.dds`, `gfx/hudr/HudReticleWindow.gfx`, `gfx/inve/InventoryWindow.gfx`, `gfx/uiro/UIRoot.gfx`
- `assets_x64_1` -> `assets_x64_1.payload` (128,031,755 bytes, sha256 `663eaa7ec399ea195ce6cbec8d9e21619088278257ab1a0b5a4d23af7cad4915`)
  - `Resources/Assets/assets_x64_1.pack2`: 1 changed
    - changed: `gfx/hudr/HudReticleWindow.gfx`
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,172,009 bytes, sha256 `083e2fd2ca17e1e2f1e18a29e204b7f2e7503647d288756f7e522dfb6ecc3f5a`)
  - `Resources/Assets/ui_x64_0.pack2`: 1 changed
    - changed: `gfx/UIRoot.gfx`
  - `Resources/Assets/ui_x64_2.pack2`: 2 changed
    - changed: `gfx/SettingsGameplayInGameWindow.gfx`, `gfx/SettingsGameplayPreGameWindow.gfx`
- `cz_death_ui` -> `cz_death_ui.payload` (42,002,444 bytes, sha256 `ed82b74229a8931fc4f6955dc7a2390fda9420cfc197870e3efd2808890130f4`)
  - `Resources/Assets/ui_x64_3.pack2`: 1 changed
    - changed: `gfx/HudReticleWindow.gfx`
