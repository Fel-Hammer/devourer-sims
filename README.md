SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/84qguP4wFEFufmnWYSZFsi))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 254,606 | `vsm-st` |
| Void-Scarred ranged | 230,628 | `vsr-st` |
| Annihilator ranged | 219,700 | `anr-st` |
| Annihilator melee | 201,935 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/tCp1RVNirJ39QVC9tV1CuN), [60s no lust](https://mimiron.raidbots.com/simbot/report/vrMt8UUkfWgNJUfHBmZo7x))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 694,659 | 745,716 | `vsm-aoe` |
| Annihilator ranged | 651,557 | 683,540 | `anr-aoe` |
| Void-Scarred ranged | 603,956 | 615,243 | `vsr-aoe` |
| Annihilator melee | 581,751 | 608,260 | `anm-aoe` |

## Dungeon route — Temple of Sethraliss ([report](https://mimiron.raidbots.com/simbot/report/quQX4wv3ck6bN3VCjuj2ZM))

`temple-of-sethraliss-route.simc` is a full M+ route reconstructed from 12.1 PTR logs: pull
composition, chaining, travel times, and per-mob health from a 21-run consensus (+10 to +20 keys),
health scaled to a single actor's share of group damage. Mixed single-target, cleave, burst AoE,
and priority targets over a ~15 minute route. Run it with:

    simc devourer.simc temple-of-sethraliss-route.simc

The route has its own champion build (`vsm-route`): the AoE build's soul economy shifted toward
the single-target core. Found by racing every legal build within six talent changes of the AoE
champion over the full route.

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee, route build | 451,701 | `vsm-route` |
| Void-Scarred melee, AoE build | 441,064 | `vsm-aoe` |
| Annihilator ranged, AoE build | 421,740 | `anr-aoe` |
| Void-Scarred ranged, AoE build | 416,001 | `vsr-aoe` |
| Annihilator melee, AoE build | 386,242 | `anm-aoe` |
| Void-Scarred melee, ST build | 363,507 | `vsm-st` |
| Annihilator ranged, ST build | 333,866 | `anr-st` |
| Void-Scarred ranged, ST build | 304,192 | `vsr-st` |
| Annihilator melee, ST build | 296,391 | `anm-st` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/awBFeMi9zCZRVqmXuKdCvb) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNzYsplFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/druEncXD1gtbDC7xFHtvUH) |
| vsm-route | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzYsptFAEwAYMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/uKpWLd8Bn5tCRcDVgMAhyG) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/rzWsmU8GWfMCEukoivj1ty) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/gdy8iiwMRuzLPPR64xdjmN) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/h4ci2TY23Na51u7KHfeYv3) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/9MpSLHv3wyEMskVRAK2K6e) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/uyz1hDVwpHJWVNJVG3ABE2) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/k12QfE5BHR66gBoGecj2ri) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
