# devourer-sims

SimulationCraft profile and action list for the Devourer Demon Hunter (Int/Void DH), Midnight patch 12.1.

`devourer.simc` is the complete profile: character, highest-legal season-2 gear, talents, and the maintained action list. The file sets `ptr=1` to select the 12.1 data set, so run it against a SimC build that carries Midnight 12.1 data, or paste it into Raidbots Advanced with the PTR toggle on.

The action list is scenario-aware: it branches on hero tree and key talents, so you can swap the `talents=` line to a different loadout and the correct rotation is selected automatically. No single loadout wins every scenario, which is why each benchmark below has its own build.

## Current high-water marks

The best result we have for each benchmark, verified on Raidbots (PTR). Beat one of these and it becomes the new mark.

| Scenario | DPS | Loadout | Raidbots |
|---|---|---|---|
| 1 target, 300s, bloodlust | 202,103 | single target (shipped) | https://mimiron.raidbots.com/simbot/report/tAmwRbvAkNWUGN9cto5vxC |
| 5 target, 60s, no bloodlust | 579,012 | AoE | https://mimiron.raidbots.com/simbot/report/kVWChtcJAj7pNxfZNMQ7UX |
| 5 target, 300s, bloodlust | 520,885 | AoE | https://mimiron.raidbots.com/simbot/report/kAgwL4PhJDYhUDxtAyBbrU |

The single-target loadout is the `talents=` line already in `devourer.simc`. The AoE loadout (both 5-target marks) swaps that line for:

```
talents=CgcBAAAAAAAAAAAAAAAAAAAAAAAWMmZmZmZmBmBAAAAAAYZGjBzAAAAAAAAwMmh5BmZmZmZmZGzsNzMjNttAgAGAMzMbzMTz2MbzMDzMA
```

## Running it

```
simc devourer.simc desired_targets=1 max_time=300 override.bloodlust=1
simc devourer.simc desired_targets=5 max_time=60  override.bloodlust=0
simc devourer.simc desired_targets=5 max_time=300 override.bloodlust=1
```

The profile defaults to `target_error=0.05`, the fidelity these marks were set at.

## Proposing an optimization

Optimizations are welcome by pull request. The goal is to raise a high-water mark, and because no single loadout wins every scenario, most gains come from a different talent loadout rather than an action-list edit. Include the exact build you tested.

Every PR must report, for all three scenarios, the current mark and your result (DPS and error %), each simmed separately at the same settings. State the `talents=` hash you used and any gear or action-list changes. A contribution is accepted when it sets a new high-water mark in at least one scenario. Keep `target_error=0.05` (or lower) so the deltas are real.
