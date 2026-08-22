# CMZ World Builder Custom Scenarios

Official Custom Scenarios for **CastleMiner Z World Builder**.

This repository is the public home for finished, release-ready `.cmzscenario` projects intended for CastleMiner Z 1.9.9.8 and the CMZ World Builder ecosystem.

## Repository policy

- Only finished Custom Scenario projects belong in this repository.
- Development builders, builder archives, private build tooling, test candidates, intermediate outputs, and temporary diagnostics are not committed.
- A scenario is added here only after its generated `.cmzscenario` passes its release-ready package audit.
- Finished downloadable `.cmzscenario` files and their SHA-256 files are published through GitHub Releases.
- Scenario documentation and release metadata may be kept under `Scenarios/<Scenario-Name>/`.
- Each scenario keeps its own version number and release history.
- Custom Scenarios remain separate from the CMZ World Builder itself; World Builder is the tool/framework that loads and generates them.

## Compatibility

Unless a scenario states otherwise:

- **Game:** CastleMiner Z 1.9.9.8 (Steam)
- **Tool:** CMZ World Builder 1.1.2 or newer
- **Scenario package:** `.cmzscenario`

A scenario may declare its required world-generation foundation in `scenario.json`, including `worldGeneration.base = official-cmz` when it requires the validated normal CastleMiner Z foundation.

## Official scenarios

Finished scenarios will be listed here after their release artifacts pass final audit.

## Downloads

Use this repository's **Releases** page for finished `.cmzscenario` files and matching SHA-256 checksum files.

## Related project

CMZ World Builder: https://github.com/AnlionGamer/CMZ-World-Builder
