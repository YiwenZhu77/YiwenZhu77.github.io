---
layout: page
title: Machine Learning for Space Physics
description: Fast surrogates for ionospheric and ring-current quantities
img: assets/img/area_ml_physics.jpg
importance: 3
category: research
---

Global physical models capture the underlying physics, but are too expensive to run for every solar-wind perturbation an operational service has to react to. Machine-learning surrogates trained on long historical observation records offer fast, accurate predictors that can be evaluated thousands of times for the cost of a single physics simulation.

Within this area I work on the following projects:

- **cuspML.** A gradient-boosted model that predicts the location of the ionospheric cusp from upstream solar-wind drivers.
- **TEC-FNO / SolarMamba.** Multi-horizon forecasting of total electron content and ring-current SYM-H, comparing Fourier neural operators, transformers, and Mamba state-space models on identical splits.
