# CMZ World Builder Custom Scenarios

Official Custom Scenarios for **CastleMiner Z World Builder**.

This repository is the public home for finished, release-ready `.cmzscenario` projects intended for CastleMiner Z 1.9.9.8 and the CMZ World Builder ecosystem.

## Official scenarios

| Scenario | Current version | Status | Description |
| --- | ---: | --- | --- |
| [Undead Fortresses](Scenarios/Undead-Fortresses/) | **v1.3.2** | Released | Deterministic native-block fortresses distributed through CastleMiner Z progression to the end of the first full Hell ring. |

Future finished Custom Scenarios will be added to this catalog as they pass release audit.

## Repository policy

- Only finished Custom Scenario projects belong in this repository.
- Development builders, builder archives, private build tooling, test candidates, intermediate outputs, and temporary diagnostics are not committed.
- A scenario is added here only after its generated `.cmzscenario` passes its release-ready package audit.
- Finished downloadable `.cmzscenario` files and their SHA-256 files are published through GitHub Releases.
- Public scenario metadata, documentation, checksums, and release history are kept under `Scenarios/<Scenario-Name>/`.
- Each scenario keeps its own version number and release history.
- Custom Scenarios remain separate from the CMZ World Builder itself; World Builder is the tool/framework that loads and generates them.

## Compatibility

Unless a scenario states otherwise:

- **Game:** CastleMiner Z 1.9.9.8 (Steam)
- **Tool:** CMZ World Builder 1.1.2 or newer
- **Scenario package:** `.cmzscenario`

A scenario may declare its required world-generation foundation in `scenario.json`, including `worldGeneration.base = official-cmz` when it requires the validated normal CastleMiner Z foundation.

## Downloads

Use this repository's **Releases** page for finished `.cmzscenario` files and matching SHA-256 checksum files.

## Related project

CMZ World Builder: https://github.com/AnlionGamer/CMZ-World-Builder
