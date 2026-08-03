SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/jg3ptSDPp86fs9prK3muyD))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 252,703 | `vsm-st` |
| Void-Scarred ranged | 225,480 | `vsr-st` |
| Annihilator ranged | 214,975 | `anr-st` |
| Annihilator melee | 196,799 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/2HUjC73iUaiRhn7oZsRqJP), [60s no lust](https://mimiron.raidbots.com/simbot/report/aSUAJmgWyxjbdJdCcVe4XH))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 661,334 | 702,681 | `vsm-aoe` |
| Annihilator ranged | 612,585 | 634,541 | `anr-aoe` |
| Void-Scarred ranged | 557,629 | 559,018 | `vsr-aoe` |
| Annihilator melee | 538,454 | 556,920 | `anm-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/gW7HFpPbLR5UFNRw7CjfQE))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 441,842 | `vsm-dung` |
| Annihilator ranged | 411,517 | `anr-dung` |
| Void-Scarred ranged | 403,107 | `vsr-dung` |
| Void-Scarred melee, ST build | 373,728 | `vsm-st` |
| Annihilator melee | 370,338 | `anm-dung` |
| Annihilator ranged, ST build | 344,666 | `anr-st` |
| Void-Scarred ranged, ST build | 330,616 | `vsr-st` |
| Annihilator melee, ST build | 302,915 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/kqRxG9wf5QYEQogh8sqcug) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/jnSvXNkjYt6JQNvX6k4AYV) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/kcLNcsQdJHBidms8WZHiXM) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGMMA` | [report](https://mimiron.raidbots.com/simbot/report/coy67X1NEFEU6q2qHZM6UN) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/tjxYt9xmWWhdtn79wTweLv) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/uwCsaDq717JHf9x4bC2MsF) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/kcekoxQy4QAzFiaMAJyQSN) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/osnBUkJKM7r9ZR4cg2JD7C) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/9BcM2QuWdM7cwa5xj9X2tv) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
