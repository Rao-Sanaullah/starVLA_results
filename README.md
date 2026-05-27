# StarVLA — Robotis SG2 AI Worker Results

Simulation study of closed-loop VLA control for dual-arm humanoid manipulation using [StarVLA](https://github.com/starVLA/starVLA), deployed on the Robotis SG2 AI Worker in NVIDIA IsaacLab.

> Full results, videos, and methodology: **[yourname.github.io/starvla-results](https://yourname.github.io/starvla-results)**

## Key results

| Variant | Checkpoint | Success rate | Trials |
|---|---|---|---|
| State-free | 200k steps | **52%** | 50 |
| State-conditioned | 30k steps | 28% | 50 |

## Videos

Place video files in `videos/` folder:

```
videos/
├── state_free_demo.mp4
├── state_conditioned_demo.mp4
└── state_400k_unstable.mp4
```

## Links

- [Full results page](https://yourname.github.io/starvla-results)
- [Installation guide](https://rao-sanaullah.github.io/starVLA_setup/)
- [Official StarVLA repo](https://github.com/starVLA/starVLA)
- [Paper](#)

---
