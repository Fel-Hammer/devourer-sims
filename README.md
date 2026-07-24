SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05. Group reports carry every build, including the
dungeon-route (`-dung`) loadouts.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/unjDcqWzakpH5GkZgfPsoW))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 254,655 | `vsm-st` |
| Void-Scarred ranged | 230,759 | `vsr-st` |
| Annihilator ranged | 219,690 | `anr-st` |
| Annihilator melee | 202,024 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/jqCTLNB7fvTvMo2ZhsH1Qk), [60s no lust](https://mimiron.raidbots.com/simbot/report/dU61xQPa8d8odeHrhsZApN))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 694,596 | 745,826 | `vsm-aoe` |
| Annihilator ranged | 651,735 | 683,636 | `anr-aoe` |
| Void-Scarred ranged | 603,568 | 615,421 | `vsr-aoe` |
| Annihilator melee | 582,085 | 608,211 | `anm-aoe` |

## Dungeon route — Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/nMvPTYxNba9wwX9JMHDidB))

`temple-of-sethraliss-route.simc` is a full M+ route reconstructed from 12.1 PTR logs: pull
composition, chaining, travel times, and per-mob health from a 21-run consensus (+10 to +20 keys),
health scaled to a single actor's share of group damage. Mixed single-target, cleave, burst AoE,
and priority targets over a ~15 minute route. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has a dungeon-route loadout (`-dung`). Void-Scarred melee's was found by racing
every legal build within six talent changes of the AoE champion over the full route — its soul
economy shifts toward the single-target core. The other three currently use their AoE talents;
their route races are queued.

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 451,754 | `vsm-dung` |
| Annihilator ranged | 421,810 | `anr-dung` |
| Void-Scarred ranged | 415,813 | `vsr-dung` |
| Annihilator melee | 386,050 | `anm-dung` |
| Void-Scarred melee, ST build | 363,661 | `vsm-st` |
| Annihilator ranged, ST build | 333,664 | `anr-st` |
| Void-Scarred ranged, ST build | 304,380 | `vsr-st` |
| Annihilator melee, ST build | 296,398 | `anm-st` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.
`vsr-dung`, `anr-dung`, and `anm-dung` are their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/2AhYbj2YfwvLofLG9M2s9H) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/un74DDJ8EKzA7J3hZReVnK) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/oJGWpy2mkY1qeXkcaC3Gs8) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/qqAdGu2UfAYp71MH5Lk99t) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/2oLpdBGo8QNSt8CNNocGXH) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/oeFN7ecKgC5beBFwYx92sq) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/bLjNNaq2SXo3uWQuCoG6nc) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/k9LwSqJ1ye97FHWbPtAgT9) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/a8vU9JVroQX73H6GfKwf5b) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
