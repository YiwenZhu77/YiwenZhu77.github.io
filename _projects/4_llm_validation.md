---
layout: page
title: LLM Validation &amp; Exploration
description: Frontier-LLM benchmarks for processor design and a survey of long-context reliability
img: assets/img/area_llm_validation.jpg
importance: 4
category: research
---

Two threads on what frontier large language models can — and can't — do reliably for technical work.

**Multi-model LLM benchmark on processor design (MLCAD 2026 submission).** The first systematic head-to-head comparison of Claude Opus, GPT-5, Gemini&nbsp;2.5 Pro, DeepSeek-V3, and DeepSeek-R1 at full-CPU complexity (L1 ALU → L5 pipelined CPU with branch prediction), with end-to-end ASIC synthesis, place-and-route, and timing closure at 7&nbsp;nm. Claude Opus passes L1–L5 first iteration; other models hit a clear complexity wall around L2–L3. The agent loop integrates AST-level pre-compile error analysis, VCD waveform tracing, and structural module-decomposition skeletons.

**Long-Context Reliability in LLMs — a 56-page survey** (in revision for *Neurocomputing*, Elsevier). A unified taxonomy of long-context failure modes (retrieval drift, distractor-induced collapse, position-bias asymmetries, recurrence-cascade errors), a comparative analysis of current public benchmarks with attention to what each one *fails* to measure, and a prescriptive Design Guidelines section for practitioners deploying long-context LLMs in retrieval, summarization, and agent settings.
