# Restore Z1 BR ammunition box colors

Ground ammunition uses its original Z1 BR appearance again: brown AK-47
boxes, green AR-15 boxes and the original textures for the other calibers.
The previous override pack replaced several ammunition textures and meshes
with the same green box.

This update restores 30 visual resources in `assets_x64_0.pack2`, including
the matching meshes needed to map the original textures correctly. All
8,899 unrelated pack entries retain their exact metadata and stored bytes.
Inventory icons, collisions and server gameplay remain unchanged.

Validation:

- Input pack and six source packs match the published 1.13.20 manifests.
- All 62 visual dependencies of nine ammunition actors were checked.
- Restored resources match the original client assets byte for byte.
- Original AK and AR-15 color textures were visually inspected.
- Five calibers and their weapons were displayed together in an isolated
  native client harness: green AR-15, brown AK-47 with a yellow band, orange
  shotgun, red/white Magnum and blue .45 boxes. Verified in game and accepted
  by the user; the harness pack hash matches the release candidate.

The launcher installs the corrected pack through the verified archive and
matching feed, installed-file manifest and integrity policy.
