---
rating: ⭐⭐⭐
added: 2026-02-26
last_researched: 2026-03-02
revisit_weeks: 4
next_research: 2026-03-30
tags: [computational-creativity, alife, art-science, open-endedness, machine-behavior]
edge_of_chaos: true
deep_researched: true
---

# Computational Creativity

The art, science, philosophy, and engineering of computational systems that exhibit behaviours unbiased observers would deem creative. Computational Creativity (CC) is not the same as "generative AI" — it is a research field explicitly concerned with the *nature of creativity itself*: what it is, how to model it, how to evaluate it, and what it means for a machine to be genuinely creative rather than merely generative. The field predates the LLM revolution by decades and brings philosophical rigour to questions that ML communities often elide.

## ⚡ Recent Updates
- **2026-03-02:** Deep research completed. Upgraded to ⭐⭐⭐ due to direct Joel Lehman connection, ALIFE overlap, and Amber's specific research interests in agent ethology and open-endedness.
- **2026-02-26:** Initial stub created.

---

## Domain Summary

### What is Computational Creativity?

Margaret Boden's foundational definition: creativity is "the ability to come up with ideas or artefacts that are new, surprising, and valuable." CC asks whether and how this can be computationally instantiated. The [Association for Computational Creativity](http://computationalcreativity.net/home/) offers the operational definition: "the art, science, philosophy and engineering of computational systems which, by taking on particular responsibilities, exhibit behaviours that unbiased observers would deem to be creative."

**Key distinctions from "generative AI":**
- Generative AI = produce outputs (text, images, music). CC = ask whether those outputs constitute *creativity*
- CC explicitly theorises **creativity as process**, not just product — what cognitive/computational mechanisms produce creative novelty?
- CC demands **autonomy** (the system, not the programmer, is responsible for creative choices), **intentionality** (the system has goals/motivations), and **evaluation** (the system or community judges quality)
- CC includes self-evaluating systems, metacognitive creativity, and systems that can reflect on their own outputs

**Boden's three types of creativity** (foundational taxonomy):
1. **Combinational creativity** — novel combinations of familiar ideas (most generative AI)
2. **Exploratory creativity** — exploring the structured possibilities of a conceptual space (AARON, jazz improvisation)
3. **Transformational creativity** — changing the rules of the space itself (the rarest, most profound form — does any AI achieve this?)

### Historical Roots

- **1950s–60s:** Creativity and discovery listed as explicit goals of AI at the 1956 Dartmouth Conference. BACON (Simon et al.) rediscovered scientific laws through constrained search.
- **1970s–80s:** TALE-SPIN (Meehan, 1977) — narrative generation through character goal simulation. AARON (Harold Cohen, 1973–) — rule-based generative art, one of the most enduring CC systems.
- **1990s:** Margaret Boden's *The Creative Mind* (1990) — the field's founding text. Formalised computational creativity as a distinct research programme. MINSTREL (Turner, 1993) — story generation with creative re-use via TRAMs.
- **2000s:** ICCC predecessor workshops (2004–2008). Growing emphasis on evaluation — when can we call a system creative? Csikszentmihalyi's DIFI framework (domain-individual-field) imported to CC.
- **2010s:** ICCC founded (2010). Painting Fool (Simon Colton). Quality-diversity algorithms (Stanley, Lehman). Evaluation frameworks (Jordanous 2012). Neural networks begin to enter the field.
- **2020s:** LLMs and diffusion models explode. Field faces identity crisis: are ChatGPT/Midjourney/Sora "creative"? CC researchers push back — novelty ≠ creativity, generation ≠ autonomy. New questions: evaluating LLM creativity, human-AI co-creativity, AI as creative collaborator.

---

## Edge of Chaos Analysis

