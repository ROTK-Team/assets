# Assets 1.13.53 — Z1BR night, aim-blocked weapon lowering and console stall fix

Three changes merged on main since 1.13.52, each built by its own tool or verified entry, none overlapping another.

Restores the Z1BR night in `Lighting_Z2_PS3.txt` of `assets_x64_0` (#69): the Dusk, Twilight, Night, FalseDawn and Dawn blocks come byte for byte from the Z1BR copy in `data_x64_0`; Day, Globals and SunAngleTimes are unchanged, so full daylight looks exactly as before. Hours that were forced to daylight now follow the Z1BR curve (Combat Training at 17:00 can show a light evening tint, as on Steam).

Lowers the third-person weapon when aim is blocked by a wall or an obstacle (#64), as in Pre-Season 3: `ThirdPersonMalePhysicsX64.mrn` of `assets_x64_10` gains an additive AimBlock layer driven by the existing `State_AimBlocked` input. Rifle, pistol, pump shotgun and hunting rifle, standing and crouched.

Stops the console from stalling the game when it opens (#74): `UIConsoleManager` in both `UIRoot.gfx` copies (`assets_x64_0` and `ui_x64_0`) renders only the last 200 log lines and ignores a toggle within 500 ms of the previous one. N still opens the console. The log array is unchanged, so file logging keeps everything.

Both `UIRoot.gfx` entries were rebuilt from the 1.13.52 movies, so they still carry the Social panel fixes (#73) and the native translated UI (#61) of 1.13.52.

**Not validated in game.** None of the three changes has been exercised in a running client yet: #74 (console) was only checked on the decompiled classes and by its CI test, #69 (night) and #64 (aim block) only offline against the installed packs and the client executable. Test the draft before publishing: open the console (N) in a match and in a vehicle, set the Combat Training hour to 03 and 17, and face a wall with a rifle in third person.

Pairs with server v1.5.24 of ROTK-Team/returnoftheking; publish both together.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,736,402 bytes, sha256 `d7de2452182f891f5cd06f3956cd4710b3c5c2d7f72d77d43537a7eb16f9af0c`)
  - `Resources/Assets/assets_x64_0.pack2`: 2 changed
    - changed: `gfx/uiro/UIRoot.gfx`, `txt/ligh/Lighting_Z2_PS3.txt`
- `assets_x64_10` -> `assets_x64_10.payload` (85,702,442 bytes, sha256 `f9c5cf99fc7d7a77eed7a301c73a322c61580fec6d8a15b1b6d5ae2d3aec116c`)
  - `Resources/Assets/assets_x64_10.pack2`: 1 changed
    - changed: `mrn/ThirdPersonMalePhysicsX64.mrn`
- `rank_menu_ui` -> `rank_menu_ui.payload` (88,238,617 bytes, sha256 `8c5900f1220615f9b4752efef112a7b225a9c62333afcffad49988ae71dde52e`)
  - `Resources/Assets/ui_x64_0.pack2`: 1 changed
    - changed: `gfx/UIRoot.gfx`
  - `Resources/Assets/ui_x64_2.pack2`: no entry changed (rebuilt with its payload)
