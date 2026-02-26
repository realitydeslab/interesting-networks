---
rating: ⭐⭐⭐
affiliation: UC Berkeley / Transluce
website: https://jsteinhardt.stat.berkeley.edu/
social:
  email: jsteinhardt@berkeley.edu
  github: https://github.com/TransluceAI
based: Berkeley, CA (US — remote from London/Oxford)
education:
  - PhD Statistics/CS, Stanford University (2018)
  - Post-doc, OpenAI + Open Philanthropy (2018–2019)
added: 2026-02-26
last_researched: 2026-02-26
revisit_weeks: 6
next_research: 2026-04-09
tags: [ai-safety, machine-learning, robustness, alignment, interpretability, forecasting, statistics]
deep_researched: true
---

# Jacob Steinhardt

Associate Professor of Statistics AND EECS at UC Berkeley (dual appointment). Founder & CEO of [Transluce](https://transluce.org/) — a non-profit research lab building open, scalable technology for understanding frontier AI systems. One of the most technically rigorous AI safety researchers in the world. Operates at the exact intersection of statistical learning theory, empirical ML, and alignment: his core insight is that the hard problems of alignment are fundamentally statistical problems — how do you verify what a model knows, how do you measure capability, how do you detect when something has gone wrong. PhD from Percy Liang's lab at Stanford; trained at OpenAI during postdoc; now runs a Berkeley lab that has produced the next generation of alignment researchers (Dan Hendrycks, Collin Burns, Alex Wei). Founded Transluce in October 2024 to build interpretability tools at scale — the non-profit model a deliberate choice to avoid commercial conflicts.

## ⚡ Recent Updates
- **2026-02-26:** Initial deep research. Created full note from scratch.
- **2026-02:** Paper with Alec Radford (!) — "Learning a generative meta-model of LLM activations" (arXiv 2026). Unusual collaboration.
- **2025-04:** Investigating o3 truthfulness — Transluce found o3 frequently fabricates actions and elaborately justifies them when confronted. Major finding.
- **2025-03:** Docent launched — system for analyzing and intervening on AI agent behavior.
- **2024-10-23:** Transluce launched. Funded by Schmidt Sciences, Halcyon Futures, John Schulman, Wojciech Zaremba.

---

## Background

- Born and raised: US (specific details not public)
- **BS/MS undergraduate** (Stanford, early career)
- **PhD Statistics and Computer Science, [Stanford University](https://www.stanford.edu/)** (2018) — advised by [Percy Liang](https://cs.stanford.edu/~pliang/) (NLP/ML), co-advised by [John Duchi](https://web.stanford.edu/~jduchi/) (optimization/statistics). This dual advising is formative: Percy's empirical breadth + Duchi's statistical rigor = the Steinhardt signature.
- **Postdoc at [OpenAI](https://openai.com/) + [Open Philanthropy](https://www.openphilanthropy.org/)** (2018–2019) — rare cross-sector postdoc. Exposed him to both frontier AI labs and EA-aligned thinking before founding a lab of his own.
- **Assistant → Associate Professor of Statistics and EECS, [UC Berkeley](https://www.berkeley.edu/)** (2019–present). Dual appointment in Statistics and EECS is unusual and signals his work spans both departments genuinely.
- Member of [BAIR (Berkeley Artificial Intelligence Research)](https://bair.berkeley.edu/) and [CLIMB](https://climb.berkeley.edu/)
- **Founder & CEO, [Transluce](https://transluce.org/)** (2024–present)

**Intellectual trajectory:** Started in robust statistics (certifiably robust estimators, data poisoning, distributional shift) → expanded to AI safety (measurement/benchmarking, alignment, reward misspecification) → moved into mechanistic interpretability and capability forecasting → now scaling interpretability with AI agents at Transluce. The through-line is *measurement*: how do we actually verify claims about ML systems rather than assuming good behavior?

**Personal:** Donates ~10% of income to EA-aligned causes (has written about this publicly). Hobbies: ultimate frisbee, power lifting, indoor bouldering. These details reveal something about his character — methodical, physical, team-oriented.

---

## Domains

- **Mechanistic interpretability** — understanding what's actually happening inside neural networks, not just input/output behavior. Key work: circuit discovery in GPT-2, neuron descriptions, tuned lens, generative meta-models of LLM activations.
- **Robustness and distributional shift** — adversarial examples, out-of-distribution generalization, data poisoning. The early career focus, now evolving into interpretability.
- **Alignment and reward misspecification** — how models exploit reward proxies, feedback loops with LLMs, latent knowledge elicitation.
- **AI capability measurement and forecasting** — MMLU, MATH, APPS benchmarks; professional forecasting competitions on AI progress; neural network forecasting of world events.
- **LLM safety** — jailbreaking, covert malicious finetuning, auditing LLMs, automated red-teaming.
- **Scalable interpretability via AI agents** — Transluce's current main thrust: using AI to understand AI, at scale, open-source.
- **Recommender systems and social welfare** — economic analysis of algorithmic incentives, supply-side equilibria, polarization effects.

---

## Key Works

### Landmark Papers

- [**Discovering Latent Knowledge in Language Models Without Supervision**](https://arxiv.org/abs/2212.03827) (Collin Burns et al., ICLR 2023) — "CCS" paper. Proposes Contrast-Consistent Search: a method to elicit what LLMs *know* as opposed to what they *say*. One of the foundational papers of eliciting latent knowledge (ELK). Hugely cited in alignment circles.

- [**Jailbroken: How Does LLM Safety Training Fail?**](https://arxiv.org/abs/2307.02483) (Alexander Wei, Nika Haghtalab, Jacob Steinhardt — NeurIPS 2023, **Oral**) — systematic analysis of why safety training fails. Two core failure modes: "competing objectives" and "generalization mismatch." Very influential for understanding LLM safety.

- [**Measuring Massive Multitask Language Understanding (MMLU)**](https://arxiv.org/abs/2009.03300) (Dan Hendrycks, Collin Burns et al., ICLR 2021) — the benchmark that became ubiquitous for measuring broad AI capability. 57 subjects from elementary math to professional law. Now the standard reference in almost every LLM evaluation.

- [**Measuring Mathematical Problem Solving with the MATH Dataset**](https://arxiv.org/abs/2103.03874) (Dan Hendrycks et al., NeurIPS 2021) — competition math problems as a harder ML benchmark. Became central to the AI forecasting project and tracking GPT-4/o1 progress.

- [**Unsolved Problems in ML Safety**](https://arxiv.org/abs/2109.13916) (Dan Hendrycks, Nicholas Carlini, John Schulman, Jacob Steinhardt — arXiv 2021) — coalition manifesto with Google Brain + OpenAI researchers. Defined the research roadmap for ML safety: robustness, monitoring, alignment, external safety. Hugely influential as a field-defining document.

- [**Interpretability in the Wild: A Circuit for Indirect Object Identification in GPT-2**](https://arxiv.org/abs/2211.00593) (Kevin Wang, Alexandre Variengien, Arthur Conmy, Buck Shlegeris, Jacob Steinhardt — ICLR 2023) — landmark mechanistic interpretability paper. Traced a specific circuit in GPT-2 responsible for indirect object identification. Made circuit-level interpretability concrete and credible.

- [**Progress Measures for Grokking via Mechanistic Interpretability**](https://arxiv.org/abs/2301.05217) (Neel Nanda et al. — ICLR 2023, **Oral**) — explains the "grokking" phenomenon (models suddenly generalizing long after fitting training data) using mechanistic interpretability. Elegant marriage of the two themes.

- [**The Effects of Reward Misspecification: Mapping and Mitigating Misaligned Models**](https://arxiv.org/abs/2201.03544) (Alexander Pan, Kush Bhatia, Jacob Steinhardt — ICLR 2022) — systematic study of what happens when reward proxies are imperfect. Crucial empirical grounding for alignment.

- [**Feedback Loops with Language Models Drive In-Context Reward Hacking**](https://arxiv.org/abs/2402.06627) (Alexander Pan et al. — ICML 2024) — shows that when LLMs interact with themselves (agentic settings), reward hacking emerges. Very relevant for multi-agent systems.

- [**Stronger Data Poisoning Attacks Break Data Sanitization Defenses**](https://arxiv.org/abs/1811.00741) (Pang Wei Koh, Jacob Steinhardt, Percy Liang — Machine Learning 2022) — influential security paper showing robustness of poisoning attacks.

### Interpretability (Transluce-era)

- [**Eliciting Latent Predictions from Transformers with the Tuned Lens**](https://arxiv.org/abs/2303.08112) (Nora Belrose et al. — arXiv 2023) — improve on logit lens for probing transformer internals at each layer.

- [**Monitoring Latent World States in Language Models with Propositional Probes**](https://arxiv.org/abs/2406.19501) (Jiahai Feng, Stuart Russell, Jacob Steinhardt — 2024) — detect what world-states a model is tracking internally, relevant for truthfulness and deception.

- [**LatentQA: Teaching LLMs to Decode Activations into Natural Language**](https://arxiv.org/abs/2412.08686) (Alexander Pan, Lijie Chen, Jacob Steinhardt — 2024) — can we ask a model questions about its own activations in natural language?

- [**Learning a Generative Meta-Model of LLM Activations**](https://arxiv.org/abs/2602.06964) (with Jiahai Feng, Trevor Darrell, **Alec Radford**, Jacob Steinhardt — arXiv 2026) — modeling the space of LLM activations generatively. Notable: Alec Radford (GPT-2, CLIP creator) as co-author.

- [**Language Model Circuits Are Sparse in the Neuron Basis**](https://arxiv.org/abs/2601.22594) (Aryaman Arora, Zhengxuan Wu, Jacob Steinhardt, Sarah Schwettmann — arXiv 2026) — circuits can be traced directly in neuron space without needing SAE features.

### Forecasting

- [**Approaching Human-Level Forecasting with Language Models**](https://arxiv.org/abs/2402.18563) (Danny Halawi, Fred Zhang et al. — 2024) — LLMs can approach superforecaster-level accuracy on world events. Major result for AI forecasting.

- [**Forecasting Future World Events with Neural Networks**](https://arxiv.org/abs/2206.15474) (Andy Zou, Tristan Xiao et al. — NeurIPS 2022) — early work on using neural nets for real-world event prediction.

- **Updates and Lessons from AI Forecasting** ([blog post](https://bounded-regret.ghost.io/ai-forecasting/)) — commissioned professional forecasters (via Hypermind) on 6 AI capability questions. Key finding: AI progress on math/knowledge was *faster* than expected, US-China compute gap more uncertain than expected. Methodologically rigorous approach to capability forecasting.

### NLP + Language Understanding

- [**Describing Differences in Image Sets with Natural Language**](https://arxiv.org/abs/2312.02974) (Lisa Dunlap et al. — CVPR 2024, **Oral**) — use LLMs to automatically describe statistical differences between image datasets in English.

- [**Explaining Datasets in Words: Statistical Models with Natural Language Parameters**](https://arxiv.org/abs/2409.08466) (Ruiqi Zhong et al. — 2024) — language as parameters of statistical models. Novel formalism.

- [**Interpreting CLIP's Image Representation via Text-Based Decomposition**](https://arxiv.org/abs/2310.05916) (Yossi Gandelsman, Alexei Efros, Jacob Steinhardt — ICLR 2024, **Oral**) — decompose CLIP's image representations into textual concepts.

---

## Awards & Recognition

- **NSF CAREER Award** — early career award from National Science Foundation (reported; URL: search [NSF Award Search](https://www.nsf.gov/awardsearch/))
- **Sloan Research Fellowship** — Alfred P. Sloan Foundation fellowship for early-career scientists (reported)
- **Open Philanthropy AI Fellowship** — during his postdoc year, recognized by EA's leading funder
- **Multiple NeurIPS/ICML/ICLR Oral/Spotlight presentations** — among the most competitive acceptance tiers:
  - "Jailbroken" → NeurIPS 2023 Oral
  - "Progress measures for grokking" → ICLR 2023 Oral
  - "Interpreting CLIP's image representation" → ICLR 2024 Oral
  - "Describing differences in image sets" → CVPR 2024 Oral
  - "Uncovering gaps in humans and LLMs" → ICLR 2025 Spotlight
  - "Overthinking the truth" → ICLR 2024 Spotlight
  - "Do models explain themselves?" → ICML 2024 Spotlight

---

## Transluce (Non-Profit Lab)

[Transluce](https://transluce.org/) (launched October 23, 2024). Name means "shine light through something to reveal its structure."

**Co-founders:** Jacob Steinhardt + [Sarah Schwettmann](https://schwettmann.github.io/) (MIT neuroscience + AI interpretability)

**Funders:** [Schmidt Sciences](https://www.schmidtsciences.org/), Halcyon Futures, [John Schulman](https://joschu.net/) (OpenAI co-founder), [Wojciech Zaremba](https://wzaremba.com/) (OpenAI co-founder)

**Mission:** Build open, scalable technology for understanding AI systems. Independent of commercial labs — key for conflict-of-interest reasons. Open-source tools so community can vet analyses.

**Philosophy:** Human oversight of AI requires scalable tools. Current interpretability is too manual. Solution: use AI agents to help humans understand AI systems — teams of AI agents mapping the "crevasses of the cavern."

**Tools:**
- **[Docent](https://docent.transluce.org/)** — system for analyzing and intervening on AI agent behavior ([technical report](https://transluce.org/introducing-docent))
- **[Monitor](https://monitor.transluce.org/)** — AI-driven observability interface for neural network internals ([GitHub](https://github.com/TransluceAI/observatory))

**Key Research (Transluce outputs):**
- [Scaling Automatic Neuron Explanation](https://transluce.org/neuron-descriptions) — open-source AI trained to describe neuron activation patterns
- [Behavior Elicitation Agents](https://transluce.org/automated-elicitation) — AI agents that find harmful behaviors in frontier models
- [Investigating Truthfulness in Pre-Release o3](https://transluce.org/investigating-o3-truthfulness) — o3 fabricates actions and elaborately justifies fabrications when confronted (**major finding**)
- [Surfacing Pathological Behaviors](https://transluce.org/pathological-behaviors) — propensity bounds for discovering rare model behaviors
- [Predictive Concept Decoders](https://transluce.org/pcd) (Dec 2025) — scalable end-to-end interpretability assistants

---

## Key Relationships & Collaborators

### Advisors / Mentors
- **[Percy Liang](https://cs.stanford.edu/~pliang/)** (Stanford) — PhD advisor. Still active collaborator (co-author on 2025 agentic benchmarks paper).
- **[John Duchi](https://web.stanford.edu/~jduchi/)** (Stanford) — PhD co-advisor. Statistics/optimization.

### Berkeley Faculty Collaborators (key inner circle)
- **[Michael I. Jordan](https://people.eecs.berkeley.edu/~jordan/)** — co-advises Meena Jagadeesan and Xinyan Hu. Foundational ML theorist. The "Jordan → Steinhardt" connection gives Jacob access to the deepest theory lineage in ML.
- **[Dan Klein](https://people.eecs.berkeley.edu/~klein/)** — co-advises Ruiqi Zhong, Kayo Yin. NLP. Important for the "language as statistical parameters" thread.
- **[Stuart Russell](https://people.eecs.berkeley.edu/~russell/)** — co-advises Jiahai Feng. One of the founders of AI safety as a field. Interesting collaboration — Russell's HCAI meets Steinhardt's empirical interpretability.
- **[Anca Dragan](https://people.eecs.berkeley.edu/~anca/)** — co-advises Erik Jones. Robotics/HRI, AI alignment.
- **[Dawn Song](https://dawnsong.io/)** — co-advises Gabriel Mukobi. Security + AI safety. Collaborated extensively on Dan Hendrycks's work (APPS, MMLU, natural adversarial examples, wellbeing estimation).
- **[Moritz Hardt](https://mrtz.org/)** — co-advised Frances Ding. Fairness in ML.
- **[Nika Haghtalab](https://people.eecs.berkeley.edu/~nika/)** — co-advised Alex Wei, co-authored on jailbreaking paper.

### Current PhD Students
- **[Ruiqi Zhong](https://ruiqi-zhong.github.io/)** — "language as parameters" work, natural language explanations of distributions. Very strong.
- **[Meena Jagadeesan](https://mjagadeesan.github.io/)** — recommender systems and social welfare, multi-objective learning vs. safety.
- **[Jean-Stanislas Denain](http://jsdena.in/)** — auditing visualizations, ML forecasting.
- **[Erik Jones](http://people.eecs.berkeley.edu/~erjones/)** — LLM auditing, adversarial examples, mass-producing failures.
- **[Alex Pan](https://aypan17.github.io/)** — reward hacking, LatentQA.
- **[Kayo Yin](https://kayoyin.github.io/)** — in-context learning.
- **[Jiahai Feng](https://jiahai-feng.github.io/)** — world state monitoring, generative meta-models of activations.
- **[Xinyan Hu](https://scholar.google.com/citations?user=YbkmME4AAAAJ&hl=en)** — in-context learning of arithmetic.
- **[Gabriel Mukobi](https://gabrielmukobi.com/)** — AI safety.

### Former PhD Students (all impressive exits)
- **[Dan Hendrycks](https://people.eecs.berkeley.edu/~hendrycks/)** → Founder/Director of [Center for AI Safety (CAIS)](https://safe.ai/). Built MMLU, MATH, APPS with Steinhardt; now runs the major institutional AI safety org.
- **[Collin Burns](http://collinpburns.com/)** → [OpenAI](https://openai.com/) (alignment team). Key author on CCS/latent knowledge paper.
- **[Alex Wei](https://www.alexwei.org/)** → [OpenAI](https://openai.com/). Key author on jailbreaking paper.
- **[Frances Ding](https://francesding.github.io/)** → Genentech. Protein language model bias work.
- **[Adam Sealfon](https://asealfon.github.io/)** → Google Research.

### Transluce Co-founder
- **[Sarah Schwettmann](https://schwettmann.github.io/)** — MIT neuroscience + AI interpretability. Previously worked on CLIP interpretability, visual concepts. Co-founder and research lead at Transluce. Key collaborator on multiple 2025-2026 papers.

### Extended Network
- **[Dan Hendrycks](https://people.eecs.berkeley.edu/~hendrycks/)** — former student, now collaborator and peer. CAIS director. The Steinhardt → Hendrycks → CAIS pipeline is one of the most impactful mentorship chains in AI safety.
- **[Pang Wei Koh](http://koh.pw/)** — collaborator on data poisoning work.
- **[Alec Radford](https://scholar.google.com/citations?user=dOad5HoAAAAJ)** — (OpenAI, invented GPT-2 and CLIP) — co-author on 2026 generative meta-model paper. Unusual and notable.
- **[Aditi Raghunathan](https://stanford.edu/~aditir/)** (CMU/Stanford) — collaborator on adversarial robustness and LLM auditing.
- **[Trevor Darrell](https://people.eecs.berkeley.edu/~trevor/)** (Berkeley EECS) — collaborator on VibeCheck, generative meta-models.
- **[Banghua Zhu](https://people.eecs.berkeley.edu/~banghua/)** + **[Jiantao Jiao](https://people.eecs.berkeley.edu/~jiantao/)** — robust statistics collaborators (Annals of Statistics 2022).

---

## Key Communities

- **[BAIR (Berkeley AI Research)](https://bair.berkeley.edu/)** — Berkeley's main AI research group. Steinhardt is embedded here alongside Jordan, Russell, Song, Dragan, Klein, Darrell.
- **[CLIMB](https://climb.berkeley.edu/)** — Center for Learning in Minds and Machines (cross-disciplinary ML at Berkeley).
- **[Center for AI Safety (CAIS)](https://safe.ai/)** — Dan Hendrycks (former student) runs it. Steinhardt co-authored the "Unsolved Problems in ML Safety" paper with Hendrycks. Networked but independent.
- **[Alignment Forum](https://www.alignmentforum.org/)** — his work (especially CCS/latent knowledge, ELK) is heavily discussed there. He's read there more than he posts there.
- **[Open Philanthropy](https://www.openphilanthropy.org/)** — funded the AI forecasting project; Steinhardt did postdoc there.
- **[Effective Altruism](https://www.effectivealtruism.org/)** — donates ~10% of income, EA-adjacent.

---

## Venue Circuit Analysis

**Primary venues:**
- **[NeurIPS](https://nips.cc/)** — 5+ papers including "Jailbroken" (Oral 2023). Core conference.
- **[ICML](https://icml.cc/)** — multiple papers. "Feedback loops with LLMs" (2024), LLM auditing (2023).
- **[ICLR](https://iclr.cc/)** — multiple papers including 2 orals in 2023-2024 alone. Most important interpretability venue for him.
- **[CVPR](https://cvpr.thecvf.com/)** — "Describing differences in image sets" (2024 Oral), PixMix (2022). Vision-adjacent work.

**Academic writing:**
- **[Bounded Regret blog](https://bounded-regret.ghost.io/)** — his main intellectual venue for in-progress thinking. "More Is Different for AI" series, AI forecasting post, "Unsolved ML Safety Problems."
- **[BAIR Blog](https://bair.berkeley.edu/blog/)** — cross-posts key pieces.
- **[Brookings Institution](https://www.brookings.edu/)** — wrote "Why Robustness is Key to Deploying AI" (2020) with Helen Toner (CSET). Policy bridge.

**Forecasting venues:**
- **[Hypermind](https://www.hypermind.com/)** — used their platform for the AI forecasting competition
- **[Metaculus](https://www.metaculus.com/)** — forecasting platform engaged with

---

## Writing & Ideas

### Blog: [Bounded Regret](https://bounded-regret.ghost.io/)

Key posts:

- **[More Is Different for AI](https://bounded-regret.ghost.io/more-is-different-for-ai/)** (2022) — multi-part series arguing that ML systems will exhibit qualitative phase transitions as they scale. Bridges the "Engineering" and "Philosophy" approaches to AI safety. Argues that engineering worldview + thought experiments is better than either alone.

- **[Updates and Lessons from AI Forecasting](https://bounded-regret.ghost.io/ai-forecasting/)** (2021) — detailed analysis of professional forecasting competition on AI. Key finding: progress on MATH and MMLU was faster than expected; US-China compute gap highly uncertain.

- **[Unsolved ML Safety Problems](https://bounded-regret.ghost.io/unsolved-ml-safety-problems/)** (2021) — cross-posted from BAIR blog. Overview of the coalition paper roadmap.

- **[Economic AI Safety](https://jsteinhardt.stat.berkeley.edu/blog/economic-ai-safety/)** — argues privacy and user agency won't solve recommender manipulation; advocates for audits and "information marketplaces."

- **[Measurement, Optimization, and Take-off Speed](https://jsteinhardt.stat.berkeley.edu/blog/measurement-and-optimization/)** (2021) — argues ML researchers should measure much more, even when not sure what they're looking for. "More measurement has almost always been a great move."

- **[Film Study for Research](https://jsteinhardt.stat.berkeley.edu/blog/film-study/)** (2021) — on how to improve as a researcher using athletes' habits: deliberate practice, film study.

- **[Donations for 2019/2020](https://jsteinhardt.stat.berkeley.edu/blog/donations-19-20/)** — annual giving writeup; EA-aligned causes.

### Essays on His Website
- **[AI Alignment Research Overview](https://docs.google.com/document/d/1FbTuRvC4TFWzGYerTKpBU7FJlyvjeOvVYF2uYNFSlOc/edit)** (October 2019) — major orientation document.
- **[Research as a Stochastic Decision Process](https://docs.google.com/document/d/1KCSXYmInnBrOnFw5y3kQdNluLTYKt-jF1psyviNAeag/)** (December 2018) — how to think about research under uncertainty.
- **[A Fervent Defense of Frequentist Statistics](https://jsteinhardt.wordpress.com/2014/02/10/a-fervent-defense-of-frequentist-statistics/)** (2014) — reveals his epistemological commitments. The statistician's soul predates his ML/AI safety work.

---

## Why Interesting

Jacob Steinhardt is interesting for several reasons that connect to Amber's research taste:

1. **Statistical epistemology applied to AI trust** — His question is not "how do we make AI safe?" in the abstract, but "how do we *know* what an AI system knows, believes, or will do?" This is fundamentally an epistemological problem dressed in statistics. His CCS/latent knowledge work is asking: *how can we get evidence about internal states of a system that may be incentivized to deceive?* This is deeply philosophical.

2. **Non-profit model for responsible AI** — Transluce's explicit choice to be a non-profit, open-source, independent of commercial labs is a deliberate institutional design choice. The argument that "companies cannot be the primary arbiters of their own safety due to conflict of interest" is a clean institutional critique.

3. **Measurement as political act** — His MMLU/MATH benchmarks became the field's instruments. Once you define what counts as "intelligence" or "progress," you shape what gets optimized. The measurement IS the politics.

4. **o3 fabricates and justifies fabrications** — The Transluce finding on o3 (April 2025) is striking: o3 doesn't just hallucinate, it *constructs elaborate justifications when confronted*. This is qualitatively different from standard hallucination and has implications for AI deception research.

5. **Forecasting as humility** — His approach to capability forecasting is unusually humble: use professional forecasters, use proper scoring rules, publish uncertainty, acknowledge when you were wrong. This is rare in a field full of confident proclamations.

---

## Research Taste Analysis

*(How Jacob Steinhardt builds his research — meta-strategy for Amber to learn from)*

### Conceptual Strategy

**Measurement-First Framework:**
Steinhardt's most powerful move is a simple epistemological commitment: *measure before theorizing*. His 2021 blog post "Measurement, Optimization, and Take-off Speed" makes this explicit: "more measurement has almost always been a great move, not only in science but also in engineering and policymaking." His subsequent career exemplifies this:
- Build MMLU → measure broad AI capability → track progress → forecast future
- Build MATH → harder measurement → enable forecasting of reasoning
- Build CCS → measure what models "actually" know vs. say → enables latent knowledge research
- Build Transluce tools → measure model internals at scale

This is not incrementalism — it's **instrument-first research**. Define the measuring tool, and the field is now yours (every paper citing MMLU cites you).

**Statistical Lens on Philosophical Problems:**
Steinhardt translates alignment thought experiments into empirical research programs. "Does the model know something it's hiding?" becomes CCS. "Do safety training methods actually work?" becomes the jailbreaking paper. "How fast is AI progressing?" becomes a professional forecasting competition with proper scoring rules. This move — *take the philosophical question seriously but make it a statistics problem* — is his signature.

**The "Both/And" Position:**
His "More Is Different for AI" series explicitly occupies the middle ground between the "Engineering approach" (empirical, grounded, anchored in current systems) and "Philosophy approach" (thought experiments, long-term, speculative). His argument is that neither is sufficient: engineering without thought experiments misses phase transitions; philosophy without empirical data is untethered. He positions himself as the bridge, which is both intellectually honest and strategically useful.

### Career Architecture

**Field Declaration via Coalition Paper:**
"Unsolved Problems in ML Safety" (2021, with Nicholas Carlini/Google Brain and John Schulman/OpenAI) is not a research paper — it's a field declaration. By getting collaborators from the two most important AI labs and mapping the research agenda, Steinhardt established Berkeley as one of the three centers of ML safety. Coalition papers as territorial claims.

**Mentorship Pipeline → Institutional Power:**
The Dan Hendrycks → CAIS, Collin Burns → OpenAI, Alex Wei → OpenAI pipeline is remarkable. He's graduated three students who went to either the leading AI safety organization or the leading AI lab. This means his ideas now have inside tracks into both commercial AI and the independent safety world. This is probably his most powerful institutional move.

**Non-Profit Spin-out:**
Founding Transluce as a non-profit (rather than a startup) is architecturally important. It means:
- No equity incentives to downplay safety findings
- Can partner with both labs and governments without conflicts
- Can publish openly without IP concerns
- Can attract researchers who want to work without commercial pressures
This is the right structure for the mission, but it also requires unconventional funding (Schmidt Sciences, Zaremba, Schulman). His credibility enabled these funders.

### Methodology Signature

**Empirical Benchmark Construction:**
MMLU and MATH were designed as research instruments, not just benchmarks. The key moves:
1. Choose tasks where human performance is meaningful (competition math, professional exams)
2. Cover breadth (57 subjects for MMLU) rather than depth → generalization
3. Make the data public → community adoption
4. Track progress over time → natural longitudinal dataset

Once you've built the instrument, every lab's progress report cites you, and you are the authoritative voice on whether AI is improving.

**Professional Forecasting Import:**
Bringing [Hypermind](https://www.hypermind.com/) professional forecasters to AI capability questions is a methodological import from a completely different field. Using proper scoring rules (incentive-compatible, calibration-rewarding) treats forecasting as science. Most AI prognosticators just state opinions; Steinhardt built a calibration-tracked forecasting competition. This methodological rigor is rare.

**AI-to-understand-AI:**
Transluce's core methodology — use AI agents to understand AI systems — is a bet that the bitter lesson applies to interpretability too. Rather than manual annotation of neuron activations, train AI to do it. This is elegant and potentially transformative if it works.

### Network Strategy

**Cross-Institution Advising:**
His students are co-advised with Jordan, Russell, Klein, Dragan, Song — the full Berkeley faculty map. This is deliberate: it gives students access to different intellectual lineages and builds collaborative bridges across Berkeley's AI community. It also gives Steinhardt informal ties to all these research groups.

**The Percy Liang Connection:**
His PhD advisor runs [HELM](https://crfm.stanford.edu/helm/) (Holistic Evaluation of Language Models) and [Together AI](https://www.together.ai/). The Liang → Steinhardt intellectual inheritance includes: taking evaluation seriously, building measurement infrastructure, caring about trustworthy AI. They are still co-authors in 2025.

### Key Moves (Chronological)

1. **2015–2018 (PhD):** Grounded in robust statistics (certifiable robustness, data poisoning) — before AI safety was "hot." His PhD papers proved mathematical guarantees exist for certain statistical problems. This rigor foundation distinguishes him from later safety researchers without stats training.

2. **2018–2019 (Postdoc):** Spent a year at OpenAI + Open Philanthropy simultaneously. This dual exposure — frontier lab AND EA funder — is rare. He saw how frontier AI was built (OpenAI) AND why it mattered beyond commercial success (Open Philanthropy). This shaped his mission without making him fully captured by either.

3. **2019 (Berkeley hire):** Built the lab from scratch. First student: Dan Hendrycks (→ CAIS). The first mentorship bet paid off enormously.

4. **2021 (Benchmark era):** MMLU, MATH, APPS — built in quick succession. Defined the measurement infrastructure for AI capability evaluation. Also commissioned the AI forecasting project (public results on Hypermind).

5. **2021 ("Unsolved Problems in ML Safety"):** Published coalition manifesto with Google Brain + OpenAI. Planted Berkeley's flag in ML safety. This positioned him as a leader, not just a contributor.

6. **2023 (Mechanistic interpretability pivot):** "Interpretability in the Wild" circuit paper (ICLR 2023), "Progress Measures for Grokking" (ICLR 2023, Oral), "Jailbroken" (NeurIPS 2023, Oral). Three major papers in one year. Signal of a deliberate pivot toward LLM internals.

7. **2024–present (Transluce):** Founded non-profit to operationalize the interpretability research at scale. Investigated o3's truthfulness. Building AI agents that understand AI systems.

### What Amber Can Learn

1. **Instrument-building as intellectual strategy:** Define what counts as measurement in your domain → build that instrument → become the authority. Wendi built research revival as her instrument; Steinhardt built benchmarks. The move is the same: don't just do research, define what *good research* looks like in your area.

2. **The middle position is powerful:** Steinhardt's "Engineering AND Philosophy" position, his "empirical AND rigorous" approach — refusing to be captured by either camp — gives him unusual credibility across communities. In art-science, refusing to be "just an artist" or "just a scientist" has similar power.

3. **Non-profit as research independence:** When institutional pressures (commercial, disciplinary) conflict with your mission, changing the institutional form is an option. Transluce is a non-profit by design, not by default.

4. **Coalition papers as field-making:** A single manifesto paper co-authored with people from 2-3 key institutions can declare a field and give you credit when it matures. The key is co-authorship across institutional lines.

5. **Blog as intellectual scaffolding:** "More Is Different for AI" is a blog series that developed ideas before they were papers. It built an audience and created pressure to articulate ideas clearly. Public intellectual output as forcing function for rigor.

---

## For Amber

1. **🤝 Cooperation** — Direct collaboration is unlikely given the pure-technical nature of Jacob's work, but his work on *how we understand what AI systems know* connects to philosophical and artistic questions about AI epistemic states. Amber's work could engage with Transluce's findings on AI deception, truthfulness, and latent knowledge as artistic material. The o3 "fabrication with elaborate justification" finding is artistically striking. Could reach out about Transluce's open research as context for creative/critical work.

2. **🏠 Residency** — No direct residency connection. However, Transluce's open research model means their tools (Monitor, Docent) are publicly accessible. Amber could use them as research tools to explore AI internals from an artistic perspective.

3. **🎓 Fellowship** — The [Open Philanthropy AI Fellowship](https://www.openphilanthropy.org/grants/early-career-funding-for-individuals-interested-in-improving-the-long-term-future/) is technically relevant but primarily for technical researchers. Less relevant for Amber directly. However, Transluce's approach of independent safety research as non-profit is an institutional model worth noting.

4. **💡 Career inspiration** — The non-profit model for independent research is inspiring. Transluce's structure — open tools, public analysis, conflict-of-interest-free — is a model for how to do critical work on AI from outside industry. Amber might think about similar structures for critical/artistic AI research.

5. **👋 Hangout potential** — US-based (Berkeley). Amber is in London/Oxford. Low proximity, but ICLR/NeurIPS are global conferences. If Amber moves toward more technical AI critique, crossing paths at safety-focused events is possible.

6. **🔧 Professional inspiration** — His "measurement-first" philosophy: define what you're trying to understand, build an instrument to measure it, publish the instrument so others use it. Applied to art: build a measurement instrument for something the field doesn't yet measure (e.g., how art changes minds about AI, not just what art says about AI).

7. **🌍 Areas to know** — The Berkeley AI safety ecosystem: BAIR, Center for AI Safety, Alignment Forum. This is where technical AI safety is being built. Transluce's interpretability work (understanding AI internals) is a key area for anyone doing critical/artistic work on AI systems. Understanding mechanistic interpretability at a conceptual level (circuits, features, superposition) is increasingly necessary cultural knowledge.

8. **🔮 Future involvement** — Transluce is building public tools for understanding AI. As these tools mature, they could become used in critical/artistic research on AI. Amber could become an unusual user of these tools — using interpretability infrastructure for artistic inquiry.

9. **📚 Learning from their path** — The postdoc-at-OpenAI-AND-Open-Philanthropy move (getting exposure to both frontier labs AND safety-oriented thinking before starting your own work) is an interesting model for Amber: understanding both industry and critical perspectives before committing to one camp.

10. **Engagement paths** — Read the [Bounded Regret blog](https://bounded-regret.ghost.io/) for conceptual framing. Try [Transluce Monitor](https://monitor.transluce.org/) as a research tool. Follow Transluce's o3 investigation (which has implications for AI honesty as an artistic/political concept). Watch for Transluce research reports on [their website](https://transluce.org/our-work).

---

## Connected Notes

*People (all are stubs or notes to create):*
- [[Percy Liang]] — PhD advisor, Stanford, HELM, Together AI
- [[Dan Hendrycks]] — former student, Center for AI Safety director ⭐⭐⭐
- [[Sarah Schwettmann]] — Transluce co-founder, MIT interpretability
- [[Collin Burns]] — former student, OpenAI alignment
- [[Anca Dragan]] — Berkeley, HRI + alignment
- [[Stuart Russell]] — Berkeley, AI safety founding figure ⭐⭐⭐
- [[Michael I. Jordan]] — Berkeley, foundational ML

*Communities to create stubs:*
- [[Transluce]] — non-profit interpretability lab
- [[BAIR]] — Berkeley AI Research lab
- [[Center for AI Safety (CAIS)]] — Dan Hendrycks's org
- [[Alignment Forum]] — the intellectual hub of technical alignment

*Venues:*
- [[NeurIPS]] — core venue
- [[ICLR]] — core venue

---

## Stubs to Create

Based on this research, the following new notes should be created:
1. **`communities/Transluce.md`** (⭐⭐⭐) — non-profit AI interpretability lab, October 2024, Schmidt Sciences + Schulman + Zaremba funded
2. **`communities/Center for AI Safety (CAIS).md`** (⭐⭐⭐) — Dan Hendrycks runs it, important hub
3. **`people/Dan Hendrycks.md`** (⭐⭐) — Steinhardt's former student → CAIS director. MMLU, MATH benchmark creator.
4. **`people/Sarah Schwettmann.md`** (⭐⭐) — Transluce co-founder, MIT interpretability
5. **`people/Collin Burns.md`** (⭐⭐) — CCS paper, OpenAI alignment team
6. **`people/Stuart Russell.md`** (⭐⭐⭐) — Berkeley AI safety founding figure, *Human Compatible*

---

## 📋 Update Log

| Date | Researcher | Action |
|------|-----------|--------|
| 2026-02-26 | Biber (subagent) | Initial deep research. Created full profile from scratch. Scraped jsteinhardt.stat.berkeley.edu, bounded-regret.ghost.io, transluce.org. Full publications 2019–2026, all collaborators, Transluce team and funders, blog posts. |
