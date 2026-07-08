# devourer-sims

Current SimulationCraft profile for the Devourer Demon Hunter, Midnight 12.1. `devourer.simc` has the gear, talents, and action list.

## High-water marks

Best DPS we have for each fight, run on Raidbots (PTR). Beat one and it's the new mark.

| Fight | DPS | Loadout | Sim |
|---|---|---|---|
| 1 target, 300s, lust | 202,103 | single-target | https://mimiron.raidbots.com/simbot/report/tAmwRbvAkNWUGN9cto5vxC |
| 5 target, 60s, no lust | 579,012 | AoE | https://mimiron.raidbots.com/simbot/report/kVWChtcJAj7pNxfZNMQ7UX |
| 5 target, 300s, lust | 520,885 | AoE | https://mimiron.raidbots.com/simbot/report/kAgwL4PhJDYhUDxtAyBbrU |

`devourer.simc` ships the single-target talents. For the AoE marks, swap the `talents=` line for:

```
talents=CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzMjNttAgAGAMzMbzMTz2MbzMDzMA
```

## Contributing

Open a PR that beats a mark. Most gains come from a different talent loadout, not the action list.

Include:
- The talents hash you ran.
- DPS for all three fights, current vs yours, at target_error 0.05.
