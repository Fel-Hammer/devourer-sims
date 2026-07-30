SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/cDVDULFgVrePhHMoMbJ68u))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 256,572 | `vsm-st` |
| Void-Scarred ranged | 232,769 | `vsr-st` |
| Annihilator ranged | 220,206 | `anr-st` |
| Annihilator melee | 201,708 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/umtzQbnpet2cvJLn6ByDmo), [60s no lust](https://mimiron.raidbots.com/simbot/report/2ES3BeH4QtqYSZCh6hi4Yz))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 705,537 | 754,773 | `vsm-aoe` |
| Annihilator ranged | 656,391 | 688,748 | `anr-aoe` |
| Void-Scarred ranged | 607,734 | 621,791 | `vsr-aoe` |
| Annihilator melee | 581,912 | 609,734 | `anm-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/6hp9phc5NRcntd4QVKUjSb))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 458,922 | `vsm-dung` |
| Annihilator ranged | 428,136 | `anr-dung` |
| Void-Scarred ranged | 422,778 | `vsr-dung` |
| Annihilator melee | 388,226 | `anm-dung` |
| Void-Scarred melee, ST build | 379,071 | `vsm-st` |
| Annihilator ranged, ST build | 347,857 | `anr-st` |
| Void-Scarred ranged, ST build | 315,715 | `vsr-st` |
| Annihilator melee, ST build | 307,763 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/guJjKBuQLuRWEhCAwhkE5W) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/b89ve7VnjykngdJ1LKf2ZX) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/5iLiCEyYHy9jMYRTpvGzJk) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/esTQWhSZNFzEVDCxmDzjhL) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/9HDV7L7CksBtX2nLEC3amg) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/uQyk8MjWwpnJvurUrptk44) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/vr2jcE9efqZxZZmHpK4w1E) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/arKnkohNVavy32rG8Wer9C) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/2udYfS5NxMALERy2fFsz98) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