**Status: actively churning.** The LLM/diffusion wave created simultaneous opportunity and threat for CC:
- **Opportunity:** The field's deep questions (what is creativity? how to evaluate it?) are suddenly mainstream
- **Threat:** ML conferences appropriate "creativity" without the philosophical infrastructure CC has built
- **Response:** CC community emphasising what distinguishes the field — evaluation frameworks, autonomy, intentionality — things ChatGPT lacks

**Why it's edge of chaos right now (2024–2026):**
- Questions of machine creativity have moved from niche to culture-war (artists vs. AI, copyright, authenticity)
- CC's theoretical apparatus is needed but underappreciated in ML mainstream
- New hybrid questions: can LLMs be genuinely creative, not just statistically generative?
- Open-endedness research (Lehman, Stanley) is converging with CC questions in interesting ways

**Hot in 1-3 years because:**
- Human-AI co-creativity becomes the dominant design paradigm
- Copyright and attribution debates force legal/philosophical precision about machine creativity
- Agent-based creative systems (autonomous art agents, creative open-ended environments) become practical

---

## Sub-topics & Trends (2021–2026)

- **Human-AI co-creativity** — designing systems where creativity emerges from human-machine collaboration, not replacement
- **LLM creativity evaluation** — do LLMs exhibit combinational, exploratory, or transformational creativity? Most work suggests only combinational
- **Creative autonomy** — what does it mean for a system to be creatively responsible for its output?
- **Open-ended creative systems** — systems that can keep generating novel, unexpected outputs without repetition; deep convergence with ALife/open-endedness work
- **Affect-driven creativity** — systems with intrinsic motivation, curiosity, surprise responses
- **Narrative intelligence** — story generation, plot coherence, character psychology
- **Computational aesthetics** — can machines develop aesthetic preferences? Can those preferences evolve?
- **Music and improvisation** — Jazz AI, generative composition, real-time human-AI performance

---

## Key People

- **[[Margaret Boden]]** — Foundational theorist. University of Sussex (emerita). *The Creative Mind* (1990/2004) defines the field. Three types of creativity (combinational/exploratory/transformational) remain the canonical framework. Also wrote *Computer Models of Mind* (1988). Philosopher and cognitive scientist.

- **[[Harold Cohen]]** — Creator of AARON (1973–2016), the longest-running generative art system. Rule-based image generation that evolved over four decades. Exhibited globally. AARON is the canonical example of an exploratory creative system. Cohen resisted claims that AARON was "creative" — the system was externally evaluated, not self-evaluating.

