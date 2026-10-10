# Hosted spectator HUD and persistent game navigation

Bring the tested spectator HUD and Hosted Games browser to the current assets baseline.
Keep recent spectator names, scrolling, gameplay preferences, and menu fixes.

Validated with FFDec compilation and decompilation, repository tests, asset checks,
and CI on the PR head and merged main commit.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,634,353 bytes, sha256 `698da99c056cf3f5d97afb3e16f04b01e885999f95c19a98a043bf50a87be384`)
  - `Resources/Assets/assets_x64_0.pack2`: 4 changed
    - changed: `gfx/huds/HudSpectatorWindow.gfx`, `gfx/hudv/HudVSPanelWindow.gfx`, `gfx/uiro/UIRoot.gfx`, `txt/hudi/HudIndicators.txt`
- `data_x64_0` -> `data_x64_0.payload` (60,928,046 bytes, sha256 `1599fa96939ad3547e509549036bd96b4985ad338a3fb0dac7b1e87eed7d026f`)
  - `Resources/Assets/data_x64_0.pack2`: 1 changed
    - changed: `txt/FontDefinitions.txt`
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,169,454 bytes, sha256 `91f67a0ccb54c86e207cf75d551299ad593f9795b14d0a99ef3a86b7370ee21f`)
  - `Resources/Assets/ui_x64_0.pack2`: 2 changed
    - changed: `gfx/TeamSpectateWindow.gfx`, `gfx/UIRoot.gfx`
  - `Resources/Assets/ui_x64_2.pack2`: 3 changed
    - changed: `gfx/HudSpectatorWindow.gfx`, `gfx/SettingsGameplayInGameWindow.gfx`, `gfx/SettingsGameplayPreGameWindow.gfx`
- `cz_death_ui` -> `cz_death_ui.payload` (42,002,305 bytes, sha256 `f7939833a7a66235b916eb56d5a0a891c1efdbcd66e0884f6000de52e7ce9fad`)
  - `Resources/Assets/ui_x64_3.pack2`: 1 changed
    - changed: `gfx/HudVSPanelWindow.gfx`
