# Assets 1.13.23 — Broadcasts below the compass

Red broadcast announcements now appear below the compass so directions and
the map grid remain readable. The message panel uses the native 105-unit
top margin at 1080p and scales with the game viewport. The existing message
appearance, duration, sounds and stacking are preserved.

This release applies the previously merged client builder from server PR
#613 to the current 1.13.22 assets. Only `HudSystemMessagesWindow.gfx` changes
in `assets_x64_0.pack2`; all 8,928 other resources remain identical, including
the latest ammunition colors and helicopter emblem. The other loaded copies
of the messages widget already have the correct vertical position.

Validation: compiled and decompiled the modified widget, checked all 69 other
classes and 63 other SWF tags unchanged, compared every other pack resource,
and verified the standard ZIP archive by full decompression. The installed
candidate was tested in a native Combat Training harness with recurring
broadcasts and accepted by the user on September 29, 2026. Release checks
exercise the published launcher installer and verify matching manifests and
integrity policies.

The launcher installs this update on the next Play. No launcher update or
game-server restart is required. A rollback requires a newer assets release
restoring the previous pack and matching integrity policy.
