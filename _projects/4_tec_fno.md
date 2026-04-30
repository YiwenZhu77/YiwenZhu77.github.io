---
layout: page
title: TEC-FNO
description: Fourier neural operators for global ionospheric TEC forecasting
img: assets/img/7.jpg
importance: 4
category: research
---

**TEC-FNO** applies **Fourier neural operators (FNO)** to short-horizon (1–24 h) forecasting of global **total electron content (TEC)** maps. The goal is a fast, physics-aware surrogate that competes with operational empirical models (IRI, NeQuick) and with recent transformer-based baselines on identical evaluation splits.

### Approach
- Inputs: rolling history of CODE GIM TEC maps + solar-wind drivers (F10.7, Kp, Ap, IMF Bz).
- Architecture: 2D spherical FNO with periodic-longitude padding and pole-aware spectral mode truncation.
- Loss: log-space MSE (TECU is heavy-tailed); evaluated in both log-space and native TECU.
- Benchmarks: matched train/val/test splits against published transformer + ConvLSTM baselines from the 2024–2025 TEC-prediction literature.

Currently in preparation for a NeurIPS / ICLR submission.
