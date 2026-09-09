# Undead Fortresses

**Current release:** v1.3.2  
**Game:** CastleMiner Z 1.9.9.8  
**Minimum World Builder:** v1.1.2  
**Scenario ID:** `undead-fortresses`

> **Unofficial community project:** Undead Fortresses is independently created and published by AnlionGamer for the community-developed CMZ World Builder. It is not an official CastleMiner Z release and is not affiliated with, sponsored by, approved by, or endorsed by CastleMiner Z's developers or publisher.

It generates deterministic native-block fortresses throughout a normal CastleMiner Z world, from the starting regions through the end of the first full Hell ring.

## v1.3.2 highlights

- Fixed **5,200m** authored radius through the end of the first full Hell ring.
- Uses World Builder's `official-cmz` technical foundation mode — the internal identifier for its validated stock-compatible CastleMiner Z Normal World foundation, not a statement of official status, affiliation, sponsorship, or endorsement.
- Terrain-integrated **Rock foundations** outside Hell instead of a universal Bloodstone structural layer.
- Deep terrain gaps use a two-layer Rock deck with terrain-connected support piers rather than large packed filler volumes.
- Coverage-balanced fortress distribution removes the old fixed-bearing star/spoke pattern while retaining deterministic progression-aware placement.
- Sparse, Standard, Dense, and **Very Dense** densities remain supported.
- Optional **Fortress Near Spawn** guarantee remains available.
- 30 fortress archetypes and 12 exterior profiles remain part of the scenario.
- Native CastleMiner Z encounters, loot blocks, Lucky Loot Blocks, and vanilla-compatible persisted world data are retained.

## Runtime validation

The release-final functional generator behavior was validated in CastleMiner Z 1.9.9.8 using **Very Dense + Fortress Near Spawn** with seed `1367396337`:

- 67 / 67 planned fortresses placed.
- 0 terrain-bound slot reassignments.
- 30 / 30 archetype audit PASS.
- 12 / 12 exterior-profile audit PASS.
- 240 / 240 transformed-layout audit PASS.
- Foundation appearance accepted in gameplay.
- Fortress spacing/distribution accepted after exact-center and World Inspector review.
- World Inspector reported 2,801 coordinate records and 18.4 MB persisted data.
- 2,802 / 2,802 protected-save files were valid/readable with 0 warnings.

An earlier v1.3.0 Very Dense + Fortress Near Spawn world also sustained a public-host session exceeding five hours with 8 unique remote players, 11 join events, 3 rejoins, and a peak of 4 simultaneous remote players. That earlier session is supporting evidence for the scenario's native-world architecture, not a universal multiplayer stability guarantee for every v1.3.2 world.

## License and Attribution

The current repository copy and future Undead Fortresses work are governed by the **AnlionGamer Community Distribution Terms v1.0**. See [`LICENSE.md`](LICENSE.md).

The terms allow normal use, source inspection, and private modification. Public redistribution of the scenario, its source/material, packaged scenario, forks, or modified versions requires **prior permission from AnlionGamer** and must remain **non-commercial**. Sale and paid access are prohibited without separate permission.

Copies already distributed under earlier documented terms retain the permissions that accompanied those copies; changing the repository license does not revoke earlier grants made to previously distributed copies of v1.3.2 or earlier versions.

Castle Miner Z and its original game material remain the property of their respective rights holders. See [`NOTICE.md`](NOTICE.md) for project attribution and the full affiliation notice.

Future `.cmzscenario` release packages should carry the applicable license and project notice inside the package so the terms remain attached when the scenario is shared separately from GitHub.

## Downloads

Download the finished `.cmzscenario` from this repository's GitHub Releases page.

## Release artifact and integrity

`CMZ_Undead_Fortresses_v1.3.2.cmzscenario`

GitHub automatically publishes the SHA-256 digest for the uploaded release asset. The digest displayed by GitHub on the **Releases** page is the authoritative public checksum for that file.

This repository does not separately publish a manual release-file checksum. SHA-256 values used inside scenario/package metadata remain technical integrity data and are not alternate public release checksums.

## Repository contents

This directory contains public metadata and documentation for the audited release package. Development builders and private build tooling are intentionally excluded from this repository.
