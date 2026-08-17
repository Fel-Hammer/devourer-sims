SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

All numbers include the August 14 Devourer balance changes, applied to the sim inputs as manual
data adjustments until they land in SimC's own data.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/hJaM5rsMX53wk3aX2XRTHk))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 266,196 | `vsm-st` |
| Void-Scarred melee, cleave build | 252,570 | `vsm-cleave` |
| Void-Scarred ranged | 237,043 | `vsr-st` |
| Annihilator ranged | 235,451 | `anr-st` |
| Annihilator melee | 215,114 | `anm-st` |

## 3 targets (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/ioste8L5YuWzAdkdyRFSmE))

`vsm-cleave` is a two-to-three-target compromise: the melee AoE chassis keeping Second Helping
with single-target points on top.

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 502,738 | `vsm-aoe` |
| Void-Scarred melee, cleave build | 497,486 | `vsm-cleave` |
| Annihilator ranged | 487,273 | `anr-aoe` |
| Void-Scarred ranged | 430,812 | `vsr-aoe` |
| Void-Scarred melee, ST build | 424,361 | `vsm-st` |
| Annihilator melee | 421,132 | `anm-aoe` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/cvXKWFi78v5pQaospAEP5Z), [60s no lust](https://mimiron.raidbots.com/simbot/report/c9Skc9jgZFXAmbkX2m9r2M))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 680,808 | 737,565 | `vsm-aoe` |
| Annihilator ranged | 673,941 | 702,281 | `anr-aoe` |
| Void-Scarred melee, cleave build | 665,701 | 726,575 | `vsm-cleave` |
| Annihilator melee | 586,819 | 613,650 | `anm-aoe` |
| Void-Scarred ranged | 577,247 | 583,585 | `vsr-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/vsvitTYyK9iYtK2scKiAsq))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 450,179 | `vsm-dung` |
| Void-Scarred melee, cleave build | 445,288 | `vsm-cleave` |
| Annihilator ranged | 444,589 | `anr-dung` |
| Void-Scarred ranged | 414,844 | `vsr-dung` |
| Annihilator melee | 395,757 | `anm-dung` |
| Void-Scarred melee, ST build | 386,855 | `vsm-st` |
| Annihilator ranged, ST build | 372,351 | `anr-st` |
| Void-Scarred ranged, ST build | 360,745 | `vsr-st` |
| Annihilator melee, ST build | 336,292 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZYmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/117pAjmBbDbpPLWF2xoxnV) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMzMzMzYmZYmtZGjNZBABMADzMz2Mz0sNz2MzwMDA` | [report](https://mimiron.raidbots.com/simbot/report/95aoxCN758asmiBe1w3GdS) |
| vsm-cleave | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAY5BGz2gZAAAAAAAAYGzw8AzMzMzMzMjZ2mZM202CACYAMmZmtZmpZbmlZmxYGA` | [report](https://mimiron.raidbots.com/simbot/report/dWqh9RDw4p8mwxCMRoYADu) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZYmtZGjNZBABMAzYmZ2mZmmtZ2mZGjZA` | [report](https://mimiron.raidbots.com/simbot/report/pXE1ZzuL95xuypPCC2kjbb) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGMMA` | [report](https://mimiron.raidbots.com/simbot/report/az5FuJXuMF15fKiaddphW9) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/3EuKjwN24jzLFS64rqJC1L) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZmZmFzYsolFmZmZ2abmZGAzMDABMGMMA` | [report](https://mimiron.raidbots.com/simbot/report/grA8WjGxFs7bU9qWKCeogN) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMzYmFzYsolFmZmZ2abmZGAjZAIgxgxMA` | [report](https://mimiron.raidbots.com/simbot/report/qx2BDPUEyM8jVtemXmJGVg) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZMzsMzYsolFmZmZ2abmZmBwMDABmZYY8BA` | [report](https://mimiron.raidbots.com/simbot/report/fQw5LdX8QvPWhz1sF8joUR) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/68aqTJb68QxW6NtNQDkaRj) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
