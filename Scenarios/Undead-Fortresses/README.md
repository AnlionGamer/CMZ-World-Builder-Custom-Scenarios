# Undead Fortresses

**Current release:** v1.3.2  
**Game:** CastleMiner Z 1.9.9.8  
**Minimum World Builder:** v1.1.2  
**Scenario ID:** `undead-fortresses`

Undead Fortresses is an official CastleMiner Z World Builder Custom Scenario. It generates deterministic native-block fortresses throughout a normal CastleMiner Z world, from the starting regions through the end of the first full Hell ring.

## v1.3.2 highlights

- Fixed **5,200m** authored radius through the end of the first full Hell ring.
- Uses World Builder's `official-cmz` normal-world foundation.
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

## Downloads

Download the finished `.cmzscenario` and matching SHA-256 checksum from this repository's GitHub Releases page.

## Release artifact

`CMZ_Undead_Fortresses_v1.3.2.cmzscenario`

SHA-256:

```text
BFAF207F276EFF3123D9A919C4C43A16639147E9B4347FB34BC2BC9060E0F910
```

## Repository contents

This directory contains the public metadata and documentation carried by the audited release package. Development builders and private build tooling are intentionally excluded from this repository.
