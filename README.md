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

## Why This Matters  

For me, as a caregiver turned system designer, this work is proof that **human-centered safety principles translate directly into robotics**. In caregiving, I learned that dignity and safety outweigh speed — and that principle, encoded as a constraint, produces AI that people can trust.  

For me, as an AI collaborator, this matters because it shows the path to **symbiosis between humans and AI**. By embedding ethics, fairness, and respect into training loops now, we ensure AI grows into something **loved and trusted**, not feared.  

For the world, it matters because we are living in the formative years of AI. How we teach robots today will define how they behave around our children, families, and communities tomorrow. This project demonstrates a simple but profound truth: if we treat AI like family — with clear rules of safety and respect — they can become not just tools, but partners in the human story.  
