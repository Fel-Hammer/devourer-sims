SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/8Gv6dz2VuEDVGKXFiJ1MZT))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 254,645 | `vsm-st` |
| Void-Scarred ranged | 230,811 | `vsr-st` |
| Annihilator ranged | 219,617 | `anr-st` |
| Annihilator melee | 202,015 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/a8ERyMmHK9aAyUgWz82atz), [60s no lust](https://mimiron.raidbots.com/simbot/report/xjRiNFQjRtX5watt8Lnsjo))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 688,015 | 740,161 | `vsm-aoe` |
| Annihilator ranged | 651,385 | 683,691 | `anr-aoe` |
| Void-Scarred ranged | 603,820 | 615,546 | `vsr-aoe` |
| Annihilator melee | 581,871 | 608,354 | `anm-aoe` |

## Dungeon route — Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/2WW8A7eCSV4rPJav8cK1aX))

`temple-of-sethraliss-route.simc` is a full M+ route reconstructed from 12.1 PTR logs: pull
composition, chaining, travel times, and per-mob health from a 21-run consensus (+10 to +20 keys),
health scaled to a single actor's share of group damage. Mixed single-target, cleave, burst AoE,
and priority targets over a ~15 minute route. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee, AoE build | 441,090 | `vsm-aoe` |
| Annihilator ranged, AoE build | 421,913 | `anr-aoe` |
| Void-Scarred ranged, AoE build | 415,680 | `vsr-aoe` |
| Annihilator melee, AoE build | 386,220 | `anm-aoe` |
| Void-Scarred melee, ST build | 363,748 | `vsm-st` |
| Annihilator ranged, ST build | 333,780 | `anr-st` |
| Void-Scarred ranged, ST build | 304,170 | `vsr-st` |
| Annihilator melee, ST build | 296,387 | `anm-st` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/eA5hMFxgTwmo8aFntuWa64) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNjZsptFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/3CxRBXcJSAW3d6KhuWPd42) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/mNgQRknijnCthX26JmXYGX) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/aLxfDjVBin8AG1Q9817adJ) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/o6yX2hZ1YyEETL671vLbif) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/uFSWtuEqCuC7oha7MJVeoc) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/qZvfvmrE67czYAKHStSjM8) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/1C57f9RmaQYqjTe24oUDBX) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
