# Assets 1.13.43 — Damaged armor and helmet indicators

Worn helmets and body armor now show their condition, on top of 1.13.42:

- Inventory: a helmet or vest below 51 % gets the yellow crack overlay, turning red as it nears breaking (equipped, carried, on the ground, in a loot bag or a vehicle trunk). Undamaged items and other slots stay clean.
- HUD: the body armor icon next to the health bar is back, like the helmet one, and both blink red below 50 %.

Needs the server change ROTK-Team/returnoftheking#966: older servers send worn items as full, so nothing changes until then.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,655,155 bytes, sha256 `e466c0771287ce7aa983470419c3cbf66bc9be15ea5cc945c176c3eb474c48ec`)
  - `Resources/Assets/assets_x64_0.pack2`: 3 changed
    - changed: `dds/img1/img12569630311499027349.dds`, `dds/img3/img3862987726949368029.dds`, `gfx/uiro/UIRoot.gfx`
