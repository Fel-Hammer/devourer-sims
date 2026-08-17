SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

`devourer.simc` carries two gear sets. Void-Scarred is the active one and Annihilator sits commented
out below it. Each archetype wears its own set. Everything here is simmed at target_error 0.05, and
the group reports include every build, dungeon-route (`-dung`) loadouts included.

All numbers include the August 14 Devourer balance changes, applied to the sim inputs as manual
data adjustments until they land in SimC's own data.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/6HESWQa1k61EWDphYDK4Yp))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 266,219 | `vsm-st` |
| Void-Scarred melee, cleave build | 252,628 | `vsm-cleave` |
| Void-Scarred ranged | 237,009 | `vsr-st` |
| Annihilator ranged | 235,471 | `anr-st` |
| Annihilator melee | 215,129 | `anm-st` |

## 3 targets (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/fL6ZM45yiJqjz2QxJjNoi2))

`vsm-cleave` is a two-to-three-target compromise: the melee AoE chassis keeping Second Helping
with single-target points on top.

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 502,475 | `vsm-aoe` |
| Void-Scarred melee, cleave build | 497,730 | `vsm-cleave` |
| Annihilator ranged | 487,051 | `anr-aoe` |
| Void-Scarred ranged | 430,748 | `vsr-aoe` |
| Void-Scarred melee, ST build | 424,280 | `vsm-st` |
| Annihilator melee | 420,982 | `anm-aoe` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/fT94LeDyondRDjxVDQmmuj), [60s no lust](https://mimiron.raidbots.com/simbot/report/xvkPZsHe3pJCVm7i62AGaK))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 680,788 | 737,431 | `vsm-aoe` |
| Annihilator ranged | 673,788 | 702,559 | `anr-aoe` |
| Void-Scarred melee, cleave build | 665,684 | 726,538 | `vsm-cleave` |
| Annihilator melee | 587,347 | 613,985 | `anm-aoe` |
| Void-Scarred ranged | 577,307 | 583,594 | `vsr-aoe` |

## Dungeon route: Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/iriZXbtZKqsr5pp9Bbczyv))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

Each archetype has its own route loadout (`-dung`).

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 450,154 | `vsm-dung` |
| Void-Scarred melee, cleave build | 445,235 | `vsm-cleave` |
| Annihilator ranged | 444,527 | `anr-dung` |
| Void-Scarred ranged | 414,764 | `vsr-dung` |
| Annihilator melee | 395,744 | `anm-dung` |
| Void-Scarred melee, ST build | 387,051 | `vsm-st` |
| Annihilator ranged, ST build | 372,316 | `anr-st` |
| Void-Scarred ranged, ST build | 360,707 | `vsr-st` |
| Annihilator melee, ST build | 336,336 | `anm-st` |

## Hashes

Each row links a report for that build on its own, so you can check its gear and talents.
`vsr-dung`, `anr-dung` and `anm-dung` reuse their identity's `-aoe` hash for now.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMmZmZYmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/f9khKQhVbc5MvRLZrgaCVe) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMzMwMAAAAAAALzYMYGAAAAAAAAmxMMzMzMzYmZYmtZGjNZBABMADzMz2Mz0sNz2MzwMDA` | [report](https://mimiron.raidbots.com/simbot/report/hTH5mW7UivvCPMVXaJALSk) |
| vsm-cleave | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAY5BGz2gZAAAAAAAAYGzw8AzMzMzMzMjZ2mZM202CACYAMmZmtZmpZbmlZmxYGA` | [report](https://mimiron.raidbots.com/simbot/report/ccoZnP6wiso2oFhDRgPYtg) |
| vsm-dung | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZYmtZGjNZBABMAzYmZ2mZmmtZ2mZGjZA` | [report](https://mimiron.raidbots.com/simbot/report/2N2kFwviJnhvuoz3z4nqza) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGMMA` | [report](https://mimiron.raidbots.com/simbot/report/wyj9e1ZffVJhPoEpmE1Vdn) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/xmRK2ZtLtXoCybpDbQZLBB) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZmZmFzYsolFmZmZ2abmZGAzMDABMGMMA` | [report](https://mimiron.raidbots.com/simbot/report/nXhd1oyp9A8NRRFCbjk1AJ) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMzYmFzYsolFmZmZ2abmZGAjZAIgxgxMA` | [report](https://mimiron.raidbots.com/simbot/report/8iTMnsq928XPQvcc79486n) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMPwMzMjZmZMzsMzYsolFmZmZ2abmZmBwMDABmZYY8BA` | [report](https://mimiron.raidbots.com/simbot/report/26Ks9dou5py2u5JGWjYsmS) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/1JvNq1rraTNBv8YoxKtTPP) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
