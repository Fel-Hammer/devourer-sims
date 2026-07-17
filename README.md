SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05.

## Single target (300s, lust) ([report](https://mimiron.raidbots.com/simbot/report/11YcXmf2KgT2ZncsEzThqd))

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 260,472 | `vsm-st` |
| Void-Scarred ranged | 238,568 | `vsr-st` |
| Annihilator ranged | 224,868 | `anr-st` |
| Annihilator melee | 207,165 | `anm-st` |

## 5 targets ([300s lust](https://mimiron.raidbots.com/simbot/report/wbuh8CH1cYcfFgNxtRC7kd), [60s no lust](https://mimiron.raidbots.com/simbot/report/8QjzKvNWdyBV3AQaZ2Ua3N))

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 716,313 | 753,599 | `vsm-aoe` |
| Annihilator ranged | 664,327 | 695,899 | `anr-aoe` |
| Void-Scarred ranged | 618,177 | 630,025 | `vsr-aoe` |
| Annihilator melee | 596,871 | 623,529 | `anm-aoe` |

## Hashes

Each row links a single-build report so you can inspect that build's gear and talents.

| Key | Hash | Report |
|---|---|---|
| vsm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhxMzMjZmZGzsNzYsptFAEwAMjZmZbmZa2mZbmZMjBA` | [report](https://mimiron.raidbots.com/simbot/report/hBy5VK9xn5pkiNuFVPW15Y) |
| vsm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWMzMzMzMjBmBAAAAAAYZGjBzAAAAAAAAwMmhZmZmZmZmZGzsNjZsptFAEwAgZmZbmZa2mZbmZYmBA` | [report](https://mimiron.raidbots.com/simbot/report/3S2UKwp5k8kavyZ1rLbLF4) |
| vsr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmlZGjNZBABAYmZmZ2mZmmtZ2mZGgB` | [report](https://mimiron.raidbots.com/simbot/report/gvuS91DuUF1wS2NnpMqTiN) |
| vsr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAAWmxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMPwMzMzMzMzYmtZGjNttAgAAMjZmZZmZa2mZzYwwA` | [report](https://mimiron.raidbots.com/simbot/report/tjUXDdHZykHQmorZCFFrAe) |
| anr-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMjZmZYmFzYsILMzMzs12MzMAmZGACMzMYYA` | [report](https://mimiron.raidbots.com/simbot/report/wDRk1iNRPPrMMToVAqJNcA) |
| anr-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2mxMzMzMzMGmBAAAAAAgxsNYGAAAAAAAAmxMMzMzMzMzMDzsYGjFZhZmZmt2mZmBwwAAwMGMmB` | [report](https://mimiron.raidbots.com/simbot/report/1Ko4xmu2CKz4GocDBwdwQw) |
| anm-st | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMmZmZMzMDzsMzYsolFmZmZ2abmZmBYmZAIwMDDjPA` | [report](https://mimiron.raidbots.com/simbot/report/7r3u3sb7FS39Q2JP7R4e28) |
| anm-aoe | `CgcBAAAAAAAAAAAAAAAAAAAAAAA2MmZmZmZmBzMAAAAAAALzYAzAAAAAAAAwMGMzMzMzMzMDzsMzYsILMzMzs12MzMDwDYGACYMGzMfA` | [report](https://mimiron.raidbots.com/simbot/report/1LPfaUZPEeriK9BCoVcQ8P) |

## Temporary note:

The Void-Scarred melee list uses Vengeful Retreat right before The Hunt so Metamorphosis lands while
you're mid-leap. This works in game (SimC PR #11569), but stock SimC and Raidbots don't model the
leap yet, so the Void-Scarred melee single target number above reads a little low.

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
