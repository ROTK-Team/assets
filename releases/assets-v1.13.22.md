# Assets 1.13.22 — ROTK helicopter emblem

The helicopter at the center of the lobby now displays the red ROTK emblem on both sides. The two other map helicopters sharing this material receive the same change. The result was reviewed and accepted in the local game harness before publication.

One texture, `Vehicle_Common_Helicopter01_C.dds`, is replaced in both `assets_x64_0.pack2` and `assets_x64_3.pack2`. The 4096×4096 BC1 texture retains all 13 mip levels. This release starts from assets 1.13.21, preserving the ammunition colors and all 13,711 unrelated entries in these two packs.

The existing launcher downloads the two updated packs on the next Play. No launcher update or game-server restart is required.

Validation: both texture copies match the approved DDS SHA-256 `8df334bf2974b9b33ff4c046aaff5c410ea87dfe72581c2a0f4dc16908e0fc02`; original pack baselines checked against published manifests; unrelated stored entries and metadata compared byte-for-byte. Standard ZIP archives are checked by decompression, and the released launcher 2.0.21 installer is exercised in an isolated directory, including a second sync with no download. Published payloads and manifest/attestation roots are verified during release.

Rollback requires a higher assets version restoring these two previous pack payloads and matching attestation roots. Prior versions remain available; updating only the raw feed does not undo the latest-release overlay.
