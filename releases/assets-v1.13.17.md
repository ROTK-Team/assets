Lobby ramps and signs now display ROTK branding. The leaderboard banner replaces the cat graphic with the ROTK logo and the text “H1Z1 NEVER DIE”, “Made by community, for community”, “Made by / LeBerga Mazsuka & Teuf / ROTK.app”.

Rebuilt from the published 1.13.16 installation. Four textures are replaced in all seven copies across `assets_x64_0`, `assets_x64_2`, `assets_x64_6`, `assets_x64_8`, and `assets_x64_9`:

- `Primitives_Ramps_TC.dds`
- `Common_Props_BattleRoyaleSigns_OC.dds`
- `Common_Props_BattleRoyaleSigns_02_OC.dds`
- `Common_Props_LeaderBoard_Sign_C.dds`

Validation: all 68 baseline packs matched the published manifests; all 26,246 unrelated entries in the five rebuilt packs retain identical metadata and stored bytes. Skins and all unrelated feed entries remain unchanged. The released launcher 2.0.21 installs the five archives into an isolated client with matching file hashes; a second Play downloads nothing. Native lobby rendering was previously checked with the same DDS payloads using the TypeScript harness; no native Rust gameplay test is claimed.

The five `.payload` archives are ZIP containers and require approximately 3.2 GB of downloads. The existing launcher consumes the updated feed. Attestation roots must be regenerated for the existing supported launcher versions on production and the active Rust test environment without changing enforcement or patch mode.
