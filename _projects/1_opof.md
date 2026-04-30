---
layout: page
title: OpOF / BackTrac
description: Bubble origin of ring-current ions during dipolarization (manuscript in preparation)
img: assets/img/12.jpg
importance: 1
category: completed
github: https://github.com/YiwenZhu77/backtrac
---

**OpOF** (Open Field-line Outflow) is the central thread of my dissertation: tracing where the ring-current ion population that builds up during geomagnetic storms actually comes from. I combine global MHD simulations (MAGE), the Rice Convection Model (RCM), and the CHIMP test-particle code in a coupled pipeline, then run backward integrations of the relativistic guiding-center equations under conservation of the first adiabatic invariant.

### Approach
- δ$S$-based bubble identification (Sorathia 2021), validated against the conventional Δ$B_z$&gt;5 threshold &mdash; the two diagnostics show essentially zero overlap on weak-storm events; δ$S$ is the more physical choice.
- Phase-stratified analysis (P1 / P2 / P3) with sustained-OCb classification &mdash; cusp-start, plasma-sheet entry, and ring-current capture.
- Birn energy decomposition over the trajectory: betatron + Fermi + pressure-driven (PVG) channels, with fixed μ$_0$ and 5-second `vcentri` averaging.
- Phase-space sampling at scale: 912k-particle pilot batch, 1M-particle production batches across 9M total particles, with Poisson-noise budgeting at the 1% level.

### Headline result
For a representative sawtooth event, the **PVG channel dominates** the ring-current energization budget. Of the energetic ions reaching the inner magnetosphere, **~30%** are traceable to coherent dipolarization bubbles in our simulation, vs. ~16% in the comparison run from Sina&nbsp;et&nbsp;al. The bubble effect on energization is highly significant ($K_\mathrm{landing}$ 16.3 vs 9.6&nbsp;keV, $p&lt;10^{-3}$), while the landing **location** is not significantly different &mdash; bubbles change *what energy* an ion reaches the ring current with, not *where* it ends up.

### Code
[github.com/YiwenZhu77/backtrac](https://github.com/YiwenZhu77/backtrac) &middot; [github.com/YiwenZhu77/rcm-backtrac](https://github.com/YiwenZhu77/rcm-backtrac)
