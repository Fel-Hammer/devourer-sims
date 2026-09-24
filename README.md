SimC profile for Devourer Demon Hunter, Midnight 12.1.5 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/hCLsT9Mjt7sJLcigFeBPRB))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred | 278,184 | `voidscarred-st` |
| Annihilator | 253,652 | `annihilator-st` |

## 3 targets (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/dRZ54Rafv8xG4Ynn8noacP))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred | 536,599 | `voidscarred-aoe` |
| Annihilator | 523,146 | `annihilator-aoe` |
| Void-Scarred, ST build | 456,739 | `voidscarred-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/htU8QoKfj42vEWaHhmwpZY), [60s no lust](https://mimiron.raidbots.com/simbot/report/6k1dGEU11GyvJDqp29raN4))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred | 747,076 | 805,387 | `voidscarred-aoe` |
| Annihilator | 721,372 | 747,639 | `annihilator-aoe` |

## 10 targets (60s, no lust) ([report](https://mimiron.raidbots.com/simbot/report/9Yw7DGmq3r8k4a8PPJquwQ))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred | 1,279,849 | `voidscarred-aoe` |
| Annihilator | 1,243,933 | `annihilator-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/gPQxB4s95JYhbTQ7b78dvV))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor, with health
at a +20 keystone. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred | 604,439 | `voidscarred-dung` |
| Annihilator | 599,755 | `annihilator-dung` |
| Void-Scarred, ST build | 531,709 | `voidscarred-st` |
| Annihilator, ST build | 530,248 | `annihilator-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`annihilator-dung` reuses the identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| voidscarred-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZYmZYmlZGjNttAgAGAjZmZbmZa2mZbmhxMGA` | [report](https://mimiron.raidbots.com/simbot/report/qFciF6TvEjkiK31PpihHkJ) |
| voidscarred-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMzMzMzYmZYmlZGjNtsAgAGAMzMLzMTz2MbzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/wq1UhnGiQ5tnUCjsz4rLrt) |
| voidscarred-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZGzMDzsMzYsplFAEwAYMzMLzMTz2MbzMwMGA` | [report](https://mimiron.raidbots.com/simbot/report/bNeL3Lp6mLKmbx5tJCvzC8) |
| annihilator-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZGzsYGjFtswMzMzWbzMzAYmZAIwDMGMMA` | [report](https://mimiron.raidbots.com/simbot/report/79bdMhwDEe9fvdutDGUpYw) |
| annihilator-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsYGjFZhZmZmt2mZmBwYGAC8AjZYMD` | [report](https://mimiron.raidbots.com/simbot/report/fXW7MVk7x6vnScMxgtdQKq) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
