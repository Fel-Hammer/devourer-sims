SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05. Group reports carry every build, including the
dungeon-route (`-dung`) loadouts.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/1mfeEp7pZU6Dct2FFWePWv))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 256,792 | `vsm-st` |
| Void-Scarred ranged | 233,110 | `vsr-st` |
| Annihilator ranged | 221,339 | `anr-st` |
| Annihilator melee | 202,973 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/v8WnoYfCWh7gkNGzWAncDr), [60s no lust](https://mimiron.raidbots.com/simbot/report/3cryaiz1fSU1JC4CviMR6e))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 711,349 | 759,823 | `vsm-aoe` |
| Annihilator ranged | 659,562 | 689,421 | `anr-aoe` |
| Void-Scarred ranged | 610,604 | 622,260 | `vsr-aoe` |
| Annihilator melee | 585,053 | 610,317 | `anm-aoe` |

## Dungeon route — Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/hE766goTw6GTiaTX9s4exY))

`temple-of-sethraliss-route.simc` is a full Temple of Sethraliss M+ route with real pull
composition, chaining, and mob health from 12.1 PTR logs, scaled for a single actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has a dungeon-route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 461,702 | `vsm-dung` |
| Annihilator ranged | 429,659 | `anr-dung` |
| Void-Scarred ranged | 424,068 | `vsr-dung` |
| Annihilator melee | 389,409 | `anm-dung` |
| Void-Scarred melee, ST build | 379,313 | `vsm-st` |
| Annihilator ranged, ST build | 348,098 | `anr-st` |
| Void-Scarred ranged, ST build | 317,275 | `vsr-st` |
| Annihilator melee, ST build | 308,380 | `anm-st` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.
`vsr-dung`, `anr-dung`, and `anm-dung` currently use their identity's `-aoe` hash.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/49N5WBJsZZyYMHn6LzCNNh) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/aJDyMthSfjywFRL4wsaALA) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/bEMskEWTXYMX6YeFpHaJHp) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/38rmKrNC8MKGN8fBb6nqQt) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/qAh8WGGirDwseaXMMe7tEE) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/okasrf9cAiXTZGx9NMaFvF) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/gDHqziQzVq2YwkstJxHLgp) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/uUKRBQtynG9bacWk66SGmj) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/44yYV6hGxSddmGDRC4vXox) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
