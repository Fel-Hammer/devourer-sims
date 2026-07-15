SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/oiBShmPYaaT7SCVyS3GxPU))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 258,055 | `vsm-st` |
| Void-Scarred ranged | 236,931 | `vsr-st` |
| Annihilator ranged | 224,268 | `anr-st` |
| Annihilator melee | 196,485 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/fwZY1gCnQU8Tr5meUu48aX), [60s no lust](https://mimiron.raidbots.com/simbot/report/gw4NzAigRk6xGw6YPjGmU1))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 684,998 | 816,305 | `vsm-aoe` |
| Annihilator ranged | 653,218 | 820,428 | `anr-aoe` |
| Void-Scarred ranged | 604,409 | 747,885 | `vsr-aoe` |
| Annihilator melee | 584,469 | 736,997 | `anm-aoe` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/3CKZVLDmWTPm3WB9MgacJS) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzMjNttAgAGAMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/sn6FRJUMij8okdL6sVtkP1) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/wNnYMoH72QZvU77GdqvtNa) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/b7oyTpd3nvWsnUd8vyBUF7) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/xq4Mg29xkSXynr8G8p3J4t) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/ojxGRWKsFF1m3ffPbjBkUT) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/vqNzmsbUCRQtTwPBcyHze3) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/37cycTB92g9K3EqoGmZs9D) |

## Temporary note:

The Void-Scarred melee list uses Vengeful Retreat right before The Hunt so Metamorphosis lands while
you're mid-leap. This works in game (SimC PR #11569), but stock SimC and Raidbots don't model the
leap yet, so the Void-Scarred melee single target number above reads a little low.

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
