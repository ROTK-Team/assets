# Assets 1.13.24 — ROTK Solo victory logo

Winning a Solo match now displays the official ROTK wordmark with its red
crowned skull above YOU SURVIVED. The native entrance animation, painted
backdrop, caption, sound cues and timing remain unchanged.

The owner tested this in a local native Solo match, killed the second
participant, received first place and confirmed seeing the ROTK logo.
The reproducible artwork and builders are in server PR #743:
https://github.com/h1z1rotk/returnoftheking/pull/743.

Rebuilt from the published 1.13.23 pack, preserving the latest ammunition,
helicopter and broadcast changes. Only `DeathVictoryAnimationWindow.gfx`
changes in `assets_x64_0.pack2`, and `ROTK_VictoryLogo.dds` is added. All
8,928 unrelated resources retain identical content and metadata. The two
lower-priority native victory movie variants are audited and preserved.
The widget's other 106 tags, including ActionScript, are byte-identical.

Validation includes exact matching with the approved widget and logo hashes,
full pack comparison, standard ZIP decompression, an isolated installation
with released launcher 2.0.23, and a second launch that downloads nothing.
Matching feed, installed-file manifest and integrity policies accompany the
release.

The launcher installs this update on the next Play. No launcher update or
game-server restart is required. Players already in game receive the logo
after relaunching through the launcher. A rollback requires a higher assets
version restoring the previous pack and matching integrity roots.
