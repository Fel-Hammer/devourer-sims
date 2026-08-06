SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/b1KoAtFensN2gNZKZ39J4H))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 275,154 | `vsm-st` |
| Void-Scarred ranged | 256,053 | `vsr-st` |
| Annihilator ranged | 254,317 | `anr-st` |
| Annihilator melee | 227,619 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/jrNa1vvw7NQU4yYK5JcRs1), [60s no lust](https://mimiron.raidbots.com/simbot/report/eYtht4vkNJzNpz6WjLXvo5))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 691,114 | 734,712 | `vsm-aoe` |
| Annihilator ranged | 671,310 | 690,176 | `anr-aoe` |
| Void-Scarred ranged | 604,319 | 602,889 | `vsr-aoe` |
| Annihilator melee | 585,642 | 600,923 | `anm-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/s5PoSb8igDgHChzG9kPjrU))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 464,839 | `vsm-dung` |
| Annihilator ranged | 455,344 | `anr-dung` |
| Void-Scarred ranged | 431,793 | `vsr-dung` |
| Annihilator melee | 400,455 | `anm-dung` |
| Annihilator ranged, ST build | 390,172 | `anr-st` |
| Void-Scarred melee, ST build | 386,916 | `vsm-st` |
| Void-Scarred ranged, ST build | 368,699 | `vsr-st` |
| Annihilator melee, ST build | 332,121 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZYmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/9q4q7DabnRQG37gpLYFmQf) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMPwMzMzYmZYmtZYsJLAIgBYGzMz2Mz0sNz2MzwMzA` | [report](https://mimiron.raidbots.com/simbot/report/boYoD3Da9Ys3JUPopNLvFD) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZYmtZGjNZBABMAzYmZ2mZmmtZ2mZGjZA` | [report](https://mimiron.raidbots.com/simbot/report/pHv1Hr6CQveDBpzV6mFCQf) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGMMA` | [report](https://mimiron.raidbots.com/simbot/report/vyJ99ygcg1AuH3AorxNi1t) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/bQnwPn38mNSg8ZFmWbHLCY) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZmZmFzYsolFmZmZ2abmZGAzMDABMGMMA` | [report](https://mimiron.raidbots.com/simbot/report/8bmW4HJTPZjjSTxTgDXLB1) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsYGjFtswMzMzWbzMzAYmZAIgxgxMA` | [report](https://mimiron.raidbots.com/simbot/report/dDiY3JtEH3x8YjLLNKn2C2) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/7HwKcBMVXCcvnDaHBKuySr) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/hQRArdpuG3m8dkwiTANpmL) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
