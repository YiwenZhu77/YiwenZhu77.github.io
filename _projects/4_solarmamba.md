---
layout: page
title: SolarMamba (TEC-FNO)
description: Protocol-dependent multi-horizon SYM-H and TEC forecasting (in progress, target Space Weather)
img: assets/img/7.jpg
importance: 4
category: ongoing
---

**SolarMamba** is an in-progress study of how the choice of evaluation protocol &mdash; not just architecture &mdash; controls reported accuracy on multi-horizon ring-current and ionospheric-electron-content forecasting tasks.

### Approach
- Architectures: spherical Fourier neural operators (FNO), transformers, ConvLSTM, and Mamba state-space variants &mdash; trained head-to-head on identical splits.
- Inputs: rolling solar-wind history (F10.7, Kp, Ap, IMF B$_z$) plus prior SYM-H and global TEC maps.
- Targets: 1, 6, 12, 24-hour SYM-H and global TEC nowcasts.
- Evaluation: explicit cross-solar-cycle holdout (SC25 as test) plus a strict input-ablation matrix (SW-only, SW+AE, SW+SYM-H, full).

### Reframing
After an in-depth GPT-5 / Codex critical review, the paper's storyline is being reframed from "Mamba wins" to **"evaluation protocol matters more than architecture choice"** &mdash; a conclusion supported by the input-ablation, protocol-sensitivity, and SC25-holdout experiment packages now in flight. Targeting *Space Weather* (AGU).
