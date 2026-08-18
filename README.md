SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

All numbers include the August 14 Devourer balance changes, applied to the sim inputs as manual
data adjustments until they land in SimC's own data.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/fDhaVDH8w1ZQu5yfzUey6K))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 266,923 | `vsm-st` |
| Void-Scarred melee, cleave build | 253,398 | `vsm-cleave` |
| Void-Scarred ranged | 237,950 | `vsr-st` |
| Annihilator ranged | 236,112 | `anr-st` |
| Annihilator melee | 215,841 | `anm-st` |

## 3 targets (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/6WqSfKHWgSPNZu4E4qTh1E))

`vsm-cleave` is a two-to-three-target compromise: the melee AoE chassis keeping Second Helping
with single-target points on top.

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 504,189 | `vsm-aoe` |
| Void-Scarred melee, cleave build | 499,110 | `vsm-cleave` |
| Annihilator ranged | 488,110 | `anr-aoe` |
| Void-Scarred ranged | 432,494 | `vsr-aoe` |
| Void-Scarred melee, ST build | 425,632 | `vsm-st` |
| Annihilator melee | 422,458 | `anm-aoe` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/o6d6HDegAaZWyS4ctK3iAQ), [60s no lust](https://mimiron.raidbots.com/simbot/report/hrWdysX7o9TtDug4bzKQyZ))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 682,744 | 739,185 | `vsm-aoe` |
| Annihilator ranged | 675,089 | 698,812 | `anr-aoe` |
| Void-Scarred melee, cleave build | 667,667 | 728,056 | `vsm-cleave` |
| Annihilator melee | 588,896 | 614,641 | `anm-aoe` |
| Void-Scarred ranged | 579,270 | 585,307 | `vsr-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/qkRohqiPQ7eQibPFYEN7cW))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 451,289 | `vsm-dung` |
| Void-Scarred melee, cleave build | 446,268 | `vsm-cleave` |
| Annihilator ranged | 445,770 | `anr-dung` |
| Void-Scarred ranged | 416,138 | `vsr-dung` |
| Annihilator melee | 396,493 | `anm-dung` |
| Void-Scarred melee, ST build | 387,996 | `vsm-st` |
| Annihilator ranged, ST build | 373,232 | `anr-st` |
| Void-Scarred ranged, ST build | 362,002 | `vsr-st` |
| Annihilator melee, ST build | 337,304 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZYmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/8ru3wBL5uzkrdJLbQRN8P7) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMzMzMzYmZYmtZGjNZBABMADzMz2Mz0sNz2MzwMDA` | [report](https://mimiron.raidbots.com/simbot/report/vNzobG6KcEADroJDRqMJQT) |
| vsm-cleave | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAY5BGz2gZAAAAAAAAYGzw8AzMzMzMzMjZ2mZM202CACYAMmZmtZmpZbmlZmxYGA` | [report](https://mimiron.raidbots.com/simbot/report/pSuPx6yrJP4gJwc6GejaVt) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZYmtZGjNZBABMAzYmZ2mZmmtZ2mZGjZA` | [report](https://mimiron.raidbots.com/simbot/report/vtGc1HVYsHMguznjMVR29c) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGMMA` | [report](https://mimiron.raidbots.com/simbot/report/opTpZSN3WcFGZQ7KRxNEz2) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/epedH5cRXs1utAMtSEut19) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZmZmFzYsolFmZmZ2abmZGAzMDABMGMMA` | [report](https://mimiron.raidbots.com/simbot/report/j9vdadFBXhp5MNkyF6HJ7p) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMzYmFzYsolFmZmZ2abmZGAjZAIgxgxMA` | [report](https://mimiron.raidbots.com/simbot/report/i9simEH6mJqL9nGknKPXRB) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZMzsMzYsolFmZmZ2abmZmBwMDABmZYY8BA` | [report](https://mimiron.raidbots.com/simbot/report/p772wE16LwRKnnASyg4Hzx) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/8JAL4u3x3s8jZdnLifiEqf) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
