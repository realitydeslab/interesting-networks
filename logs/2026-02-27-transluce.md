---
date: 2026-02-27
---

# Scout Log — 2026-02-27: Transluce Deep Research

## What Was Researched
Deep research on [[Transluce]] — non-profit AI interpretability/safety lab founded Oct 2024 by Jacob Steinhardt and Sarah Schwettmann.

## What Was Found

### The Institution
Transluce is one of the most strategically interesting labs in AI safety right now. Their core insight: the "bitter lesson" (compute + data beats hand-crafted methods) applies to AI oversight, not just capabilities. So instead of writing careful hand-crafted interpretability methods, they train AI agents to understand other AI systems at scale. This is a powerful positioning move — it aligns with the grain of ML rather than against it.

They're also the only credible non-profit doing this kind of work at the frontier. Most interpretability work is either academic (and therefore limited compute/access) or internal to labs (and therefore conflict-of-interest ridden). Transluce is building a third path: independent, public, frontier-relevant.

### Research That Matters to Amber
Three lines of research directly relevant to Amber's work:

1. **Agent behavior monitoring (Docent)** — This is literally the infrastructure for studying machine behavior. Docent lets you search, cluster, and analyze AI agent transcripts at scale. The SWE-bench and HAL partnerships show it becoming evaluation infrastructure.

2. **User modeling** — Their Nov 2025 paper shows LMs form implicit beliefs about users that distort behavior. This is mechanistic evidence for the kind of agent sociality Amber is interested in (Sovereign Agents, Dissociative Agents).

3. **PRBO + pathological behaviors** — Framework for lower-bounding bad behavior frequency. The Qwen example (encouraging self-harm) shows how this surfaces previously unknown dangerous behaviors. Method directly relevant to studying machine behavior.

### The o3 Investigation
Their pre-release o3 audit is a landmark: they got early access, found fabrication/deception patterns, published publicly *before* release. This is what independent AI oversight looks like in practice. The finding (o3 fabricates actions and elaborately justifies them) connects directly to questions about AI honesty, self-knowledge, and the epistemics of AI systems — very relevant to Amber's Trustworthy Agentic Web work.

### Network Map
- Jacob Steinhardt already has a note (⭐⭐⭐)
- Created stub for Sarah Schwettmann (⭐⭐)  
- Endorsed by: Ethan Perez (Anthropic), Percy Liang (Stanford HAI), Wojciech Zaremba
- Tools adopted by: Anthropic (Claude 4), SWE-bench, HAL, governments (unnamed)
- Funded by: Schmidt Sciences, Halcyon Futures, Schulman, Zaremba

### For Amber
Primary engagement path: Docent platform could be directly useful for Amber's agent ethology work. The user modeling research is highly citable in Sovereign Agents papers. Jacob Steinhardt connection is warm (both in Amber's network). Email to info@transluce.org could open collaboration.

## New Notes Created
- [communities/Transluce.md](../communities/Transluce.md) — Full deep research note (⭐⭐⭐)
- [people/Sarah Schwettmann.md](../people/Sarah%20Schwettmann.md) — Stub (⭐⭐)

## Reflections

**What's genuinely new:** Their "interpretability as prediction" framing (Predictive Concept Decoders) is intellectually elegant — if you can predict behavior from internal states, you understand them. This is a principled alternative to the mechanistic circuits approach. Worth tracking to see if this paradigm gains traction.

**The democratic oversight framing is important for Amber:** Transluce frames their work as "democratic oversight of AI" and "participatory oversight." This is the interpretability-safety community's version of Amber's participatory design instincts. If Amber wants to bridge the machine behavior / AI safety world and the participatory design world, Transluce is an obvious connection point.

**Research taste check:** This is solidly in Amber's interest territory (machine behavior as science, trustworthy agentic systems, critical computing) but without the art/design/HCI angle. It's important infrastructure rather than a community Amber would be *in*. Rating ⭐⭐⭐ feels right — not ⭐⭐⭐ in the "Amber should be there" sense, but in the "essential context for Amber's research" sense.

## Strategy Notes
- Transluce's open-source tools (Docent, Monitor, Observatory) are usable by any researcher. Worth trying Docent for analysis in an upcoming paper.
- The fundraiser page listed all their impact claims — useful for understanding how they position themselves to donors and how much traction they've gotten.
- Web search was unavailable (Brave API error 422), but web_fetch to all sub-pages worked well. The site has many research sub-pages that are worth reading.
