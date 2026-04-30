---
layout: page
title: RCM + CHIMP coupling
description: Test-particle modeling of plasma-sheet flow channels with the Rice Convection Model
img: assets/img/8.jpg
importance: 3
category: research
---

A combined modeling framework that couples the **Rice Convection Model (RCM)** for inner-magnetosphere plasma transport with the **CHIMP** test-particle code, used to study how individual ion species are accelerated and transported during substorm dipolarization events.

### What I work on
- η-tracking and λ-channel formulation of bounce-averaged transport in the RCM.
- Validation against MHD via cross-comparison of independent backtracking codes (cos θ ≈ 0.98 between methods).
- Development of a `V_eff` integrator that handles inductive E-fields and signed `bVol` consistently across the entire ring-current loss cone.
- Phase-space sampling at scale: 1M-particle batches across 9M total ions, with Poisson-noise budgeting at the 1% level.

### Tooling
The work runs on **NCAR's Derecho** HPC system (PBS / MPI), with all I/O in HDF5 (h5part) and analysis in Python (polars, JAX-on-CPU, matplotlib). I maintain a custom persistent REPL engine for interactive multi-million-particle phase-space analysis without paying Jupyter restart costs.
