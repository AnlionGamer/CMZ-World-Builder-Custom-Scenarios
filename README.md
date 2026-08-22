# CMZ World Builder Custom Scenarios

Community-made Custom Scenarios for **CastleMiner Z World Builder**.

> **Independent community project:** CMZ World Builder and the Custom Scenarios in this repository are community-made projects. They are not official CastleMiner Z releases and are not affiliated with or endorsed by CastleMiner Z's developers or publisher.

This repository is the public home for finished, release-ready `.cmzscenario` projects intended for CastleMiner Z 1.9.9.8 and the CMZ World Builder ecosystem.

## Released scenarios

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
- Custom Scenarios remain separate from CMZ World Builder itself; World Builder is the community-made tool/framework that loads and generates them.

## Compatibility

Unless a scenario states otherwise:

- **Game:** CastleMiner Z 1.9.9.8 (Steam)
- **Tool:** CMZ World Builder 1.1.2 or newer
- **Scenario package:** `.cmzscenario`

A scenario may declare `worldGeneration.base = official-cmz` in `scenario.json`. **`official-cmz` is an internal World Builder protocol identifier** for the validated stock-compatible CastleMiner Z Normal World foundation. It does not indicate affiliation, endorsement, or official CastleMiner Z status.

## Downloads

Use this repository's **Releases** page for finished `.cmzscenario` files and matching SHA-256 checksum files.

## Related project

CMZ World Builder: https://github.com/AnlionGamer/CMZ-World-Builder
