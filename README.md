# devourer-sims

SimulationCraft profile and action list for the Devourer Demon Hunter (Int/Void DH), Midnight patch 12.1.

`devourer.simc` is the complete profile: character, highest-legal season-2 gear, talents, and the maintained action list. The file sets `ptr=1` to select the 12.1 data set, so run it against a SimC build that carries Midnight 12.1 data, or paste it into Raidbots Advanced with the PTR toggle on.

## Running it

```
simc devourer.simc
```

The profile defaults to single target, 300s, `target_error=0.05`. Override the fight parameters on the command line for the benchmark scenarios below.

## Proposing an optimization

Optimizations are welcome by pull request. Any PR that changes the profile must include sim results showing the change is neutral or a gain in all three scenarios below. No scenario may lose DPS beyond noise.

| Scenario | Targets | Fight length | Bloodlust |
|---|---|---|---|
| Single target | 1 | 500s | yes |
| AoE burst | 5 | 60s | no |
| AoE sustained | 5 | 300s | yes |

Run each with:

```
simc devourer.simc desired_targets=1 max_time=500 override.bloodlust=1
simc devourer.simc desired_targets=5 max_time=60  override.bloodlust=0
simc devourer.simc desired_targets=5 max_time=300 override.bloodlust=1
```

Sim the current profile and your modified copy separately at the same settings, then report both DPS values and the error % for each scenario. The profile already sets `target_error=0.05` so the deltas are meaningful; keep it there or lower for the comparison. A change is acceptable when every scenario is within error of, or ahead of, the current profile.
