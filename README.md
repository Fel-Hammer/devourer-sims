SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05. Group reports carry every build, including the
dungeon-route (`-dung`) loadouts.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/pUBsLvBCUctjykk2RC57ww))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 254,575 | `vsm-st` |
| Void-Scarred ranged | 230,813 | `vsr-st` |
| Annihilator ranged | 219,739 | `anr-st` |
| Annihilator melee | 201,998 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/sX81ww1MnGxDPNdbhn5ibW), [60s no lust](https://mimiron.raidbots.com/simbot/report/nWSKAoQEus9SrZuzmGWdbw))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 699,452 | 750,289 | `vsm-aoe` |
| Annihilator ranged | 651,501 | 683,380 | `anr-aoe` |
| Void-Scarred ranged | 603,733 | 615,653 | `vsr-aoe` |
| Annihilator melee | 582,102 | 608,317 | `anm-aoe` |

## Dungeon route — Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/jYCieZNoac1Eh8dop4CZo2))

`temple-of-sethraliss-route.simc` is a full Temple of Sethraliss M+ route with real pull
composition, chaining, and mob health from 12.1 PTR logs, scaled for a single actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has a dungeon-route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 452,089 | `vsm-dung` |
| Annihilator ranged | 421,786 | `anr-dung` |
| Void-Scarred ranged | 415,872 | `vsr-dung` |
| Annihilator melee | 386,291 | `anm-dung` |
| Void-Scarred melee, ST build | 363,631 | `vsm-st` |
| Annihilator ranged, ST build | 333,870 | `anr-st` |
| Void-Scarred ranged, ST build | 304,236 | `vsr-st` |
| Annihilator melee, ST build | 296,484 | `anm-st` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.
`vsr-dung`, `anr-dung`, and `anm-dung` currently use their identity's `-aoe` hash.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/vxArgwSsRmagAxvbWenC6r) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/ouXyWXHmqGBpZbGZgvT7fY) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/q1D76K2JvihDZF5xtemBSV) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/5YT9gFCXW5wmRJwMHqTKdj) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/rQBi1b6C9rHwYtzuJGmGSN) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/26epdqkwEBFmrJpsaKsHRx) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/wpjnjkfn7KBqraMKgZRPi6) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/48qbaBkzh4hfTVzFu2ohn8) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/6EtqBYrS3MaCSTDdE9uKQk) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
