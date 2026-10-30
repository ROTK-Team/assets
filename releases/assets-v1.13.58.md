# Assets 1.13.58 — No light flash on metal bullet impacts

One change on top of the live assets 1.13.57 (Halloween 2026 Z2 map).

Bullets hitting metal (hangar sheets, fences, barbed wire, grates, vehicles) no longer flash: under the Halloween night exposure the light of the stock metal impact effects bloomed into a large flash. `ActorFxDefinitions.xml` of `data_x64_0` points the three metal bullet impacts (FX 1181 light, 1806 shotgun, 1713 heavy) at the stock `Impact_Fist_Metal.fxd`: embers and mist without a light. Sounds and decals are unchanged.

Validated in game in the isolated two-client harness. Temporary: the Halloween revert puts the original effects back. Assets only.

## Changed assets

- `data_x64_0` -> `data_x64_0.payload` (419,731,064 bytes, sha256 `319795df1f3a990f0f46ad973637561ccbcf307e834f04b68c834a4debb4956b`)
  - `Resources/Assets/data_x64_0.pack2`: 1 changed
    - changed: `xml/ActorFxDefinitions.xml`
