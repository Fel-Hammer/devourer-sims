SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

All sims run at target_error 0.05 on the gear in `devourer.simc`.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/eqERA4Fgxz3FLj4aJdsrqY))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 250,641 | `vsm-st` |
| Void-Scarred ranged | 232,312 | `vsr-st` |
| Annihilator ranged | 217,365 | `anr-st` |
| Annihilator melee | 192,249 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/pmw8DKq7AeSuV5xtQRUFCa), [60s no lust](https://mimiron.raidbots.com/simbot/report/x7tSYHVgRWwCbDuDNiubTo))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 655,788 | 703,065 | `vsm-aoe` |
| Annihilator ranged | 629,430 | 646,536 | `anr-aoe` |
| Void-Scarred ranged | 585,782 | 600,196 | `vsr-aoe` |
| Annihilator melee | 567,178 | 584,488 | `anm-aoe` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/j2BiuQWGgQ2ns1cMDGFFBo) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzMjNttAgAGAMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/sizmAxH1RE2N8WZPFVv64J) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/czzn32aNmPs3R9QEqmDG3o) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/emoBjNh2fTKrddho4YaXew) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/vup6FDQNAbEcJrhghhKVea) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/akX6j5veb3zXhyUEBJK9LD) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/eTV5RrduPHZodjkrwPhBK5) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/w3DhEg8R4bPKP3kTxqjBzZ) |

## Temporary note 7/9/26:

The Void-Scarred melee list uses Vengeful Retreat right before The Hunt so Metamorphosis lands while
you're mid-leap. This works in game (SimC PR #11569), but stock SimC and Raidbots don't model the
leap yet, so the VS melee single target number above reads a little low.

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
