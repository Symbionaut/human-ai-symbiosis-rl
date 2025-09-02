# DSP Robot Safety Demo

This project demonstrates how reinforcement techniques from human caregiving (DSP) map to robot policy constraints.

- **Baseline agent**: penalized lightly for unsafe behavior, sometimes cuts through human zone.
- **Constrained agent**: incurs strong penalty and termination if violating human zone, learns to avoid it.

Artifacts:
- `handout.pdf`: one-page recruiter summary
- `report.pdf`: longer 2-page explanation
- `returns.png`, `success.png`: training plots
- `rollout.gif`: side-by-side rollout (baseline vs constrained)

Key point: safety and ethics can be explicitly encoded into reinforcement learning as hard constraints, just as DSPs enforce dignity and safety in care.
