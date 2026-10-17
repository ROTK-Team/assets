# Assets 1.13.48 — Mandatory tutorial menu and guide

Add the native tutorial entry and the guided objectives panel for new players. The tutorial server alone determines progress and unlocks public modes after qualification. Existing players with a recorded public Solo, Duo or Trio match remain exempt.

The menu handles all eleven supported languages, nonce validation, pending and stale state, confirmation and completion. Distributed tutorial text currently uses English. The current FPS setting and all unrelated client assets are preserved.

Rebuilt from the published 1.13.47 files using returnoftheking server-rust/tools/recruit-course/v1/build-menu.mjs and build-hud.mjs. Both compiled menu variants pass check-menu.mjs. Every other class and non-code SWF tag is unchanged. Pack comparison preserves all entries except UIRoot.gfx in two packs and HudSystemMessagesWindow.gfx in three packs.

Server routing and public menu gates must be enabled for this menu before publishing. No launcher executable update is required; restart through the launcher to download these assets.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,707,687 bytes, sha256 `bb216abd1ea333e95f76a5305ef10c2e2e9944d1bdacdd4a4bd27f6d2db7dd1a`)
  - `Resources/Assets/assets_x64_0.pack2`: 2 changed
    - changed: `gfx/huds/HudSystemMessagesWindow.gfx`, `gfx/uiro/UIRoot.gfx`
- `assets_x64_1` -> `assets_x64_1.payload` (128,071,347 bytes, sha256 `ca472a571b6fd113828c82f645615a0166d2ab4f6ecdbe1dd8073528c8b38fcf`)
  - `Resources/Assets/assets_x64_1.pack2`: 1 changed
    - changed: `gfx/huds/HudSystemMessagesWindow.gfx`
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,221,631 bytes, sha256 `3685cde4efe08a0ddbde8056506b2b5d7a5f4cdd9ff63caba398bf4d5b4934f1`)
  - `Resources/Assets/ui_x64_0.pack2`: 2 changed
    - changed: `gfx/HudSystemMessagesWindow.gfx`, `gfx/UIRoot.gfx`
  - `Resources/Assets/ui_x64_2.pack2`: no entry changed (rebuilt with its payload)
