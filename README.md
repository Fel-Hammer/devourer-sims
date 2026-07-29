SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc`, Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05. Group reports carry every build, including the
dungeon-route (`-dung`) loadouts.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/3bMKTTSZKMqoZFDaXPfCNk))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 254,568 | `vsm-st` |
| Void-Scarred ranged | 231,019 | `vsr-st` |
| Annihilator ranged | 219,181 | `anr-st` |
| Annihilator melee | 201,052 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/7MhG9U81YAS6mGKJ3EYdSn), [60s no lust](https://mimiron.raidbots.com/simbot/report/u78MQT4y3d4T82zugziv37))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 702,296 | 753,274 | `vsm-aoe` |
| Annihilator ranged | 652,025 | 683,892 | `anr-aoe` |
| Void-Scarred ranged | 603,691 | 617,001 | `vsr-aoe` |
| Annihilator melee | 579,145 | 605,987 | `anm-aoe` |

## Dungeon route — Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/a4rH5gWLk92TZ2BpJsGUe6))

`temple-of-sethraliss-route.simc` is a full Temple of Sethraliss M+ route with real pull
composition, chaining, and mob health from 12.1 PTR logs, scaled for a single actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has a dungeon-route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 456,660 | `vsm-dung` |
| Annihilator ranged | 425,875 | `anr-dung` |
| Void-Scarred ranged | 420,291 | `vsr-dung` |
| Annihilator melee | 386,053 | `anm-dung` |
| Void-Scarred melee, ST build | 377,689 | `vsm-st` |
| Annihilator ranged, ST build | 345,577 | `anr-st` |
| Void-Scarred ranged, ST build | 314,415 | `vsr-st` |
| Annihilator melee, ST build | 306,044 | `anm-st` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.
`vsr-dung`, `anr-dung`, and `anm-dung` currently use their identity's `-aoe` hash.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/2FGz1VQJVhQSaHZzb6DcyQ) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/oP4JjBq9EGTrVX38X3KwYy) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/5G9y1gNLy3DPGWP61Fkpga) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/7W75zfYXWqxWpsy1rWCG2M) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/kShM9EUZ3Q2vrBqgKi6HgN) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/u4mij7VH17v3bkS81gekWe) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/crHbmYyHfAcqBSfZiGWmDU) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/6WnCMNsQpWGdbfgmRyFtCg) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/m996EVotXuUTCs3fhtRxm3) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
