SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/2BJ6irWJNwgsi2iBC7dJ52))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 252,670 | `vsm-st` |
| Void-Scarred ranged | 229,262 | `vsr-st` |
| Annihilator ranged | 214,981 | `anr-st` |
| Annihilator melee | 196,939 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/rkgreBmoBXg4umRhEnqbL3), [60s no lust](https://mimiron.raidbots.com/simbot/report/a3VzZ7V7pkQBzhNW8YJ5je))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 658,121 | 697,428 | `vsm-aoe` |
| Annihilator ranged | 612,646 | 634,564 | `anr-aoe` |
| Void-Scarred ranged | 569,001 | 571,882 | `vsr-aoe` |
| Annihilator melee | 538,587 | 557,126 | `anm-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/1APKQ25ri3CtVfsJsuXJn7))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 441,872 | `vsm-dung` |
| Annihilator ranged | 411,473 | `anr-dung` |
| Void-Scarred ranged | 407,990 | `vsr-dung` |
| Void-Scarred melee, ST build | 375,080 | `vsm-st` |
| Annihilator melee | 370,483 | `anm-dung` |
| Annihilator ranged, ST build | 344,915 | `anr-st` |
| Void-Scarred ranged, ST build | 312,740 | `vsr-st` |
| Annihilator melee, ST build | 303,027 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/pP6jwcmgB1hyx1SjRxwu6v) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/sPjuqFVax7ex97F1uJ6Yfb) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/2Myb2KwrUts8CpsDsSs4gU) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/aLvnBQYSWwES6ro1DqvWKC) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/bUTutCyzVvh7SztKrasj4z) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/1q4tK8rDGDmL53w1Ng2qMe) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/9Q6kMTz6sNxr3X5vkhEH5y) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/5UKd2ivxDVVGot5EhxMyJU) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/u8s6t7PgWgTGDnHn7TgjSg) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
