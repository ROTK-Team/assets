# Assets 1.13.30 - AK animation resource isolation

Give the AK animation bundle its own resource identifiers while preserving the current models, skins and animation motion. This prevents identity overlap with the stock weapon animation bundle.

Native local checks preserved first-person, third-person and reload visuals and completed weapon switching and six vehicle entry/exit cycles without a crash. The original reported crash was not reproduced; this is a preventive resource-isolation change, not a confirmed crash-resolution claim.

## Changed assets

- `assets_x64_0` -> `assets_x64_0.payload` (1,327,617,509 bytes, sha256 `3545e32d1f93c20b7ec30c65aa64f1a64312c6f2726f66cab64d1ea0f4d334b5`)
  - `Resources/Assets/assets_x64_0.pack2`: 1 changed
    - changed: `mrn/ak47/AK47ClassicROTKX64.mrn`
