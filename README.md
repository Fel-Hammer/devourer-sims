SimC profile for Devourer Demon Hunter, Midnight 12.1 PTR.

Two gear sets in `devourer.simc` — Void-Scarred (default) and Annihilator (commented). Each archetype
wears its own set. All sims run at target_error 0.05.

## Single target (300s, lust)

| Build | DPS | Hash |
|---|---|---|
| Void-Scarred melee | 252,747 | `vsm-st` |
| Void-Scarred ranged | 230,157 | `vsr-st` |
| Annihilator ranged | 220,284 | `anr-st` |
| Annihilator melee | 202,097 | `anm-st` |

## 5 targets (300s lust, 60s no lust)

| Build | 300s | 60s | Hash |
|---|---|---|---|
| Void-Scarred melee | 698,022 | 861,509 | `vsm-aoe` |
| Annihilator ranged | 659,644 | 847,474 | `anr-aoe` |
| Void-Scarred ranged | 604,232 | 760,904 | `vsr-aoe` |
| Annihilator melee | 591,344 | 769,116 | `anm-aoe` |

Rows are ranked by the 300s column; at 60s Annihilator melee edges Void-Scarred ranged on this engine.

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

The marks above were simmed locally on SimC built from upstream midnight plus two pending PRs:
#11569 (Metamorphosis catches The Hunt mid-leap — the Void-Scarred melee list sets this up with
Vengeful Retreat right before The Hunt, and it works in game) and #11359 (soul fragments auto-pickup
in range). Stock SimC and Raidbots model neither yet, so Raidbots runs of this profile won't match
these numbers — single target reads a few percent higher without #11359, and Void-Scarred melee
reads low without #11569. Report links return once both land upstream.

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
