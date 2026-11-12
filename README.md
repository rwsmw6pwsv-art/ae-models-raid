# ae-models-raid

Village Raid models for Ancient Empires (studio Ancient Arcade).

Public, jsDelivr-tagged, same convention as `ae-models-city`, `ae-models-units`, and `ae-models-extra`. Additive new commits and tags only: do not rewrite or delete an existing live tag. Keep the tree under 40 MB at the tagged commit. Paths mirror the game's `public/models/...` layout.

## v1

15 GLBs: look-approved #82 trophies and ground markers (banner, pelt, AOE ring, AOE cone, aim line, LOD0/1/2 each). First published on `ae-models-extra@v7` (10 Nov 2026) and unchanged through `@v10`. Split into this repo under #15, with Michael's OK on 12 Nov 2026, 9:50 AM America/Chicago.

This repo does **not** include campaign `models/cities/village_*.glb` (those stay on `ae-models-extra@v6`) or the garrison captain (that stays on `ae-models-units@v10` at `models/units/captain/`).

Convention: +Z forward, +Y up. See `models.manifest.json` and `HASHES.md`.

## jsDelivr

```
https://cdn.jsdelivr.net/gh/rwsmw6pwsv-art/ae-models-raid@v1/models/raid/<file>
```

Raw GitHub fallback, same tag:

```
https://raw.githubusercontent.com/rwsmw6pwsv-art/ae-models-raid/refs/tags/v1/models/raid/<file>
```
