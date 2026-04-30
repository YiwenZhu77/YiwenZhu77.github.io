---
layout: about
title: about
permalink: /
subtitle: PhD candidate, <a href='https://physics.rice.edu/'>Department of Physics &amp; Astronomy</a>, Rice University. Advised by <a href='https://profiles.rice.edu/faculty/frank-r-toffoletto'>Frank Toffoletto</a>.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p><strong>Yiwen Zhu (朱亦文)</strong></p>
    <p>Houston, TX, USA</p>
    <p><a href="mailto:yz167@rice.edu">yz167@rice.edu</a></p>

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I'm a final-year PhD candidate in space physics at **Rice University**, working with [Frank Toffoletto](https://profiles.rice.edu/faculty/frank-r-toffoletto) on the dynamics of Earth's inner magnetosphere. I'm concurrently completing an MS in **Computer Science (Data &amp; Artificial Intelligence)** at Rice. My research combines large-scale magnetohydrodynamic (MHD) simulations, kinetic test-particle modeling, and machine learning to understand how the magnetosphere stores and releases energy during geomagnetic storms and substorms.

### Research interests

- **Ring-current &amp; substorm dynamics** &mdash; backward test-particle tracing through coupled MHD + RCM simulations to identify the *bubble origin* of ring-current ions during dipolarization events.
- **Magnetosphere&ndash;ionosphere coupling** &mdash; Rice Convection Model (RCM) modeling of plasma-sheet flow channels, polar-cap convection, field-aligned currents, and the cusp.
- **Machine learning for space weather** &mdash; Fourier neural operators and transformers for ionospheric and ring-current nowcasting; XGBoost models for cusp-location prediction.
- **LLM-driven scientific computing** &mdash; benchmarking frontier LLMs on full-CPU hardware design, building autonomous research-agent pipelines, and surveying long-context reliability in LLMs.

### Recent work

**Completed &amp; submitted**

- *O$^{+}$ outflow contribution to the ring current during geomagnetic storms* &mdash; backward test-particle tracing in coupled MHD + RCM simulations identifies bubble-injection events as the dominant energization channel; Birn-decomposition shows ~30% of ring-current pressure increase originates from coherent dipolarization bubbles. Manuscript in preparation, AGU 2023.
- *XGBoost prediction of ionospheric cusp location* &mdash; 27-year DMSP dataset, tilt-stratified sampling to control for the natural dipole-tilt imbalance. Manuscript in late revision.
- *A Multi-Agent Systems Survey* &mdash; submitted to MDPI *Future Internet*.
- *Operational RCM &amp; geosynchronous-injection nowcasting* &mdash; collaboration with NASA on a real-time injection-prediction model based on RCM (AGU 2022, GEM 2022).

**In progress**

- *Multi-LLM benchmarking on processor design with ASIC physical implementation* &mdash; targeting **MLCAD 2026**, comparing five frontier LLMs across five complexity levels from ALU to full-CPU at 7&nbsp;nm.
- *Long-context reliability in large language models &mdash; a 56-page survey* &mdash; in revision for *Neurocomputing* (Elsevier).
- *Protocol-dependent multi-horizon SYM-H forecasting* (working title: SolarMamba) &mdash; transformer / Mamba-based ring-current index forecasting under cross-solar-cycle evaluation; targeting *Space Weather*.

### Background

Before Rice I earned my BS in Physics at the [Southern University of Science and Technology (SUSTech)](https://www.sustech.edu.cn/) in Shenzhen (GPA 3.85 / 4.00). I'm an HPC affiliate of the [High Altitude Observatory](https://www2.hao.ucar.edu/) at NCAR, where I run my numerical work on the Derecho system. My day-to-day toolchain is Python (polars, JAX, PyTorch), HPC-scale numerical simulation (CHIMP, RCM, MAGE), and a growing stack of LLM agent tooling.

If you're interested in space-physics + ML, magnetospheric particle dynamics, or research-agent infrastructure, I'd love to talk.
