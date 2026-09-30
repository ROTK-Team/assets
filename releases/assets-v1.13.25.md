# Assets 1.13.25 — Gas siren client support

Restore the native siren sound requested by gas-warning announcements. The
ROTK messages widget previously ignored the supplied sound ID and always
selected the generic broadcast sound. The corrected widget forwards unsigned
sound IDs while preserving the existing default and explicit mute behavior.

This client update prepares the siren for the next server release containing
[returnoftheking PR #755](https://github.com/h1z1rotk/returnoftheking/pull/755).
That server change triggers it two seconds before every Solo and Duos gas
shrink. Publishing these assets alone does not activate the server schedule.

Only `HudSystemMessagesWindow.gfx` in `assets_x64_0.pack2` changes. The pack is
rebuilt on public assets 1.13.24, preserving the ROTK victory logo, message
placement below the compass and all other installed content. All 8,929 other
pack assets, 69 other classes and 63 other SWF tags are byte-identical.

Validation includes compilation/decompilation of the widget, preservation of
unrelated content, an audible native Solo harness test accepted by the user,
and installation through the released launcher 2.0.23 code. The launcher
installs the update once and downloads nothing on a second launch. Duo audio
was not separately tested by ear; the server schedule uses the shared
Solo/Duos path with automated phase coverage.

The normal launcher downloads the update before launching the game. This
release contains no new sound file, launcher executable or server deployment.
