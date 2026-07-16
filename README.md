SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/kgnu2PHn56H9j5FdAkgz2k))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 258,803 | `vsm-st` |
| Void-Scarred ranged | 235,604 | `vsr-st` |
| Annihilator ranged | 226,456 | `anr-st` |
| Annihilator melee | 199,486 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/iihUWuRYnA54sFgjMfkwzd), [60s no lust](https://mimiron.raidbots.com/simbot/report/6sBPNMac7ewzAWhKAGLJFK))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 702,070 | 739,317 | `vsm-aoe` |
| Annihilator ranged | 658,581 | 682,101 | `anr-aoe` |
| Void-Scarred ranged | 607,341 | 614,072 | `vsr-aoe` |
| Annihilator melee | 591,271 | 613,209 | `anm-aoe` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/nNFppLAPw4BxZiywkPXKZG) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzMjNttAgAGAMzMbzMTz2MbzMDzMA` | [report](https://mimiron.raidbots.com/simbot/report/iuhVCBRPcNCpP1tYp12yAr) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/8eKQqL9D9unYz1UzGfKB4f) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/qj4PPNtpHPKAhVSbpgaqn7) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/r3Yhs6hrESmkLPSUVhRaXK) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/5oVhGxKat8j37T6XazqYdT) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/nxSVLLivZSf8VMmprBAdu4) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/bHRAnTDDbLBzpujLkBzHEs) |

## Temporary note:

The Void-Scarred melee list uses Vengeful Retreat right before The Hunt so Metamorphosis lands while
you're mid-leap. This works in game (SimC PR #11569), but stock SimC and Raidbots don't model the
leap yet, so the Void-Scarred melee single target number above reads a little low.

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
