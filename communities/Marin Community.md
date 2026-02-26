---
rating: ⭐⭐
full_name: Marin — Open Lab for Building Foundation Models
website: https://marin.community/
github: https://github.com/marin-community/marin
founded: 2025-05
parent: CRFM Stanford (spun out)
added: 2026-02-26
deep_researched: false
last_researched: 2026-02-26
revisit_weeks: 12
tags: [foundation-models, open-source-ai, open-science, machine-learning, nlp, reproducibility]
---

# Marin Community

An open lab for building foundation models — together, openly, in public. Launched May 2025 by [[Percy Liang]] and the CRFM Stanford team. The most radical articulation of open-science AI development: every experiment is a public GitHub issue, every PR is open for review, every mistake is documented, every result is shared in real time. No cherry-picking. No ambiguity about what was run. Everything is reproducible.

## Why Interesting
Marin represents an argument about how AI should be built — not the OpenAI way (closed, selective disclosure), not the Llama way (open weights, opaque training), but the true open-source way: complete transparency about the development process, from data curation to training algorithms to evaluation. This is a political commitment as much as a technical one.

The fact that it works (Marin-8B-Base beats Llama 3.1 8B on 14/19 standard benchmarks) shows open science doesn't require sacrificing performance.

## What It Does
- Trains foundation models from scratch (architecture experiments → full training runs)
- Documents all experiments as GitHub issues with hypotheses, code, results, WandB logs
- Open contribution: anyone can submit experiments, review PRs, propose architectures
- Runs a "speedrun" competition for efficient training methods
- Discord community for collaboration

## Models Released
- **Marin-8B-Base** (deeper-starling): Llama architecture, 12.7T tokens. Beats Llama 3.1 8B on 14/19 benchmarks.
- **Marin-8B-Instruct**: Available on Together AI
- **Marin-32B-Base**: Beats OLMo 2 32B Base on 14/19 benchmarks; close to Gemma 3 27B PT

## Infrastructure
- **Levanter**: JAX-based training framework (reproducible, bitwise deterministic). github.com/marin-community/levanter
- **GitHub issues**: Experiment tracking and preregistration
- **WandB**: Live training metrics
- **Marin data browser**: Inspect experiment executions

## Connections
- [[CRFM Stanford]] — parent institution; Percy Liang directing
- [[Percy Liang]] — director
- EleutherAI, Allen AI (AI2), Hugging Face — peer open-source AI projects

*Stub created 2026-02-26 during CRFM Stanford deep research. Deep research pending.*
