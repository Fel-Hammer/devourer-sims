SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

All numbers include the August 14 Devourer balance changes, applied to the sim inputs as manual
data adjustments until they land in SimC's own data.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/1q9zp4QRDAwEc5TDoFiP2z))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 257,346 | `vsm-st` |
| Void-Scarred ranged | 226,284 | `vsr-st` |
| Annihilator ranged | 226,096 | `anr-st` |
| Annihilator melee | 207,040 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/g1ZdedpU8LGdum6jYXuVdX), [60s no lust](https://mimiron.raidbots.com/simbot/report/jQaNMbequEcs83cFiPQU2Y))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 660,552 | 720,385 | `vsm-aoe` |
| Annihilator ranged | 653,928 | 682,194 | `anr-aoe` |
| Annihilator melee | 568,308 | 594,662 | `anm-aoe` |
| Void-Scarred ranged | 551,820 | 556,910 | `vsr-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/hTkMdsB4yyjfyMmDMA2ndt))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 442,099 | `vsm-dung` |
| Annihilator ranged | 431,305 | `anr-dung` |
| Void-Scarred ranged | 401,857 | `vsr-dung` |
| Annihilator melee | 386,680 | `anm-dung` |
| Void-Scarred melee, ST build | 386,473 | `vsm-st` |
| Annihilator ranged, ST build | 366,512 | `anr-st` |
| Void-Scarred ranged, ST build | 350,460 | `vsr-st` |
| Annihilator melee, ST build | 330,344 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZYmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/r2LFpNXnttyQ6Lnyc3dPf1) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMPwMzMzYmZYmtZGjNZBABMAzYmZ2mZmmtZ2mZGmZA` | [report](https://mimiron.raidbots.com/simbot/report/mHGTyFi9yfpCEhWQjnSZxd) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZYmtZGjNZBABMAzYmZ2mZmmtZ2mZGjZA` | [report](https://mimiron.raidbots.com/simbot/report/2wmaDaUNdytcUw6wsfvoS3) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGMMA` | [report](https://mimiron.raidbots.com/simbot/report/q8bQUhmiYwnQo1sB4bb5JC) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/ucHHfkAQpotLQ6aA33QCnb) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZmZmFzYsolFmZmZ2abmZGAzMDABMGMMA` | [report](https://mimiron.raidbots.com/simbot/report/gaTiWemkbXcB4gmAwz3c7y) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMzYmFzYsolFmZmZ2abmZGAjZAIgxgxMA` | [report](https://mimiron.raidbots.com/simbot/report/eK4wyAZbb1E4eDJgaMcUio) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZMzsMzYsolFmZmZ2abmZmBwMDABmZYY8BA` | [report](https://mimiron.raidbots.com/simbot/report/bA8jWhuG9FsZGUfrr3rgT7) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/oxwFRhVfc7Y8r3xeKxzWDD) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
