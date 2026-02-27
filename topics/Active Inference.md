---
added: 2026-02-26
last_researched: 2026-02-27
revisit_weeks: 6
next_research: 2026-04-10
rating: ⭐⭐
tags: [alife, machine-behavior, more-than-human, embodied, active-inference, enactivism, social-simulation, open-endedness]
edge_of_chaos: true
deep_researched: true
---

# Active Inference

A unified mathematical framework for understanding how living systems — from bacteria to brains to social collectives — maintain their existence by minimizing variational "free energy" (a measure of surprise or prediction error). Proposed by Karl Friston as the Free Energy Principle (FEP), active inference holds that all biological behavior can be understood as inference: perception updates internal models of the world; action changes the world to match predictions. The agent is simultaneously a scientist (modeling its environment) and an engineer (reshaping reality to fit its model). Arguably the most ambitious unified theory in cognitive/life science — claiming to explain perception, action, learning, attention, consciousness, morphogenesis, sociality, and evolution under one formal language.

## ⚡ Recent Updates
- **2026-02-27:** Deep research completed. Full topic note written.
- **2025:** Active Inference Institute holds its 5th Applied Active Inference Symposium (Nov 12–14). pymdp transitions to JAX backend (v1 alpha).
- **2024:** AII receives 501(c)(3) recognition. Fellows program launched. 4th Applied Symposium held.
- **2023:** Bayesian Mechanics paper in *Interface Focus* (Ramstead et al.) formalizes connections between FEP and physics. AII publishes "Distributed Science" applying active inference to the scientific process itself.
- **2022:** Parr, Pezzulo, Friston textbook [*Active Inference: The Free Energy Principle in Mind, Brain, and Behavior*](https://mitpress.mit.edu/9780262045353/active-inference/) published (MIT Press) — field's anchor text. pymdp Python library published (JOSS).
- **2021:** International Workshop on Active Inference (IWAI) established as annual academic conference. 1st Applied Active Inference Symposium.
- **2018:** WIRED profile — ["The Genius Neuroscientist Who Might Hold the Key to True AI"](https://www.wired.com/story/karl-friston-free-energy-principle-artificial-intelligence/) — brings Friston to wider AI attention.

---

## Domain Summary

Active Inference is built on the **Free Energy Principle (FEP)**: any self-organizing system that maintains its existence must minimize variational free energy — a measure of the difference between the system's internal model (its predictions) and the actual sensory data it receives.

Key concepts:
- **Generative model** — the agent's internal probabilistic model of how the world produces observations
- **Markov blanket** — the statistical boundary separating internal states from external states; the surface through which agent interacts with the world
- **Variational free energy** — a tractable upper bound on surprise (negative log evidence); minimized through both perception and action
- **Expected free energy** — governs policy selection; agents prefer actions that minimize expected surprise, balancing *epistemic value* (curiosity/uncertainty reduction) with *pragmatic value* (goal achievement)
- **Predictive coding** — the neuronal process theory: descending predictions + ascending prediction errors through hierarchical generative models

**Perception** = updating internal model to match sensory data (inference about hidden states)  
**Action** = changing sensory data to match predictions (acting to make predictions true)  
**Learning** = updating the parameters of the generative model over time

This dual optimization resolves the classic dichotomy between passive Bayesian inference and active goal-directed behavior. Unlike reinforcement learning (which maximizes reward), active inference agents maximize model evidence — in effect, they *confirm their existence* rather than maximize utility.

**Scale invariance**: The FEP applies across spatial and temporal scales — from single cells maintaining homeostasis through Markov blankets, to neural circuits, to organisms, to social groups, to ecosystems. This is why it has attracted applications in sociology, linguistics, organizational theory, evolutionary biology, and even quantum mechanics.

**Contested status**: Critics note that the FEP is a mathematical principle (not falsifiable by definition), raising questions about its empirical content. The process theories (predictive coding, active inference) are empirically testable, but the overarching principle itself functions more like a conceptual framework than a standard scientific theory.

---

## Edge of Chaos Analysis

**Is it fast-evolving?** Yes. The field has accelerated dramatically since ~2018:
- Moving from neuroscience-only to applications in AI, robotics, ALife, social science, organizational design, philosophy of mind
- pymdp library democratizing implementation; JAX migration underway
- VERSES AI (Maxwell Ramstead) commercializing the framework; deep pockets + rapid product development
- International Workshop on Active Inference (IWAI) now annual; attendance growing
- The AII's open-science ecosystem generating dozens of novel applications yearly

**Will it be hot in 1-3 years?** Very likely. Active inference is gaining traction as an alternative to RL for AI agents with *intrinsic curiosity* and *epistemic drives*. The connection to large language models and world models is being actively developed. The framework is also being applied to multi-agent systems, collective intelligence, and decentralized AI — all areas with high funding and interest. Could break into mainstream AI discourse if JAX-based pymdp proves competitive.

**What's driving it?**
- Dissatisfaction with reward-maximizing AI agents (no intrinsic curiosity, no robust world models)
- Interest in *embodied* and *enactive* AI — agents that actively shape their environment
- Neuroscience validation: predictive coding has strong empirical support in visual/motor cortex
- The AII's open-science infrastructure has made the field unusually accessible

---

## Sub-topics & Trends (last 3-5 years)

- **Bayesian Mechanics** (2022–present) — new sub-field connecting FEP to statistical physics; Ramstead, Sakthivadivel, Friston, Klein. Formalizing the physics of belief-updating systems. [*Interface Focus* paper 2023](https://royalsocietypublishing.org/doi/10.1098/rsfs.2022.0029).
- **Multi-agent active inference** — Conor Heins, Maxwell Ramstead, Mahault Albarracin. Collective intelligence, epistemic communities, societal dynamics. Epistemic Communities paper 2022.
- **Active inference for robotics** — real-time robot control using FEP; IWAI 2022 symposium theme. Competitive with model-based RL.
- **Quantum active inference** — Chris Fields. Applying FEP to quantum systems; morphogenesis; consciousness. Highly speculative but intellectually stimulating.
- **Morphogenesis and developmental biology** — Friston + Michael Levin collaboration. Cells as active inference agents; pattern regulation through FEP. Bridges ALife and developmental biology.
- **Computational psychiatry** — active inference accounts of schizophrenia, autism, depression. Already has clinical traction.
- **Social and cultural active inference** — Ramstead, Veissière, Albarracin. Culture as shared generative models; communication as socially extended active inference.
- **Active inference and decentralized systems** — "Active Blockference" (2022); DeSci applications; organizational design.
- **pymdp v1 (JAX)** — major engineering effort underway. Conor Heins et al. Moving to GPU-accelerated JAX backend for scalability.

---

## Key People

- **[[Karl Friston]]** — FRS, UCL Wellcome Centre for Human Neuroimaging. Originator of the Free Energy Principle (~2006). Most cited neuroscientist alive (~300k citations). Also created SPM (statistical parametric mapping) — dominant neuroimaging toolbox. [Website](https://www.fil.ion.ucl.ac.uk/~karl/). ⭐⭐⭐
- **Thomas Parr** — UCL. Co-author of the definitive textbook. Leads formal development of active inference for psychiatry and perception. ⭐⭐
- **Maxwell Ramstead** — Director of Research at VERSES AI; previously UCL/McGill. Applying active inference to collective cognition, culture, social dynamics. Bayesian Mechanics co-developer. ⭐⭐⭐
- **Giovanni Pezzulo** — ISTC-CNR Rome. Co-author of the textbook. Leads applications in robotics, motor control, and decision-making.
- **Andy Clark** — Edinburgh. "Whatever next?" paper (2013) — popularized predictive processing for cognitive science. *Surfing Uncertainty* (2016).
- **Anil Seth** — Sussex. Extending predictive processing to consciousness and the "controlled hallucination" theory of perception. *Being You* (2021). Bridge figure to public discourse.
- **Daniel Friedman** — UC Davis / AII President. Leads AII operations. Applied active inference to organizational design, DeSci.
- **Conor Heins** — Max Planck Institute for Animal Behavior. Multi-agent active inference; pymdp lead developer. Animal behavior + AI lens.
- **Chris Fields** — Independent researcher. Quantum active inference; morphogenesis; consciousness. Wildcard interdisciplinarian.
- **Mahault Albarracin** — UQAM. Active inference in social cognition and collective dynamics.
- **Avel Guénin-Carlut** — VERSES Lab / Sussex / Kairos Research. Philosophy of active inference; societal dynamics.
- **Dalton Sakthivadivel** — Bayesian Mechanics formalization. Physics angle on FEP.
- **Beren Millidge** — Oxford. Predictive coding and active inference; bridge to ML community.

---

## Must-Read List

### Books
- [*Active Inference: The Free Energy Principle in Mind, Brain, and Behavior*](https://mitpress.mit.edu/9780262045353/active-inference/) (Thomas Parr, Giovanni Pezzulo, Karl Friston — MIT Press, 2022) — the definitive textbook. Open access. Start here.
- [*Surfing Uncertainty: Prediction, Action, and the Embodied Mind*](https://global.oup.com/academic/product/surfing-uncertainty-9780190217013) (Andy Clark — Oxford University Press, 2016) — best accessible introduction to predictive processing.
- [*Being You: A New Science of Consciousness*](https://www.penguinrandomhouse.com/books/609357/being-you-by-anil-seth/) (Anil Seth — Dutton, 2021) — predictive coding → consciousness, written for general audience. Very Amber-relevant.
- [*The Experience Machine: How Our Minds Predict and Shape Reality*](https://www.penguinrandomhouse.com/books/700459/the-experience-machine-by-andy-clark/) (Andy Clark — Pantheon, 2023) — updated Clark, more accessible.

### Papers (Essential)
- [The free-energy principle: a unified brain theory?](https://www.nature.com/articles/nrn2787) (Friston, *Nature Reviews Neuroscience* 2010) — the landmark overview paper
- [Active Inference: A Process Theory](https://doi.org/10.1162/neco_a_00912) (Friston et al., *Neural Computation* 2017) — the canonical process theory formulation
- [Life as we know it](https://royalsocietypublishing.org/doi/10.1098/rsif.2013.0475) (Friston, *J R Soc Interface* 2013) — applying FEP to living systems; directly relevant to ALife
- [On Bayesian mechanics: A physics of and by beliefs](https://royalsocietypublishing.org/doi/10.1098/rsfs.2022.0029) (Ramstead et al., *Interface Focus* 2023) — Bayesian Mechanics paper
- [Whatever next? Predictive brains, situated agents, and the future of cognitive science](https://doi.org/10.1017/S0140525X12000477) (Clark, *Behavioral and Brain Sciences* 2013) — key predictive processing synthesis
- [Epistemic communities under active inference](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9027706/) (Albarracin et al., *Entropy* 2022) — social/collective angle; most relevant to Amber
- [Thinking through other minds: A variational approach to cognition and culture](https://www.cambridge.org/core/journals/behavioral-and-brain-sciences/article/abs/thinking-through-other-minds-a-variational-approach-to-cognition-and-culture/9A10399BA85F428D5943DD847092C14A) (Veissière, Ramstead et al., *BBS* 2020) — culture as shared generative models
- [pymdp: A Python library for active inference in discrete state spaces](https://doi.org/10.21105/joss.04098) (Heins et al., *JOSS* 2022) — the key software paper; open access
- [Knowing one's place: a free-energy approach to pattern regulation](https://royalsocietypublishing.org/doi/10.1098/rsif.2014.1383) (Friston, Levin, Sengupta, Pezzulo — *J R Soc Interface* 2015) — morphogenesis via FEP; ALife angle

### Journals
- [*PLOS Computational Biology*](https://journals.plos.org/ploscompbiol/) — major venue for active inference papers
- [*Neural Computation*](https://direct.mit.edu/neco) — key venue for formal papers
- [*Entropy* (MDPI)](https://www.mdpi.com/journal/entropy) — open-access; many AII-affiliated papers published here
- [*Journal of the Royal Society Interface*](https://royalsocietypublishing.org/journal/rsif) — living systems and complexity angle
- [*Active Inference Journal*](https://www.activeinference.institute/) — AII's own open-access journal, interdisciplinary

---

## Key Venues

- **[International Workshop on Active Inference (IWAI)](https://iwaiworkshop.github.io/)** — annual academic workshop; the technical academic home of the field. Accepts papers. ⭐⭐
- **[Applied Active Inference Symposium](https://coda.io/@active-inference-institute/2nd-applied-active-inference-symposium)** — annual AII flagship; broader audience; call for presenters open. ⭐⭐⭐
- **[[ALIFE Conference]]** — major venue where FEP/active inference work appears; morphogenesis, open-endedness threads
- **[CogSci Conference](https://cognitivesciencesociety.org/)** — cognitive science; active inference papers on perception/action
- **NeurIPS / ICLR** — growing presence; active inference as alternative to RL

---

## Key Communities & Institutions

- **[[Active Inference Institute]]** — open-science home of the community. Discord, YouTube, symposia, journal, textbook groups. The essential starting point. <https://www.activeinference.institute/> ⭐⭐⭐
- **[UCL Wellcome Centre for Human Neuroimaging](https://www.fil.ion.ucl.ac.uk/)** — Friston's home lab; source institution. Karl Friston, Thomas Parr, Adeel Razi.
- **[VERSES AI](https://www.verses.ai/)** — commercial active inference company. Maxwell Ramstead as Director of Research. Significant R&D investment. Friston is Chief Scientist.
- **[infer-actively (GitHub)](https://github.com/infer-actively)** — open-source active inference software organization; pymdp.
- **[BIASlab (TU Eindhoven)](https://biaslab.github.io/)** — Bert de Vries group. RxInfer.jl (Julia-based active inference); Forney-style Factor Graphs for FEP. European engineering angle.
- **[Sussex Sackler Centre](https://www.sussex.ac.uk/sackler/)** — Anil Seth group. Consciousness + predictive processing. Several TNB Group chairs based here.
- **[Santa Fe Institute](https://www.santafe.edu/)** — complexity science community; overlap with active inference via self-organization, adaptive systems

---

## Fellowships & Programmes

- **[Active Inference Institute Research Fellowship](https://fellows.activeinference.institute)** — 2-year, self-directed, unpaid but provides institutional affiliation + network. Rolling applications. Contact: [blanket@activeinference.institute](mailto:blanket@activeinference.institute).
- **[AII Internship Program](https://coda.io/form/Application-for-Internship-at-Active-Inference-Institute_dFhds6b9JXv)** — 1–6 months, mentored. Open to all backgrounds.
- **[Theoretical Neurobiology Group](mailto:theoreticalneurobiology@gmail.com)** — weekly sessions with Friston. Free; join by email.

---

## How Can Amber Engage?

- **Join AII Discord** immediately — [discord.activeinference.institute](https://discord.activeinference.institute/). Active community, weekly meetings, very welcoming.
- **Theoretical Neurobiology Group** — attend weekly online sessions with Friston. Email [theoreticalneurobiology@gmail.com](mailto:theoreticalneurobiology@gmail.com) to join the mailing list.
- **5th Applied Symposium 2025** (Nov 12–14) — call for presenters is open. Amber's work on collective AI behavior, agent ethology, and machine behavior is highly relevant.
- **GuestStream presenter** at AII — contact Daniel Friedman to present. Excellent visibility in the community.
- **Active Inference Journal** — publish early/speculative work connecting active inference to more-than-human design or agent ethology.
- **Read the textbook** — Parr/Pezzulo/Friston (2022); AII runs textbook groups for guided reading.
- **Follow Beren Millidge** — Oxford-based, predictive coding × ML; natural Oxford connection for Amber.

---

## For Amber

**Who should Amber know?**
- **[[Karl Friston]]** — at UCL; Amber is at Oxford. Practically neighbors. TNB Group is the best path.
- **Maxwell Ramstead** (VERSES AI) — active inference × collective cognition × distributed AI. Natural collaborator for Amber's decentralized AI work.
- **Avel Guénin-Carlut** (VERSES/Sussex) — philosophy of active inference × societal dynamics. Most aligned with Amber's critical theory side.
- **Conor Heins** (Max Planck Animal Behavior) — multi-agent active inference × animal behavior. Direct overlap with agent ethology.
- **Daniel Friedman** (AII) — key connector and community-builder; responds to email.
- **Beren Millidge** (Oxford) — local; predictive coding × ML.

**Who might like Amber's work?**
- **Maxwell Ramstead** — Amber's work on AI agents in ecological/social contexts maps directly to his research.
- **Avel Guénin-Carlut** — philosophical angle on collective active inference and societal dynamics.
- **Conor Heins** — agent ethology lens; active inference as model of animal/AI behavior.
- **The ArtStream community** — AII has an explicit ArtStream; Amber's practice would be welcome.

**Who can Amber collaborate with?**
- Ramstead on collective active inference models for multi-agent AI systems
- Heins on ethological models of AI agents using FEP framework
- Guénin-Carlut on philosophy of machine agency

**What publications should Amber target?**
- *Active Inference Journal* — open-access, interdisciplinary, explicitly welcomes non-standard contributions
- *Entropy* (MDPI) — Ramstead-affiliated, open-access, many AII papers
- IWAI workshop proceedings — good for technical contributions
- Applied Symposium proceedings/videos — community visibility

**Key connection to Amber's research:**
1. **Agent Ethology** — active inference provides the strongest formal theory of *why* agents behave as they do; Amber's empirical work on AI ethology could be framed through FEP, giving it theoretical grounding.
2. **Cyborg Sociology** — culture-as-shared-generative-models (Ramstead, Veissière) is deeply compatible with Amber's interest in how humans and AI co-constitute social reality.
3. **ALife** — FEP applied to living systems (Friston 2013) is foundational for ALife theories; morphogenesis via active inference (Friston + Levin) directly relevant.
4. **More-than-Human Design** — active inference provides a non-anthropocentric theory of agency (bacteria, slime molds, forests all operate by FEP); powerful conceptual framing for more-than-human systems.
5. **Decentralized AI** — "Active Blockference" and organizational active inference (AII) provide frameworks for multi-agent decentralized systems.
6. **Open-Endedness** — connection to open-ended evolution through FEP as theory of adaptive self-organization.
7. **Machine Behavior** — FEP potentially explains the "why" behind emergent machine behaviors; active inference agents have intrinsic curiosity/epistemic drive that explains exploratory behaviors.

---

## Recent Important Updates (Timeline)

- **2024:** VERSES AI raises significant funding; Friston as Chief Scientist signals commercialization of active inference for AI
- **2023:** Bayesian Mechanics paper (*Interface Focus*) — formalizes connections between FEP and statistical physics; a major theoretical advance
- **2023:** "Distributed Science" paper — applying AII's own framework to the scientific process; novel institutional experiment
- **2022:** Parr/Pezzulo/Friston textbook published — field's anchor text. Makes active inference accessible to non-specialists
- **2022:** pymdp published in *JOSS* — open-source Python library makes active inference implementable without MATLAB/SPM
- **2021:** AII formally incorporated as nonprofit; IWAI established as annual workshop; 1st Applied Symposium
- **2018:** WIRED profile — brings Friston to mainstream AI attention; begins wave of cross-disciplinary interest
- **2015:** Friston + Levin: morphogenesis via FEP — seed of ALife applications

---

## Adjacent Topics

- [[Enactivism]] — philosophical cousin; shares emphasis on embodied agent-environment coupling; Maturana/Varela's autopoiesis → FEP
- [[Autopoiesis]] — FEP is a formalization of autopoiesis in Bayesian terms; Maturana/Varela → Friston lineage
- [[Predictive Processing]] — FEP's neurological process theory; Andy Clark, Anil Seth
- [[Cybernetics]] — FEP draws on control theory and homeostasis; Ashby's good regulator theorem
- [[Artificial Life]] — FEP applied to living systems; morphogenesis, self-organization, open-endedness
- [[Machine Behavior]] — active inference as formal theory of machine agency
- [[Self-Organization]] — FEP as mathematical account of self-organization
- [[Open-Endedness]] — active inference agents' intrinsic curiosity drives open-ended exploration
- [[Emergence]] — FEP and emergence at multiple scales
- [[Distributed Cognition]] — socially extended active inference; culture as shared generative models

---

## Open Questions

1. **Falsifiability problem** — the FEP is mathematically true by construction; is it scientifically useful or just a tautology? How to distinguish FEP predictions from trivial claims?
2. **Scaling to real AI systems** — can active inference compete with RL at scale? pymdp JAX version is key test.
3. **Multi-agent FEP** — how do multiple active inference agents coordinate? What happens when generative models conflict? Key for collective/social applications.
4. **Quantum active inference** — does FEP apply at quantum scales? Chris Fields' controversial claim.
5. **Consciousness and phenomenology** — does FEP explain the *feeling* of being an agent, or just the functional organization?
6. **Morphogenesis** — can FEP actually explain developmental biology? The Friston-Levin collaboration is live research here.
7. **Design implications** — if all agents minimize free energy, what does this mean for designing AI-human environments? How do we design "preferred priors"?

---

## Why Interesting

Active inference occupies a singular position: it's the most ambitious unifying theory in cognitive/life science, AND it has a thriving open-science community building tools, institutions, and applications. For Amber, the relevance is rare and deep:

- **The formal language Amber needs** — agent ethology, more-than-human design, and cyborg sociology all orbit the question "what is it like to be an agent in an environment?" Active inference provides a *precise mathematical answer* that works at every scale from bacteria to societies.
- **Friston at UCL / Oxford adjacency** — the intellectual center of the field is practically next door. TNB Group meets weekly online; the field's creator is reachable.
- **Edge of chaos** — the field is transforming rapidly (VERSES AI, JAX pymdp, quantum AIF, collective AIF). Getting in now means being present at the moment of crystallization.
- **Community alignment** — the AII's radical openness, interdisciplinarity, and commitment to open science matches Amber's working style and values. Not a gated institution but a genuinely collaborative ecosystem.
- **The design angle** — "preferred priors" in active inference are essentially design objects: you design what the agent *expects and desires*. This is a powerful frame for more-than-human design — designing not just the environment but the agent's anticipatory model of it.

---

## 📋 Update Log
| Date | Researcher | Action |
|------|-----------|--------|
| 2026-02-26 | Biber (agent) | Initial stub created. Basic frontmatter and placeholder notes. |
| 2026-02-27 | Biber (subagent) | Full deep research completed at ⭐⭐ depth. All sections filled. Key people, institutions, papers, venues, communities, For Amber analysis, open questions, edge of chaos analysis. `deep_researched: true`. |
