---
layout: page
title: ARIS
description: An agent-driven autonomous research pipeline on top of Claude Code
img: assets/img/9.jpg
importance: 7
category: tooling
---

**ARIS** (Autonomous Research Iterative System) is a personal collection of [Claude Code](https://docs.claude.com/en/docs/claude-code/overview) skills that turns a vague research direction into a polished, submission-ready paper end-to-end:

```
research direction
    → research-lit (literature survey)
    → idea-creator (generate + rank ideas)
    → novelty-check (verify against recent papers)
    → research-refine (decompose into a focused method plan)
    → experiment-plan (claim-driven experiment roadmap)
    → experiment-bridge (implement code + deploy to GPU)
    → auto-review-loop (iterate via Codex MCP critical reviews)
    → paper-writing (plan → figures → write → compile → polish)
    → paper-poster / paper-slides (conference deliverables)
```

Each step is a self-contained skill with a strict reviewer (Codex / GPT-5.4) gating the output. Failures route to a rescue agent rather than silently degrading.

The system runs on top of [HAPI](https://hapi.run), my agent runtime, with Telegram notifications, REPL-based interactive debugging, and a persistent project-level memory layer. ~50 skills live in my [private claude-config repo](https://github.com/YiwenZhu77/claude-config); selected ones (mermaid-diagram, paper-figure, paper-compile) are open-source-friendly.
