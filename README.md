SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR. `devourer.simc` has the gear and the
action list. The list handles all four ways to play the spec and routes off your talents, so just
swap `talents=` to one of the hashes below.

All sims run at target_error 0.05 on the gear in `devourer.simc`.

## Single target (300s, lust) — [report](https://mimiron.raidbots.com/simbot/report/w5R8aGY6DNtypnPM8CK4aQ)

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 222,625 | `vsm-st` |
| Void-Scarred ranged | 200,059 | `vsr-st` |
| Annihilator ranged | 192,092 | `anr-st` |
| Annihilator melee | 166,487 | `anm-st` |

## 5 targets — [300s lust](https://mimiron.raidbots.com/simbot/report/cehQWCKmkHzSXyRtmpeZuH) · [60s no lust](https://mimiron.raidbots.com/simbot/report/3qfcEW26cBhVsqD9MgCaSt)

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 591,617 | 643,735 | `vsm-aoe` |
| Annihilator ranged | 534,938 | 566,858 | `anr-aoe` |
| Void-Scarred ranged | 512,972 | 534,586 | `vsr-aoe` |
| Annihilator melee | 482,980 | 509,852 | `anm-aoe` |

## Hashes

| Key | Hash |
|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNDjNttAgAGgHgZmZbmZa2mZbmZMzMA` |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZmZmFzYsJAQAAmZmZmtZmpZbmtZmZAD` |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZGzsYGjFBzMzMbtNzMDgZmBgAzMDGGA` |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZmZmZGzsYGjFttxMzMzWbzMzAYMDABmxgxMA` |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZYsIYmZmZrtZmZGgZmBgAzMMMGA` |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZmZmZYmlZYsIYmZmZrtZmZGgxMAEYmZMmxA` |

## The Hunt and Meta

The Void-Scarred melee list uses Vengeful Retreat right before The Hunt so Metamorphosis lands while
you're mid-leap. This works in game (SimC PR #11569), but stock SimC and Raidbots don't model the
leap yet, so the VS melee single target number above reads a little low.

## Contributing

PRs welcome if you beat one of these numbers with the same kind of build (melee builds keep The
Hunt, ranged builds skip it). Include the hash and a Raidbots report at target_error 0.05.
