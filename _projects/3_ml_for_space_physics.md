---
layout: page
title: Machine Learning for Space Physics
description: Fast surrogates for ionospheric and ring-current quantities driven by space data
img: assets/img/area_ml_physics.jpg
importance: 3
category: research
---

Global MHD models capture the underlying physics, but they are far too expensive to run for every solar-wind perturbation that an operational service has to react to. Machine-learning surrogates &mdash; trained on decades of in-situ and ground-based observations and on the upstream solar-wind drivers that ultimately set everything in motion &mdash; offer fast, accurate predictors that can be evaluated thousands of times for the price of a single physics simulation.

Within this area I work on the following projects:

- **cuspML.** A gradient-boosted model that predicts the magnetic-latitude location of the ionospheric cusp from upstream solar-wind drivers, trained on 27&nbsp;years of DMSP particle-precipitation observations, with a tilt-stratified subsample to control for the natural dipole-tilt imbalance that makes na&iuml;ve fits over-fit high-tilt regimes.
- **TEC-FNO / SolarMamba.** Multi-horizon forecasting of total electron content and ring-current SYM-H, comparing spherical Fourier neural operators, transformers, and Mamba state-space models on identical splits, with an explicit cross-solar-cycle holdout; the central finding is that *evaluation protocol matters more than architecture choice* on this task.
