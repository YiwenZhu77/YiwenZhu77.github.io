---
layout: page
title: LLMs × Hardware (MLCAD 2026)
description: How complex can LLMs go? Multi-model empirical study of processor design with ASIC PnR (in progress)
img: assets/img/2.jpg
importance: 5
category: ongoing
---

**MLCAD 2026 submission** &mdash; the first systematic head-to-head benchmark of frontier LLMs at full-CPU complexity, with end-to-end ASIC physical implementation.

### Setup
- **Five frontier models**: Claude Opus 4.7, GPT-5, Gemini 2.5 Pro, DeepSeek-V3, DeepSeek-R1.
- **Five complexity levels**: L1 (28-line ALU) → L5 (full pipelined CPU with branch prediction, ~500&nbsp;LoC).
- **Single-file constraint** at every level &mdash; defended against reviewer pushback with a planned ablation that allows decomposition for high-complexity levels.
- **Canonical reference policy**: every model gets the same fixed Opus-4.6 reference at each level &mdash; no per-model leakage, mitigated by a no-reference ablation and an alternate-reference ablation.
- **End-to-end ASIC**: synthesis &rarr; place &amp; route &rarr; timing closure at 7&nbsp;nm with a commercial PDK.
- **Headline result so far**: Claude Opus passes L1&ndash;L5 first iteration, with measurable IPC and branch-prediction-miss numbers; other models hit a clear complexity wall around L2&ndash;L3.

### Tooling
The agent loop integrates AST-level pre-compile error analysis, VCD waveform tracing for first-divergence-cycle localization, and structural module-decomposition skeletons. Built on top of my [ARIS](/projects/aris/) research-agent framework.

Submission deadline: **2026-05-23** (MLCAD 2026, Jeju, Korea).
