# Assets 1.13.45 — Yellow pulsing knocked teammate health

Rebuilt from the published 1.13.44 client. The remaining teammate HP fill pulses yellow (#FFD400) while knocked. Revive restores its original color and opacity; final death and spectator state override a stale knock flag. Names, team colors, icons and health width keep their existing behavior.

Requires the server change in [returnoftheking#980](https://github.com/ROTK-Team/returnoftheking/pull/980), which publishes the native downed life-state bit for Trio teammates, including distant members. Coordinate this draft with the next server tag containing that change.

## Payloads

- `assets_x64_0.payload`: 1,338,361,713 bytes; SHA-256 `8cc15df92384722883efff9f9ea0d1f04c6fb887a9d7037fc424f81c68ad67e3`.
- `rank_menu_ui.payload`: 89,524,544 bytes; SHA-256 `a9aa1570c2fe34bc6aa3cb489b5b2f926d7acfb1ac808022494501adaec50c67`.

`assets_x64_0.payload` contains the rebuilt `assets_x64_0.pack2`. `rank_menu_ui.payload` contains the rebuilt `ui_x64_0.pack2` and the byte-identical `ui_x64_2.pack2` required by that existing owner. All other feed entries and installed files are preserved, including the armor, spectator reticle, cargo and FPS changes in 1.13.44.

## Validation

- All 16 distributed pack files in the input client matched the 1.13.44 payload manifest.
- Every present `UIRoot.gfx` and `HudGroupVoiceWindow.gfx` copy was rebuilt. All three distinct variants were compiled, re-exported and exercised by the lifecycle proof; all unrelated exported classes stayed identical.
- 9,606 unrelated assets in the rebuilt packs retained their exact bytes and metadata. Standard ZIP archive contents were decompressed and checked against staging by the feed builder.
- The user approved the yellow pulse in the native local harness. The refreshed 1.13.44 candidate passed the compiled proof; that baseline was not separately launched for a combined native acceptance pass.
- The exact Rust knock/revive/final-death combat journey and packet-byte test passed. The UI lifecycle proof is part of the server PR's Duos CI shard.
- The 40 current clean/patched launcher roots were verified against their recorded asset baselines before deriving the new roots. The private policy is staged locally with a guard against a changed policy; it is not applied or published here.

## Promotion at the next server tag

Keep this release and distribution PR in draft until promotion. Recheck that the published asset feed is still 1.13.44 and the integrity policy still matches the preparation baseline. If either changed, refresh this candidate to preserve the intervening changes. Complete the native acceptance pass on the release candidate and confirm the server tag includes returnoftheking#980.

The uploaded draft payloads must be downloaded and SHA-256 checked before publication. Publish the release before merging this distribution PR, then apply the matching private integrity policy through the normal release process. Recheck the public feed, latest release overlay and integrity roots. A server tag alone does not distribute these UI assets.
