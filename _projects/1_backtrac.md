---
layout: page
title: BackTrac
description: Backward test-particle tracing in MAGE — bubble origin of ring-current ions
img: assets/img/12.jpg
importance: 1
category: research
github: https://github.com/YiwenZhu77/backtrac
---

**BackTrac** is a Python framework that backward-traces ring-current ion guiding-centers through the time-dependent fields of a coupled MHD + RCM (Rice Convection Model) simulation, in order to identify the **plasma-sheet origin of ring-current H+** during dipolarization events.

### What it does
- Reads time-series electromagnetic fields from MAGE (Multiscale Atmosphere–Geospace Environment) simulations.
- Integrates the relativistic guiding-center equations of motion **backward in time** under conservation of the first adiabatic invariant μ.
- Tags each backtraced trajectory with the bubble it originated from, using a dBz threshold and causal-chain analysis.
- Produces phase-space distributions, bubble-vs-non-bubble fractions, and energization decompositions (betatron + Fermi + drift work).

### Key result
Of the ring-current pressure increase observed during a typical sawtooth event, **~30%** of energetic ions are traceable to coherent dipolarization bubbles, vs. only **~16%** in the comparison run by Sina et al. The PVG (pressure-driven gradient drift) channel turns out to dominate the energization budget.

### Stack
Python, NumPy, h5py, multiprocessing for batched particle integration, h5part for trajectory I/O.

Code: [github.com/YiwenZhu77/backtrac](https://github.com/YiwenZhu77/backtrac)