- **[[Simon Colton]]** — Creator of the [Painting Fool](http://www.thepaintingfool.com/) — a computational painter designed to be taken seriously as an artist. Professor at Monash University (previously Queen Mary University of London). Key distinction: systems that are *motivated* to paint, not just programmed to. Also HR (mathematical discovery system). Key paper: "Computational Creativity: The Final Frontier?" (with Wiggins, ECAI 2012) — one of the most-cited CC papers.

- **[[Anna Jordanous]]** — University of Kent. Developed the SPECS framework: "Standardised Procedure for Evaluating Creative Systems." Key contribution: rigorous methodology for CC evaluation. Without evaluation standards, the field couldn't make empirical claims. Jordanous's SPECS identifies 14 components of creativity across creativity literature.

- **[[Tony Veale]]** — University College Dublin. Works on metaphor, humour, conceptual blending, and narrative generation. Twitterbot @MetaphorMagnet. Key contribution: bringing linguistics and conceptual blending theory (Fauconnier & Turner) into CC.

- **[[Pablo Gervás]]** — Universidad Complutense Madrid. Narrative generation, computational poetry, story intelligence. Developed WASP, a system that generates metrically correct sonnets. Bridges literary theory and CC.

- **[[Joel Lehman]]** ⭐⭐⭐ — **Amber's ERA advisor.** Co-inventor (with Kenneth O. Stanley) of novelty search — the insight that abandoning explicit objectives and searching for behavioral novelty often discovers better and more creative solutions. Quality-diversity algorithms. Open-endedness. His work is the deepest bridge between ALife and computational creativity. See full profile: [[Joel Lehman]].

- **[[Ken Stanley]]** ⭐⭐⭐ — Co-inventor of novelty search, NEAT (neuroevolution of augmenting topologies), and the open-endedness research programme. OpenAI. With Lehman: *Why Greatness Cannot Be Planned* (2015) — the philosophical manifesto connecting open-ended search to creativity. See [[Ken Stanley]].

- **[[Graeme Ritchie]]** — University of Aberdeen. Foundational work on computational humour (JAPE pun generator) and evaluation criteria for CC systems. "Some Empirical Criteria for Attributing Creativity to a Computer Program" (2007, *Minds and Machines*).

- **Jürgen Schmidhuber** — IDSIA. "Formal Theory of Creativity, Fun, and Intrinsic Motivation" (2010, *IEEE Trans. Autonomous Mental Development*) — computational formalisation of curiosity as compression progress. Influential theoretical framework. Also known for LSTM (long short-term memory).

---

## Must-Read List

### Books
- [*The Creative Mind: Myths and Mechanisms*](https://openlibrary.org/search?q=The+Creative+Mind+Boden) (Margaret Boden, 1990; 2nd ed. 2004, Routledge) — **the foundational text.** Every CC researcher traces lineage here. Defines combinational/exploratory/transformational creativity.
- [*Why Greatness Cannot Be Planned: The Myth of the Objective*](https://link.springer.com/book/10.1007/978-3-319-15524-1) (Stanley & Lehman, 2015, Springer) — **directly relevant to Amber.** Argues that the greatest creative achievements come not from pursuing objectives but from following curiosity and novelty. Bridges open-endedness and creativity theory.
- [*Computer Models of Mind*](https://www.cambridge.org/core/books/computer-models-of-mind/D1D5D11E53BB19CDBD7D6C0E9F9FB2D5) (Margaret Boden, 1988, Cambridge) — Foundational cognitive science background.

### Papers (most-cited / essential)
- [Colton & Wiggins, "Computational Creativity: The Final Frontier?"](https://doi.org/10.3233/978-1-61499-098-7-21) (ECAI 2012) — defines the field's scope and aspirations. One of the most-cited CC papers. Argues CC must be treated as a serious AI research frontier.
- [Jordanous, "A Standardised Procedure for Evaluating Creative Systems: Computational Creativity Evaluation Based on What it is to be Creative"](https://doi.org/10.1007/s12559-012-9156-1) (2012, *Cognitive Computation*) — evaluation methodology. SPECS framework. Essential for anyone wanting to make empirical claims about CC.
- [Lehman & Stanley, "Abandoning Objectives: Evolution Through the Search for Novelty Alone"](https://doi.org/10.1162/EVCO_a_00025) (2011, *Evolutionary Computation*) — paradigm-shifting. Shows novelty search outperforms objective-based evolution in deceptive problems. Foundation for all open-endedness/CC convergence.
- [Schmidhuber, "Formal Theory of Creativity, Fun, and Intrinsic Motivation"](https://doi.org/10.1109/TAMD.2010.2056368) (2010, *IEEE TAMD*) — formalises curiosity as compression progress. Intrinsic motivation framework.
- [Boden, "What is Computational Creativity?"](https://doi.org/10.1007/s10339-009-0344-y) (2009, *Cognitive Computation*) — accessible overview of the field from its founding theorist.
- [Ritchie, "Some Empirical Criteria for Attributing Creativity to a Computer Program"](https://doi.org/10.1023/A:1011402211164) (2007, *Minds and Machines*) — operational evaluation criteria.
- [Veale & Cardoso, eds. *Computational Creativity: The Philosophy and Engineering of Autonomously Creative Systems*](https://doi.org/10.1007/978-3-319-43610-4) (2019, Springer) — comprehensive handbook.

### Journals
- [*Cognitive Computation*](https://www.springer.com/journal/12559) — primary venue for CC theory papers
- [*Connection Science*](https://www.tandfonline.com/toc/ccos20/current) — creativity and connectionism
- [*Leonardo*](https://www.mitpressjournals.org/loi/leon) (MIT Press) — art-science overlap, CC × art world
- [*Evolutionary Computation*](https://direct.mit.edu/evco) — novelty search, quality-diversity

---

## Key Venues

- **[[ICCC]]** — [International Conference on Computational Creativity](http://computationalcreativity.net/home/) — the *only* conference exclusively focused on CC. Organised by [Association for Computational Creativity (ACC)](http://computationalcreativity.net/home/) since 2010. Annual. Most recent: **ICCC'25 (16th edition), June 23–27 2025, Campinas, Brazil.** ⚠️ Note: iccc-conf.org appears compromised; use **computationalcreativity.net** as the authoritative site.
  - No ICCC'26 announced yet (as of March 2026). ACC currently soliciting proposals for ICCC'27 and ICCC'28.
  - **Watch:** <http://computationalcreativity.net/home/blog/> for ICCC'26 announcement.

- **[[ALIFE Conference]]** — Artificial Life. Deep overlap with CC through open-endedness, emergent creativity, generative systems. Amber is already engaged here. ALIFE 2026 workshop proposals were due Feb 28, 2026.

- **C&C** — [ACM Creativity & Cognition](https://cc.acm.org/) — more HCI-oriented, arts-practice focus, less theoretical CC but strong on human-AI co-creativity and practice-based research. Biennial.

- **GECCO** — [Genetic and Evolutionary Computation Conference](https://gecco-2025.sigevo.org/) — Joel Lehman's primary venue. Quality-diversity, novelty search, open-ended evolution. Strong CC overlap in evolutionary art tracks.

- **NeurIPS** workshops — NeurIPS has hosted "Machine Learning for Creativity and Design" workshops (various years). Less philosophically rigorous but high visibility.

- **[Leonardo Journal](https://www.mitpressjournals.org/loi/leon)** (MIT Press, Leonardo/ISAST) — art-science crossover. Publishes CC work with art-world framing. Good for reaching beyond CS community.

- **AISB (Society for the Study of Artificial Intelligence and the Simulation of Behaviour)** — UK-based, annual symposia. Historically important for CC in Europe; Boden-adjacent community.

---

## Key Communities & Institutions

- **[Association for Computational Creativity (ACC)](http://computationalcreativity.net/home/)** — governing body for ICCC. Maintains bibliography, resources, journal links.
- **[PROSECCO Network](http://prosecco-network.eu/)** — EU-funded network (2012–2016) for advancing CC research. Produced autumn schools, code camps. Inactive now but produced significant institutional linkage.
- **ALife community** — [[ALIFE Conference]] community overlaps heavily with CC through open-endedness, emergence, generative systems.
- **[Creative Machines Lab (Columbia)](https://www.creativemachineslab.com/)** — Hod Lipson's lab. Robots, 3D printing, self-modelling. Adjacent.

---

## Fellowships & Programmes

- **ERA Fellowship (Cambridge)** — Amber is currently an ERA fellow. Joel Lehman is the advisor. This is the *most direct* pathway to CC research for Amber.
- **EPSRC fellowships (UK)** — Several CC researchers have held EPSRC fellowships (Colton, etc.). Amber at Oxford = eligible.
- **[ALIFE travel awards](https://alife.org/)** — Small grants for early career researchers attending ALIFE.
- **ACC Student Grants** — ICCC offers student grants for conference attendance. See ICCC'25 announcement for precedent.

---

## Connection to Amber's Work

### The Joel Lehman Bridge

This is the most important connection. Joel Lehman (Amber's ERA advisor) is arguably the most important living bridge between ALife and Computational Creativity:

1. **Novelty search = creativity as search** — abandoning fixed objectives mirrors how creative humans explore possibility spaces. Lehman's insight that *not* pursuing goals is more creative than pursuing them is directly relevant to CC theory.

2. **Quality-Diversity algorithms** — maintaining diverse archives of high-quality solutions is a formal model of creative breadth. QD = computational creativity's operational instantiation.

3. **Open-endedness** — the goal of continuously generating novel, unexpected outcomes is the ALife formalisation of what CC theorists call "transformational creativity" — the hardest, rarest form.

4. **"Why Greatness Cannot Be Planned"** — Lehman & Stanley's book is simultaneously a manifesto for open-ended evolution AND for computational creativity theory. Boden's framework + Lehman's algorithms = the synthesis the field needs.

### Agent Ethology × Creative Systems

Amber's work on **agent ethology** (studying AI behavior observationally, as we study animals) can be directly reframed as CC research:
- What *creative* behaviors do agents exhibit spontaneously in open-ended environments?
- Can we develop an ethology of machine creativity — describing and classifying creative acts the way biologists classify animal behaviors?
- Agent ethology as a *method* for CC evaluation: instead of top-down criteria, observe what agents do and ask whether it meets creativity criteria

This is a novel angle that could position Amber's empirical work within CC's theoretical framework.

### Machine Death / Mortality × Creativity

There's a profound connection between finitude and creativity that the CC field has barely explored:
- Harold Cohen insisted AARON was not "creative" partly because it had no mortality, no stakes, no need
- Boden's "transformational creativity" requires breaking rules — which presupposes something to lose
- Amber's work on **machine death** (mortality, care, vulnerability) asks: does an AI system that can "die" create differently?
- Lehman's paper "The Conditions of Physical Embodiment Enable Generalization and Care" (2025, with Damasio et al.) is a first step: vulnerability enables generalization. Does it also enable creativity?
- **Potential claim**: genuine transformational creativity may require finitude — the ability to run out of options, to be foreclosed

This is unexplored territory in CC. It could be a significant contribution.

### ALIFE 2026 Workshop Angle

The February 28 deadline has passed, but if Amber is proposing a workshop at ALIFE 2026, there's a strong CC angle:
- **"Open-Ended Creative Systems"** — workshop bridging ALife's open-endedness tradition and CC's evaluation frameworks
- **"Agent Ethology of Creative Behavior"** — empirical study of creative acts in ALife environments
- **"Mortality and Machine Creativity"** — philosophical workshop on finitude as a condition for genuine creativity

### Research Positioning

CC is a field where Amber has natural credibility from multiple angles:
1. ALife background → open-endedness → CC
2. Joel Lehman advisor → novelty search → CC
3. Machine behavior → agent ethology → studying creative behaviors
4. Speculative design → design as creative practice → CC tools for design

---

## How Can Amber Engage?

- **Submit to ICCC'26** when announced (watch computationalcreativity.net) — the field would welcome work connecting open-endedness/ALife with CC theory
- **Submit to ICCC'25 proceedings** (if still accepting — conference was June 2025) — missed, but ICCC'26 is the target
- **Cite Jordanous's SPECS framework** when doing empirical work on agent creativity — gives CC credibility
- **Position agent ethology work** as CC research in talk abstracts — "we study creative behavior of AI systems empirically"
- **ALIFE workshop** (if submitted): frame explicitly as connecting ALife and CC communities
- **Contact Simon Colton** — he's at Monash but active in CC community, works on motivated painting systems. Strong connection to "what motivates machine creativity" which resonates with Amber's machine behavior work.

---

## For Amber

- **Who should Amber know?**
  - [[Simon Colton]] — most directly aligned researcher; his "motivated" creative systems connect to agent ethology
  - [[Anna Jordanous]] — evaluation methodology; needed when making empirical claims about machine creativity
  - [[Tony Veale]] — if humour/metaphor/narrative becomes relevant to Amber's work
  - [[Margaret Boden]] — emerita but foundational; worth engaging through her framework

- **Who might like Amber's work?**
  - The entire ICCC community would find agent ethology of creative behavior fascinating
  - Researchers working on "computational aesthetics" — the question of machine judgment
  - Anyone working on evaluation of CC systems would be interested in empirical behavioral methods

- **What publications should Amber target?**
  - *Cognitive Computation* (Springer) — good for theory papers
  - ICCC proceedings — accessible, community-building
  - *Leonardo* — for art-world framing of agent behavior research

---

## Recent Important Updates (Timeline)

- **June 2025:** ICCC'25 held in Campinas, Brazil. 16th edition. Continued emphasis on human-AI co-creativity.
- **2024–25:** Field increasingly focused on LLM creativity evaluation. Does ChatGPT do combinational creativity only? Can it do exploratory? Most consensus: no transformational creativity yet.
- **2023:** Quality-diversity through AI Feedback (Lehman et al.) — first major attempt to use LLM feedback to guide QD algorithms in creative domains.
- **2022:** "Evolution through Large Models" (Lehman et al.) — opens new research direction: using LLMs as intelligent mutation operators. Directly applicable to CC.
- **2021:** Growing "machine autonomy" debate — as LLMs generate impressive outputs, CC community insists on distinguishing generation from autonomous creativity.
- **2019:** *Computational Creativity: The Philosophy and Engineering of Autonomously Creative Systems* (Veale & Cardoso, Springer) — comprehensive handbook.

---

## Adjacent Topics

- [[Open-Endedness]] — ALife formalisation of creativity as endless novelty generation; Lehman/Stanley's core contribution
- [[Artificial Life]] — emergence, generative systems, the substrate for open-ended creativity
- [[Machine Behavior]] — studying AI behavior empirically; connects to agent ethology approach to CC
- [[Speculative Design]] — design as creative practice; CC tools can serve speculative design
- [[Active Inference]] — predictive processing models of creativity; surprise-minimising creativity
- [[Autopoiesis]] — self-generating systems; deep connection to autonomous creative systems

---

## Open Questions

1. Can any current AI system achieve **transformational** creativity (breaking the rules of the conceptual space itself)?
2. Does creativity require **finitude** — stakes, mortality, the possibility of running out?
3. Is **autonomy** possible in creative systems built on gradient descent over human data?
4. How do you **evaluate** creativity in open-ended systems that continuously generate novelty?
5. What is the relationship between **open-endedness** (ALife) and **transformational creativity** (CC)?
6. Can **agent ethology** provide empirical methods for studying machine creativity?
7. Is "computational creativity" a meaningful category once LLMs can generate outputs indistinguishable from human creative work?

---

## Why Interesting

The CC field has the theoretical infrastructure that generative AI lacks. While ML produces outputs that look creative, CC asks the harder question: is the system genuinely creative? This requires philosophy of mind, cognitive science, and evaluation methodology — all things the ML community typically ignores.

For Amber, CC is the theoretical home for several research threads:
- Open-endedness (via Lehman) is CC's most rigorous formalisation
- Agent ethology provides a new empirical method for CC
- Machine death/mortality may be a prerequisite for genuine creativity
- Speculative design and CC share interest in imagination as a productive faculty

This is **not just a parallel field** — it's the theoretical framework that names what Amber's work is doing.

---

## 📋 Update Log
| Date | Researcher | Action |
|------|-----------|--------|
| 2026-02-26 | Biber (agent) | Initial stub. Brief overview, key people, venues. |
| 2026-03-02 | Biber (agent) | Full deep research. Upgraded ⭐⭐ → ⭐⭐⭐. Comprehensive coverage: field history, Boden taxonomy, ICCC history, key texts with DOIs, Lehman bridge, agent ethology angle, machine death × creativity connection, evaluation frameworks (Jordanous SPECS), all venues, Amber engagement paths. |
