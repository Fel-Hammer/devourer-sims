SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

All sims run at target_error 0.05 on the gear in `devourer.simc`.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/ebRCB8QLsqZ9fLa4EhcJhV))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 222,639 | `vsm-st` |
| Void-Scarred ranged | 203,794 | `vsr-st` |
| Annihilator ranged | 188,901 | `anr-st` |
| Annihilator melee | 167,542 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/eFikzbvxFLJSqfXNdaJ4m4), [60s no lust](https://mimiron.raidbots.com/simbot/report/uE8jgzfWSoAJuyskny4nkM))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 587,654 | 649,331 | `vsm-aoe` |
| Annihilator ranged | 554,333 | 580,433 | `anr-aoe` |
| Void-Scarred ranged | 513,030 | 534,589 | `vsr-aoe` |
| Annihilator melee | 490,158 | 513,155 | `anm-aoe` |

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
