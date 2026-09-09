# Undead Fortresses v1.3.2 — Release Notes

Undead Fortresses v1.3.2 is the first public Custom Scenario release published in the CMZ World Builder Custom Scenarios repository.

> **Community-made project:** Undead Fortresses and CMZ World Builder are not official CastleMiner Z releases and are not affiliated with or endorsed by CastleMiner Z's developers or publisher.

## Main changes

- Terrain-integrated foundations replace the previous universal Bloodstone foundation treatment.
- Rock is the standard non-Hell foundation material while contextual Hell-region Bloodstone remains supported by native terrain/material rules.
- Deep foundation gaps use a two-layer Rock deck and 8m support-pier rhythm rather than large solid filler masses.
- Fortress placement now uses coverage-balanced shell rotation with bounded seed jitter, removing the old visible five-spoke distribution while keeping progression-aware, deterministic placement.
- The authored range remains fixed at 5,200m, the end of CastleMiner Z's first full Hell ring.

## Preserved systems

- 30 fortress archetypes
- 12 exterior profiles
- Sparse / Standard / Dense / Very Dense
- Fortress Near Spawn
- Small / Medium / Large archetypes
- Native encounters and boss spawners
- Native Loot and Lucky Loot Blocks
- Mirrored layouts
- Native CastleMiner Z persisted world data
- Vanilla-client compatibility after generation

## Technical foundation identifier

The scenario declares `worldGeneration.base = official-cmz`. `official-cmz` is an internal CMZ World Builder protocol identifier for its validated stock-compatible CastleMiner Z Normal World foundation. It is not a claim of official CastleMiner Z status, affiliation, or endorsement.

## Release artifact and integrity

`CMZ_Undead_Fortresses_v1.3.2.cmzscenario`

GitHub automatically publishes the SHA-256 digest for the uploaded release asset. The digest displayed by GitHub on the **Releases** page is the authoritative public checksum for that file.
