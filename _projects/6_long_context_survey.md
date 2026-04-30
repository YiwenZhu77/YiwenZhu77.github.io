---
layout: page
title: Long-Context Reliability of LLMs
description: A 56-page survey on benchmarks, failure modes, and practitioner guidelines (in revision, Neurocomputing)
img: assets/img/4.jpg
importance: 6
category: ongoing
---

A 56-page survey on **long-context reliability in large language models** &mdash; covering retrieval-style benchmarks (NIAH and successors), reasoning-over-context evaluations, document-level QA, agentic / tool-use long horizons, and the engineering trade-offs between sliding-window attention, position-extrapolation tricks, and full-attention scaling.

### Contributions
- Unified taxonomy of long-context failure modes (retrieval drift, distractor-induced collapse, position-bias asymmetries, recurrence-cascade errors).
- Comparative analysis of current public benchmarks with attention to what each one *fails to measure* &mdash; the largest gap is realistic agentic / multi-turn long horizons.
- A prescriptive **Design Guidelines** subsection for practitioners deploying long-context LLMs in retrieval, summarization, and agent settings.

In revision for *Neurocomputing* (Elsevier) after a successful auto-review-loop polish (3 rounds, 7&rarr;9 / 10 reviewer scores).
