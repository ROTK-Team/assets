# Assets 1.13.64 — Reboot crate crash fix

Pressing E on a reboot crate no longer crashes the game. Since 1.13.63 the client closed with no error as soon as the reboot panel opened, in Duos and Trios; reviving a downed teammate was not affected.

The teammate tabs of the reboot panel are now laid out with plain values. The panel looks the same: one or two teammates get the large tabs, three or four (Fives) get the compact 2x2 grid.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,328,395,232 bytes, sha256 `fde0d916a81df588628be2fb21be92037ed662f688412314458db0330ba46631`)
  - `Resources/Assets/assets_x64_0.pack2`: 1 changed
    - changed: `gfx/uiro/UIRoot.gfx`
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,257,980 bytes, sha256 `d93f008c48bf3c9b1c988d99c9580f5b527e17c9ce7a6d1916b835345e0d2944`)
  - `Resources/Assets/ui_x64_0.pack2`: 1 changed
    - changed: `gfx/UIRoot.gfx`
  - `Resources/Assets/ui_x64_2.pack2`: no entry changed (rebuilt with its payload)
