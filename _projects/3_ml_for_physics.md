---
layout: page
title: Machine Learning for Space Physics
description: cuspML and TEC-FNO — fast surrogates for ionospheric prediction
img: assets/img/area_ml_physics.jpg
importance: 3
category: research
---

Machine-learning surrogates for ionospheric and ring-current quantities that are too expensive to run with global MHD models for every solar-wind perturbation.

**cuspML** is a gradient-boosted-tree model (XGBoost) that predicts the magnetic-latitude location of the **ionospheric cusp** from upstream solar-wind drivers, using **27&nbsp;years of DMSP particle-precipitation observations** (F13–F18 SSJ) as ground truth. A tilt-stratified subsample controls for the natural dipole-tilt imbalance and yields cleaner partial-dependence curves than published regressions. Manuscript in late revision; code at [github.com/YiwenZhu77/cuspML](https://github.com/YiwenZhu77/cuspML).

**TEC-FNO / SolarMamba** is an in-progress study comparing spherical Fourier neural operators, transformers, and Mamba state-space variants on multi-horizon **total electron content (TEC)** and **SYM-H** forecasting. The headline finding (after a thorough Codex / GPT-5 critical review) reframes the question from *"Mamba wins"* to *"evaluation protocol matters more than architecture choice"* — driven by an input-ablation, protocol-sensitivity, and SC25-holdout matrix. Targeting *Space Weather* (AGU).
