SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

All numbers include the August 14 Devourer balance changes, applied to the sim inputs as manual
data adjustments until they land in SimC's own data.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/e24qa6Jvyu4MGugJKkerEc))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 257,305 | `vsm-st` |
| Void-Scarred ranged | 226,387 | `vsr-st` |
| Annihilator ranged | 226,180 | `anr-st` |
| Annihilator melee | 206,966 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/oJS8SMJVVzc4oxD4QWqnZD), [60s no lust](https://mimiron.raidbots.com/simbot/report/9grgqY6KNTt5HH4AiDyJi2))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 662,729 | 718,301 | `vsm-aoe` |
| Annihilator ranged | 653,932 | 682,382 | `anr-aoe` |
| Annihilator melee | 568,260 | 594,603 | `anm-aoe` |
| Void-Scarred ranged | 552,158 | 556,885 | `vsr-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/q91NMvqoE5Ab6yrJkz2Z2p))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 442,159 | `vsm-dung` |
| Annihilator ranged | 431,543 | `anr-dung` |
| Void-Scarred ranged | 401,902 | `vsr-dung` |
| Annihilator melee | 386,679 | `anm-dung` |
| Void-Scarred melee, ST build | 386,285 | `vsm-st` |
| Annihilator ranged, ST build | 366,436 | `anr-st` |
| Void-Scarred ranged, ST build | 350,092 | `vsr-st` |
| Annihilator melee, ST build | 330,409 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZYmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/i4ng7iwsg5Bk5vfBC3zfb2) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMzMzMzYmZYmtZGjNZBABMADzMz2Mz0sNz2MzwMDA` | [report](https://mimiron.raidbots.com/simbot/report/rhzfvf48WQoLLuerFVYuvS) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZYmtZGjNZBABMAzYmZ2mZmmtZ2mZGjZA` | [report](https://mimiron.raidbots.com/simbot/report/qVKEFMYKAiphWtsdAJ1xhh) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGMMA` | [report](https://mimiron.raidbots.com/simbot/report/fm3o9h73N1WohY6mRfXte4) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/qGtFU8jkyGUnajUuVKBukK) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZmZmFzYsolFmZmZ2abmZGAzMDABMGMMA` | [report](https://mimiron.raidbots.com/simbot/report/53K42XoCxRyWC9CoquQtMp) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMzYmFzYsolFmZmZ2abmZGAjZAIgxgxMA` | [report](https://mimiron.raidbots.com/simbot/report/8iJpmaCVj25yibtLrJBQ2u) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZMzsMzYsolFmZmZ2abmZmBwMDABmZYY8BA` | [report](https://mimiron.raidbots.com/simbot/report/gvZiFdVAKb8SPJg5CnwYuo) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/kagg21nM5RpkfV1jSwTeje) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
