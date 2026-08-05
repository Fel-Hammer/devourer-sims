SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/39rsd7uCy1z6fwrG212ZAB))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 273,725 | `vsm-st` |
| Void-Scarred ranged | 255,995 | `vsr-st` |
| Annihilator ranged | 254,226 | `anr-st` |
| Annihilator melee | 227,619 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/h3tHD3uh8bHCTCtrbkuSMK), [60s no lust](https://mimiron.raidbots.com/simbot/report/qprAbumDYteaqyz6fmVL3b))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 682,275 | 728,055 | `vsm-aoe` |
| Annihilator ranged | 671,205 | 690,277 | `anr-aoe` |
| Void-Scarred ranged | 604,165 | 602,969 | `vsr-aoe` |
| Annihilator melee | 585,875 | 601,089 | `anm-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/jH6zAjb2McPAhACr9VHWA4))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 462,539 | `vsm-dung` |
| Annihilator ranged | 455,455 | `anr-dung` |
| Void-Scarred ranged | 431,698 | `vsr-dung` |
| Annihilator melee | 400,306 | `anm-dung` |
| Annihilator ranged, ST build | 389,955 | `anr-st` |
| Void-Scarred melee, ST build | 388,602 | `vsm-st` |
| Void-Scarred ranged, ST build | 368,712 | `vsr-st` |
| Annihilator melee, ST build | 332,146 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/7UgPFLWR6CQeyM8qHCmjmu) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/tP1XFPb5NYJsJamfxNPTDn) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/4HfpDXi4PFvVhcW7SgYhZ8) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGMMA` | [report](https://mimiron.raidbots.com/simbot/report/vekdRwLNUBepBLoaf4E7zu) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/vitBb2uxUxNzVR9dLvttTk) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZmZmFzYsolFmZmZ2abmZGAzMDABMGMMA` | [report](https://mimiron.raidbots.com/simbot/report/5Uq9yxyURX1SDK3RHgGvnx) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsYGjFtswMzMzWbzMzAYmZAIgxgxMA` | [report](https://mimiron.raidbots.com/simbot/report/iY8L8EZx7bdoJEvQbALuwH) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/779HCAKKNPKy9DdzndKbgJ) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/9tdxU1E8hzR6WhrFtbU478) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
