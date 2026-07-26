SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05. Group reports carry every build, including the
dungeon-route (`-dung`) loadouts.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/mn4m6syJTHeEowZ4v6D5ot))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 254,747 | `vsm-st` |
| Void-Scarred ranged | 230,954 | `vsr-st` |
| Annihilator ranged | 220,231 | `anr-st` |
| Annihilator melee | 202,247 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/q2qzdKjVqQfNMSwewrrfCv), [60s no lust](https://mimiron.raidbots.com/simbot/report/w7oFJcJYnqmBF54zhszt6x))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 701,137 | 751,626 | `vsm-aoe` |
| Annihilator ranged | 656,396 | 689,323 | `anr-aoe` |
| Void-Scarred ranged | 605,496 | 616,979 | `vsr-aoe` |
| Annihilator melee | 583,544 | 609,470 | `anm-aoe` |

## Dungeon route — Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/pViBbQooziqpgNTzTVtWxV))

`temple-of-sethraliss-route.simc` is a full Temple of Sethraliss M+ route with real pull
composition, chaining, and mob health from 12.1 PTR logs, scaled for a single actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has a dungeon-route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 453,125 | `vsm-dung` |
| Annihilator ranged | 425,179 | `anr-dung` |
| Void-Scarred ranged | 416,567 | `vsr-dung` |
| Annihilator melee | 387,248 | `anm-dung` |
| Void-Scarred melee, ST build | 364,273 | `vsm-st` |
| Annihilator ranged, ST build | 334,517 | `anr-st` |
| Void-Scarred ranged, ST build | 305,322 | `vsr-st` |
| Annihilator melee, ST build | 297,297 | `anm-st` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.
`vsr-dung`, `anr-dung`, and `anm-dung` currently use their identity's `-aoe` hash.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/vcSoYByPntfFQ9LfGZzu2w) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/nhxtgHLVkT96tNLZpYyREy) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/vyJJbQHhdkC7538hEMm5nN) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/w1VebFtwo5FwyKqzbVt2wL) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/8puFjaRDRrCp8rtPr7sVir) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/8tbc2J9twwsthKJDLrUahq) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/eSNK6LnFHWvUV36xZcDHgV) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/dnugWppMCH9sp3UzDSXmT7) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/7NUaijivVkKM7byeK4AV1j) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
