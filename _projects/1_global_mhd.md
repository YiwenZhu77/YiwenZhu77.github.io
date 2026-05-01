---
layout: page
title: Global MHD Simulation of Earth's Magnetosphere
description: Coupled MHD + RCM simulations with the MAGE model — bubble origin of ring-current ions
img: assets/img/area_mhd_simulation.jpg
importance: 1
category: research
---

How does Earth's magnetosphere store and release energy during geomagnetic storms? My dissertation work uses the **MAGE** (Multiscale Atmosphere–Geospace Environment) coupled MHD + RCM model on NCAR Derecho to attack this question at the kinetic level.

The flagship project, **OpOF** (Open Field-line Outflow), backward-traces ring-current ion guiding centers through MAGE's time-dependent fields, conserving the first adiabatic invariant μ. By identifying coherent dipolarization bubbles via the δ$S$ diagnostic (Sorathia 2021) and decomposing the energization budget into betatron, Fermi, and pressure-driven (PVG) channels, we show that the **PVG channel dominates** ring-current build-up, with **~30 %** of energetic ions traceable to bubble injections (vs. ~16 % in earlier comparison runs). The bubble effect on energization is highly significant ($K_\mathrm{landing}$ 16.3 vs 9.6&nbsp;keV, $p&lt;10^{-3}$); the *landing location* is not — bubbles change the energy an ion arrives with, not where it ends up.

Code: [github.com/YiwenZhu77/backtrac](https://github.com/YiwenZhu77/backtrac) &middot; [github.com/YiwenZhu77/rcm-backtrac](https://github.com/YiwenZhu77/rcm-backtrac).
