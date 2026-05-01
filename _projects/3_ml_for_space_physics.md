---
layout: page
title: Machine Learning for Space Physics
description: Fast surrogates for ionospheric and ring-current quantities
img: assets/img/area_ml_physics.jpg
importance: 3
category: research
---

Global physical models capture the underlying physics, but they are too expensive to run for every solar-wind perturbation that an operational service has to react to. Machine-learning surrogates, trained on long historical observation records, offer fast and accurate predictors at a tiny fraction of the computational cost.

Within this area I work on the following projects:

- **Ionospheric cusp location prediction.** A gradient-boosted model that predicts the magnetic-latitude location of the ionospheric cusp from upstream solar-wind drivers, trained on decades of in-situ particle-precipitation observations.
- **Total electron content and ring-current forecasting.** Multi-horizon prediction of the ionospheric total electron content and the ring-current SYM-H index, using neural-operator and state-space models on identical evaluation splits.
