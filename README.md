SimC profile for Devourer Demon Hunter, Midnight 12.1.5 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

All numbers include the 12.1.5 PTR changes SimC's own data does not carry yet, applied as the
`override.spell_data` lines at the top of `devourer.simc`.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/s7HycWue3wz8vHUdVthrtL))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 271,571 | `vsm-st` |
| Annihilator ranged | 249,335 | `anr-st` |

## 3 targets (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/6W2NBsHWqcfq8zJhwGazu9))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 523,044 | `vsm-aoe` |
| Annihilator ranged | 507,584 | `anr-aoe` |
| Void-Scarred melee, ST build | 444,395 | `vsm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/bkQs5PLeFsaMumfVBSD8kM), [60s no lust](https://mimiron.raidbots.com/simbot/report/7p6xYRTSJoYqgzXsYSZm6i))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 726,880 | 794,374 | `vsm-aoe` |
| Annihilator ranged | 695,516 | 730,400 | `anr-aoe` |

## 10 targets (60s, no lust) ([report](https://mimiron.raidbots.com/simbot/report/oe2RW22ozS2dvhbcyH6SD5))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 1,248,184 | `vsm-aoe` |
| Annihilator ranged | 1,195,060 | `anr-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/wCsv1kMQ5RjJnzGBVHxRXr))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor, with health
at a +20 keystone. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 502,453 | `vsm-dung` |
| Annihilator ranged | 497,360 | `anr-dung` |
| Void-Scarred melee, ST build | 437,013 | `vsm-st` |
| Annihilator ranged, ST build | 432,412 | `anr-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`anr-dung` reuses the identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZYmZYmlZGjNttAgAGAjZmZbmZa2mZbmhxMGA` | [report](https://mimiron.raidbots.com/simbot/report/sp3Vws7hQcrFddSrhJ1Khq) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMzMzMzYmZYmlZGjNtsAgAGAMzMLzMTz2MbzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/8khSfcqjwTnNKnJZHPhQBM) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZGzMDzsMzYsplFAEwAYMzMLzMTz2MbzMwMGA` | [report](https://mimiron.raidbots.com/simbot/report/6s8UD7dNnptWyM1PxZvZid) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZGzsYGjFtswMzMzWbzMzAYmZAIwDMGMMA` | [report](https://mimiron.raidbots.com/simbot/report/sJ7Ag1fZ3T8eDfmuR9Z3Cy) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsYGjFZhZmZmt2mZmBwYGAC8AjZYMD` | [report](https://mimiron.raidbots.com/simbot/report/ir6WS8uczGjbSBdnaLvnfU) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
