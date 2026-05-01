---
layout: page
title: LLM Validation &amp; Exploration
description: Stress-testing frontier large language models on technical, long-horizon work
img: assets/img/area_llm_validation.jpg
importance: 3
category: research
---

Frontier large language models are being deployed for tasks far beyond chat — from generating production code to running multi-step agentic workflows. Whether they are *actually reliable* on these high-stakes, long-horizon tasks is a separate, largely empirical question. This area asks where today's frontier LLMs succeed, where they fail in non-obvious ways, and what kinds of evaluation protocols we need to tell the difference.

Within this area I work on the following projects:

- **LLM-driven processor design (MLCAD 2026 submission).** The first systematic head-to-head comparison of five frontier LLMs across five complexity levels of CPU design, all the way to a full pipelined processor with branch prediction, with end-to-end ASIC synthesis, place-and-route, and timing closure at 7&nbsp;nm.
- **Long-context reliability survey.** A 56-page survey, in revision for *Neurocomputing*, that catalogues failure modes of long-context LLMs (retrieval drift, distractor-induced collapse, position-bias asymmetries, recurrence-cascade errors), benchmarks what current public evaluations actually measure, and gives prescriptive design guidelines for practitioners deploying long-context LLMs in retrieval, summarization, and agent settings.
