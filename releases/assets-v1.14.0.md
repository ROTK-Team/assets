# Assets 1.14.0 — Custom crosshair, weapon slots, main menu and RIDES preview

Client packs for the server release that contains these returnoftheking pull
requests: [#785](https://github.com/h1z1rotk/returnoftheking/pull/785) custom
crosshair, [#739](https://github.com/h1z1rotk/returnoftheking/pull/739) weapon
slots, [#777](https://github.com/h1z1rotk/returnoftheking/pull/777) main menu
client patches, [#768](https://github.com/h1z1rotk/returnoftheking/pull/768)
emotes and [#778](https://github.com/h1z1rotk/returnoftheking/pull/778) RIDES
preview. Publish these assets after that server release: the weapon slot page
needs the `/slot set` server command, and the Customize emote and RIDES panels
need the matching menu server.

## What changes for the player

- Settings > Gameplay starts with a Weapon Slots section (Slot 1/2/3 with the
  native stepper, conflicts shown in red and never saved) and the four settings
  pages are centred, in the main menu and in match.
- Settings > Gameplay > RETICLE gets a Custom Crosshair row with an EDIT button
  and an OFF/ON switch. OFF leaves the whole game reticle system untouched. ON
  shows the custom crosshairs in match, one per weapon or a shared one; the game
  reticles stay listed, greyed and locked while ON. Custom crosshairs are fixed.
- Main menu: no MISSIONS and no GET CROWNS button on the home page (the Crowns
  hover bubble stays), smoother logo intro, hover description fix, LINK ACCOUNT
  hidden, no arrow-key navigation in Customize, replayable emote previews.

## Changed entries

| Archive | Pack | Entries |
|---|---|---|
| `assets_x64_0.payload` | `assets_x64_0.pack2` | `HudReticleWindow.gfx`, `UIRoot.gfx`, `BackgroundWindow.gfx`, `CustomizationWindow.gfx` |
| `assets_x64_1.payload` | `assets_x64_1.pack2` | `HudReticleWindow.gfx` |
| `rank_menu_ui.payload` | `ui_x64_0.pack2` | `UIRoot.gfx` |
| `rank_menu_ui.payload` | `ui_x64_2.pack2` | the 8 Settings pages (Gameplay, Graphics, Audio, Keybindings; PreGame and InGame), `CustomizationWindow.gfx` |
| `cz_death_ui.payload` | `ui_x64_3.pack2` | `HudReticleWindow.gfx` |
| `data_x64_0.payload` | `data_x64_0.pack2` | `MenuItem.txt` (LINK ACCOUNT hidden) |

Every pack is rebuilt on the published assets 1.13.25 packs; all other entries
are byte-identical (`pack2-workbench diff`: 8,926 / 3,178 / 678 / 966 / 404 /
634 unchanged entries). `HudReticleWindow.gfx` is patched in its three copies.

## How the packs were built

From the pull requests above, applied on the published packs, in this order:

1. `build-weapon-slots-client1315.py` (#739) on the original `ui_x64_2.pack2`;
2. `build-crosshair-client1315.py` (#785) on that output;
3. `build-crosshair-hud1315.py` (#785) for the three `HudReticleWindow.gfx`;
4. the `build-menu-*1315.mjs` builders (#777), order in
   `docs/MENU_CLIENT_UI_1315.md`.

## Validation

Compilation and decompilation of every patched widget, preservation of the
other entries, and live checks on a local server with the matching server
branches: weapon slot ordering in match, settings pages centred, custom
crosshair per weapon with the switch OFF and ON, menu patches, emotes and RIDES
preview. Not checked: resolutions other than 2560x1440.

## Manifests

`feed.json` and `asset-payloads.v1.json` were produced by
`devts/tools/build-asset-feed-release.mjs --version 1.14.0` from the published
manifests; only the five owners above change, `packVersion` becomes 1.14.0.
The matching server integrity policy must be published with them.
