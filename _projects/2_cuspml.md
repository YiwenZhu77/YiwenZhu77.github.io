---
layout: page
title: cuspML
description: XGBoost prediction of the ionospheric cusp from 27 years of DMSP data (manuscript in late revision)
img: assets/img/3.jpg
importance: 2
category: completed
github: https://github.com/YiwenZhu77/cuspML
---

**cuspML** is a gradient-boosted-tree model that predicts the magnetic-latitude location of the **ionospheric cusp** from upstream solar-wind drivers, using **27 years of DMSP particle-precipitation observations** as ground truth.

### What it does
- Curates ~100k cusp-crossing events from DMSP F13&ndash;F18 SSJ data through an automated identification pipeline.
- Trains an XGBoost regressor on solar-wind clock angle, IMF magnitude, dynamic pressure, dipole tilt, and Dst.
- Validates against independent test years and against analytic cusp-latitude relations (Newell &amp; Meng, Burch).
- Quantifies the dipole-tilt effect on cusp location with a **tilt-stratified subsample** that controls for the natural tilt-distribution imbalance &mdash; a known source of overfitting in solar-wind&ndash;driven models.

### Why it matters
A fast, accurate cusp-latitude predictor enables real-time space-weather products (auroral-zone forecasting, satellite-drag input, communications-blackout warnings) without running expensive global MHD models for every solar-wind perturbation.

Code: [github.com/YiwenZhu77/cuspML](https://github.com/YiwenZhu77/cuspML)
