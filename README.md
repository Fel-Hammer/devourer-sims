SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

All sims run at target_error 0.05 on the gear in `devourer.simc`.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/8qgPvSM8AUKth4dEzQkLYJ))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 236,969 | `vsm-st` |
| Void-Scarred ranged | 219,694 | `vsr-st` |
| Annihilator ranged | 205,230 | `anr-st` |
| Annihilator melee | 181,628 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/jmAwDBhKg5KZo7chH93i2Z), [60s no lust](https://mimiron.raidbots.com/simbot/report/eK8G8K5kWJvsZobfPFRdz7))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 620,824 | 666,118 | `vsm-aoe` |
| Annihilator ranged | 594,218 | 611,729 | `anr-aoe` |
| Void-Scarred ranged | 554,520 | 568,665 | `vsr-aoe` |
| Annihilator melee | 535,644 | 552,615 | `anm-aoe` |

## Hashes

| Key | Hash |
|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzMjNttAgAGAMzMbzMTz2MbzMDzMA` |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` |

## Temporary note 7/9/26:

The Void-Scarred melee list uses Vengeful Retreat right before The Hunt so Metamorphosis lands while
you're mid-leap. This works in game (SimC PR #11569), but stock SimC and Raidbots don't model the
leap yet, so the VS melee single target number above reads a little low.

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
