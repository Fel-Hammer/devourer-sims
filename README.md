SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/3Y7FrU9B69edLQhdJYw89Q))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 252,656 | `vsm-st` |
| Void-Scarred ranged | 225,536 | `vsr-st` |
| Annihilator ranged | 215,017 | `anr-st` |
| Annihilator melee | 196,892 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/wuESyLb44rJxwKwcTHyvAR), [60s no lust](https://mimiron.raidbots.com/simbot/report/12VnVBBz8eKPpexLcfcMWL))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 658,011 | 697,040 | `vsm-aoe` |
| Annihilator ranged | 612,563 | 634,217 | `anr-aoe` |
| Void-Scarred ranged | 557,743 | 558,440 | `vsr-aoe` |
| Annihilator melee | 538,536 | 556,782 | `anm-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/8bHhxPckFkT4Zy3AQFKqJ4))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 441,630 | `vsm-dung` |
| Annihilator ranged | 411,217 | `anr-dung` |
| Void-Scarred ranged | 403,279 | `vsr-dung` |
| Void-Scarred melee, ST build | 375,009 | `vsm-st` |
| Annihilator melee | 370,689 | `anm-dung` |
| Annihilator ranged, ST build | 345,010 | `anr-st` |
| Void-Scarred ranged, ST build | 330,431 | `vsr-st` |
| Annihilator melee, ST build | 302,956 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/1bEEkWUDJq6FUD2XGEseaf) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/sJ3Lyxijsmj1sGG8JNS95C) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/oUNpr6Zy3s4UdLQZedmSEh) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGMMA` | [report](https://mimiron.raidbots.com/simbot/report/tSKAwzPmTFF33XZGTT449j) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/rPJ2z7EWjbVJVALqfs5SVQ) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/54hSVTV4PGm6VwZ1uojBn8) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/vo5XRuJ6BNw4LHqVu7XD8A) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/wYVL7MvGDQe77okUgBKRBf) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/o53afGpSP6SC5kEZYUEG6e) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
