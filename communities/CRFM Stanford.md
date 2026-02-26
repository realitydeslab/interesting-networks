---
rating: ⭐⭐⭐
full_name: Center for Research on Foundation Models
website: https://crfm.stanford.edu/
location: Stanford University, Palo Alto, CA
founded: 2021-08
parent: Stanford HAI
github: https://github.com/stanford-crfm
added: 2026-02-26
deep_researched: true
last_researched: 2026-02-26
revisit_weeks: 8
next_research: 2026-04-23
tags: [foundation-models, nlp, machine-learning, ai-policy, benchmarking, open-source-ai, ai-governance, social-simulation, machine-behavior, critical-computing]
---

# CRFM Stanford

## Center for Research on Foundation Models

The most consequential academic research institution for foundation model governance, evaluation, and open development. Launched August 2021 simultaneously with the landmark "On the Opportunities and Risks of Foundation Models" paper — the 200-page report that coined the term "foundation model" and defined the conceptual architecture for the entire field. An interdisciplinary initiative within [[Stanford HAI]], spanning 10+ departments — not just CS, but law, medicine, education, social science, music, economics. Directed by [[Percy Liang]], intellectually scaffolded by [[Rishi Bommasani]], and socially extended by [[Michael Bernstein]] and [[Joon Sung Park]].

## ⚡ Recent Updates
- **2026-02-26:** Deep research complete. Expanded from stub to comprehensive note.
- **2025-05:** Marin open lab launched — open-source, fully transparent foundation model training platform. Trained Marin-8B-Base (beats Llama 3.1 8B on 14/19 benchmarks) and Marin-32B-Base.
- **2025:** California Report on Frontier AI Policy co-authored with Li Fei-Fei, Dawn Song, Rishi Bommasani — direct input to California SB 53.
- **2025-12:** HELM Arabic leaderboard launched, expanding evaluation to Arabic language models.
- **2024-05:** Foundation Model Transparency Index v1.1 — 14 companies now participating, mean score rose from 37 to 58 (out of 100).
- **2023-10:** Foundation Model Transparency Index v1.0 (FMTI) released, scoring 10 major AI developers.

## Origin & Founding Story

CRFM was formally established in August 2021, the same week the landmark Foundation Models report appeared on arXiv. This simultaneity was deliberate: the center and the conceptual frame were launched together as a coherent institutional act. [[Percy Liang]] and [[Rishi Bommasani]] coordinated 100+ Stanford co-authors across every department that could be affected by large pretrained models — law (copyright, liability), medicine (clinical NLP), education (automated tutoring), social science (bias, fairness), security, economics. The result was a 200-page document that: (1) named the object of study ("foundation model"), (2) mapped its scope, and (3) established Stanford as the intellectual center for studying it.

The founding was explicitly a counter-move to the trend of foundation model research happening only inside companies (OpenAI, DeepMind, Google Brain). CRFM's thesis: academic research is necessary because companies have structural incentives to avoid transparency, and society needs independent evaluators, benchmark-builders, and policy analysts. This argument — that academic institutions must build the infrastructure for AI accountability — has shaped CRFM's entire program.

[[Joon Sung Park]] designed the CRFM website itself — a detail that encapsulates how closely the lab's intellectual community is intertwined.

## Structure

CRFM operates as an interdisciplinary center within Stanford HAI, not as a standalone department. It has:
- **Core faculty members**: [[Percy Liang]] (director), [[Michael Bernstein]], Dan Jurafsky, Chris Manning, Tatsunori Hashimoto, Sanmi Koyejo, Chelsea Finn, Jure Leskovec, Dan Ho, Dawn Song, Dan Boneh, Li Fei-Fei (HAI director, affiliated), Diyi Yang
- **Research scholars and postdocs**: [[Rishi Bommasani]] (senior research scholar), A. Feder Cooper (postdoc), Sam Park (postdoc)
- **PhD students**: 10+ across Liang's lab alone; dozens more in affiliated faculty labs
- **Affiliated researchers**: wide network across Stanford and beyond

Four research pillars:
1. **Technical foundations** — data curation, systems, architectures, training methods, evaluation methodology, interpretability, adaptation
2. **Beneficial applications** — domain-specific models (biomedicine, law, music, robotics)
3. **Societal impact** — transparency, supply chain analysis, copyright, privacy, openness, systemic risk
4. **AI policy** — direct engagement with governments across multiple jurisdictions (EU AI Act, NTIA, California, White House)

## Key Projects

### Foundation Models Report (2021)
**["On the Opportunities and Risks of Foundation Models"](https://arxiv.org/abs/2108.07258)**
arXiv:2108.07258. Lead: [[Rishi Bommasani]], [[Percy Liang]], and 100+ Stanford co-authors.
The conceptual founding document of the foundation model field. Over 200 pages, covering every conceivable dimension: capabilities, limitations, risks, data, compute, robustness, alignment, fairness, interpretability, law, economics, society, education, healthcare, climate. This is not an AI paper in the narrow sense — it's a map of a new research paradigm. **4,000+ citations.** The term "foundation model" (models trained at scale on broad data that can be adapted to many downstream tasks) now permeates academic literature, policy documents, and press.

What made it different: previous work on "pretrained models" or "GPT-style models" was siloed by subfield. The Foundation Models report insisted that GPT-3, CLIP, DALL-E, AlphaFold, and Codex were instances of the *same phenomenon*, and that they warranted a unified research paradigm. This is conceptual work with institutional consequences.

### HELM — Holistic Evaluation of Language Models (2022–present)
**[HELM](https://crfm.stanford.edu/helm/latest/)** — live benchmark at crfm.stanford.edu/helm
Paper: arXiv:2211.09110. [[Percy Liang]], [[Rishi Bommasani]], Tony Lee, Dimitris Tsipras, and 50+ co-authors.

The field's most comprehensive open evaluation framework for language models. The argument encoded in its design: **you cannot evaluate a language model with one number**. A model might score high on accuracy but fail on calibration, toxicity, or fairness. HELM evaluates 30+ LLMs across:
- 42 scenarios (question answering, summarization, disinformation, code, etc.)
- 7 metrics: accuracy, calibration, robustness, fairness, bias, toxicity, efficiency
- Multi-metric approach: accuracy optimized at expense of toxicity is a real trade-off; HELM makes it visible

Updated continuously. Has expanded to include HELM Arabic (Dec 2025), Cyberbench (cybersecurity, 2024), BioMedLM evaluations, and others. The standard reference point for LLM evaluation in academic and policy contexts. HELM Lite focuses on cost-efficient evaluation for smaller research budgets.

### Foundation Model Transparency Index (FMTI, 2023–present)
**[FMTI](https://crfm.stanford.edu/fmti/)**
Paper: arXiv:2310.12941. [[Rishi Bommasani]], [[Percy Liang]], and CRFM team.

100 fine-grained transparency indicators across three domains:
- **Upstream**: data sources, data labor, data copyright, compute, energy
- **Model**: architecture, capabilities, limitations, evaluations, mitigations
- **Downstream**: distribution channels, usage policies, user impact, geographic reach

**October 2023 (v1.0)**: Scored 10 major foundation model developers (OpenAI, Google, Meta, Anthropic, Hugging Face, Amazon, Cohere, AI21 Labs, Stability AI, Inflection). Mean score: **37/100**. Top score: 54/100. Finding: **no developer disclosed meaningful information about downstream impact.**

**May 2024 (v1.1)**: 14 companies participated, submitted transparency reports. Mean score: **58/100**. Top score: 85/100. 21-point improvement in mean. All 8 companies scored in both versions improved. Developers disclosed 17 new indicators on average. Finding: sustained opacity on data copyright, mitigation effectiveness, and downstream usage data.

Policy impact is direct: FMTI indicators became reference points for the **EU AI Act Code of Practice for GPAI systems**, California's AI policy discussions, and the NTIA's openness report. Boards the FMTI advisory board include Arvind Narayanan (Princeton), Daniel Ho (Stanford law), Danielle Allen (Harvard political philosophy), and others.

### Marin — Open Lab (2025–present)
**[Marin](https://marin.community/)**
GitHub: github.com/marin-community/marin. Lead: David Hall, Ahmed Ahmed, [[Percy Liang]], and team.

Launched May 2025. CRFM's most ambitious open-science commitment: training foundation models completely in public, with every experiment documented as a GitHub issue, every PR reviewed publicly, every mistake logged, every result shared in real-time. "We normalize making mistakes." This is open-source AI taken to its logical conclusion.

**What's been built:**
- **Marin-8B-Base** (Llama architecture, 12.7T tokens): Outperforms Llama 3.1 8B on 14/19 standard benchmarks
- **Marin-8B-Instruct**: Available on Together AI for inference
- **Marin-32B-Base**: Beats OLMo 2 32B Base on 14/19 benchmarks; close to Gemma 3 27B and Qwen 2.5 32B

**The vision**: Like open-source software (Linux, Apache), where anyone can read the code, propose experiments, and contribute back — but for AI training. Piggybacking on GitHub infrastructure for issue tracking, PR review, and provenance.

**Speedrun competition**: Anyone can propose a more efficient training method, pick a compute budget, and submit. Top performers get free compute to scale up. Inspired by the nanogpt speedrun.

Marin represents a political argument: closed development of foundation models is not inevitable. The claim is that open science produces better, safer, more reproducible results than the closed corporate model.

### Levanter — Reproducible Training Framework
**[Levanter](https://github.com/marin-community/levanter)** (formerly stanford-crfm/levanter)
A JAX-based framework for training large language models emphasizing *legibility*, *scalability*, and *reproducibility*. Built by the CRFM research engineering team. Uses Haliax (a named-tensor library) for readable, composable deep learning code. Bitwise deterministic — same configuration always produces same results, even after preemption. Compatible with Hugging Face ecosystem. Powers Marin training runs.

### Ecosystem Graphs (2022)
**[Ecosystem Graphs](https://crfm.stanford.edu/ecosystem-graphs/)**
Maps the supply chain of AI systems: what training data flows into what models, which APIs depend on which foundation models, what applications are built on what APIs. Makes the dependency structure of the AI economy visible. Research tool for understanding systemic risk (if GPT-4 goes down, what applications fail?) and for accountability (if a model is trained on data with copyright problems, which downstream products are affected?).

### BioMedLM (2022)
**[BioMedLM](https://huggingface.co/stanford-crfm/BioMedLM)**
2.7B parameter language model trained exclusively on biomedical literature (PubMed abstracts + full papers). Trained in partnership with MosaicML. Achieves 50.3% accuracy on MedQA biomedical question answering — state of the art at release. Custom biomedical tokenizer that treats medical terms as single tokens. Research artifact for studying domain-specific foundation models; released openly.

### Generative Agents (2023)
**["Generative Agents: Interactive Simulacra of Human Behavior"](https://arxiv.org/abs/2304.03442)**
arXiv:2304.03442. [[Joon Sung Park]], Joseph O'Brien, Carrie Cai, Meredith Ringel Morris, [[Percy Liang]], [[Michael Bernstein]]. UIST 2023, **Best Paper Award**. ~9,000 citations.

While Generative Agents was primarily produced by [[Joon Sung Park]] and [[Michael Bernstein]]'s labs, it is part of the CRFM intellectual ecosystem (Liang is co-author, and Park's PhD was at Stanford). Created 25 LLM-powered computational agents in a sandbox environment ("Smallville") that demonstrate emergent social behavior: spontaneous party planning, relationship formation, schedule coordination. Architecture: memory store (natural language records) + reflection mechanism (higher-level synthesis) + planning module. This became the template for nearly all subsequent LLM agent simulation research.

### AlpacaFarm (2023)
**[AlpacaFarm](https://arxiv.org/abs/2305.14387)**
arXiv:2305.14387. Yann Dubois, Xuechen Li, Rohan Taori, Tianyi Zhang, Ishaan Gulrajani, Jimmy Ba, [[Percy Liang]], Tatsunori Hashimoto, et al. Simulates RLHF training for LLMs (instruction following, preference learning) at dramatically reduced cost by using LLMs as evaluators. Enables academic labs to study instruction tuning without massive GPU clusters.

### BountyBench (2025)
**[BountyBench](https://crfm.stanford.edu/2025/05/21/bountybench.html)**
Dollar-denominated AI agent evaluation framework for cybersecurity. Measures how well AI agents can find and fix security vulnerabilities (bugs with known bounty values). Led by Andy K. Zhang, with Percy Liang, Dawn Song, Dan Boneh, Daniel Ho. Measures AI attacker/defender performance in real-world cybersecurity contexts. An unusual intersection of security research and foundation model evaluation.

## Key People

### Core CRFM

**[[Percy Liang]]** ⭐⭐⭐ — **Founding Director**
Associate Professor of CS at Stanford. The intellectual architect of the entire CRFM program. Co-coined "foundation model," built HELM, launched Marin. MIT undergraduate, Berkeley PhD (advisors: Michael I. Jordan + Dan Klein). PECASE Award (2019), IJCAI Computers and Thought Award (2016). Lab has produced an extraordinary stream of researchers now at OpenAI, Google DeepMind, Berkeley, CMU, UW, Harvard. *See [[Percy Liang]] for deep profile.*

**[[Rishi Bommasani]]** ⭐⭐ — **Senior Research Scholar, Stanford HAI**
PhD (2025, co-advised by Liang and Dan Jurafsky). The intellectual architect of CRFM's public-facing work: lead author on both the Foundation Models report and FMTI. Now Senior Research Scholar at Stanford HAI, focused on AI policy and societal impact. Major policy impacts: EU AI Act Code of Practice (chairs working group), California SB 53, US NTIA openness report, International Scientific Report on AI. Featured in The Atlantic, Nature, NYT, Washington Post, Quanta Magazine. *See [[Rishi Bommasani]] for profile.*

**[[Michael Bernstein]]** ⭐⭐⭐ — **HCI Faculty, Senior Fellow at Stanford HAI**
Professor of CS at Stanford (on leave 2025–2026 to co-found [Simile.ai](https://simile.ai/)). Generative Agents co-author. Social computing, crowd computing, LLM social simulation. National bestselling book *Flash Teams* (MIT Press, 2025). Alfred P. Sloan Fellow. *See [[Michael Bernstein]] for deep profile.*

**[[Joon Sung Park]]** ⭐⭐⭐ — **PhD alumnus, Generative Agents creator**
PhD CS, Stanford (2025). Lead author of Generative Agents (the most-cited AI/HCI paper of 2023). Also lead on Generative Agent Simulations of 1,000 People (2024). Stanford HCI PhD co-advised by Percy Liang and Michael Bernstein. Designed the CRFM website. *See [[Joon Sung Park]] for deep profile.*

### Affiliated Faculty

**Li Fei-Fei** — Stanford HAI Co-Director. ImageNet pioneer. Computer vision. Foundation Models report co-author. Co-authored California Report on Frontier AI Policy (2025). The central node connecting CRFM to Stanford's AI policy infrastructure and to the broader Stanford AI ecosystem.

**Dan Jurafsky** — Professor of Linguistics and CS. Co-advised Rishi Bommasani. Author of the standard NLP textbook (*Speech and Language Processing*). HELM co-author. Provides the linguistic grounding in CRFM's natural language work.

**Chris Manning** — Professor of CS and Linguistics. Co-advisor to several Liang PhD students. One of the pioneers of statistical NLP; runs the Stanford NLP Group. HELM co-author.

**Tatsunori Hashimoto** — Assistant Professor, Stanford CS. Former Percy Liang postdoc. Robustness, distribution shift, LLM evaluation. Frequent Liang paper co-author. AlpacaFarm lead; s1 paper lead.

**Chelsea Finn** — Assistant Professor, Stanford CS. Meta-learning, robot learning. Co-advises multiple Liang students.

**Jure Leskovec** — Professor, Stanford CS. Graph machine learning, social networks. Co-advises Qian Huang. Co-authored MLAgentBench with Liang.

**Sanmi Koyejo** — Assistant Professor, Stanford CS. Fairness, robustness, safety. Co-advises Ahmed Ahmed and Ken Liu.

**Dan Ho** — William Benjamin Scott and Luna M. Scott Professor of Law, Stanford. Director of RegLab. National AI Advisory Committee (NAIAC). FMTI advisory board. Policy + AI governance expert. Co-advises postdocs at CRFM (A. Feder Cooper).

**Dawn Song** — Professor, UC Berkeley (affiliated with Stanford CRFM work). AI security. BountyBench co-author. California AI Policy report co-author. Key link between CRFM and Berkeley AI security world.

**Dan Boneh** — Professor of CS, Stanford. Cryptography and AI security. BountyBench co-author. Connects CRFM to security research.

**[[Diyi Yang]]** ⭐⭐ — Assistant Professor, Stanford CS. Social NLP, human-centered NLP. Frequent collaborator with Michael Bernstein and Joon Sung Park. Research on culturally-aware AI, social influence, and LLM alignment with human values.

**Surya Ganguli** — Associate Professor, Stanford. Theoretical neuroscience + deep learning. HELM co-author. Connects CRFM to theory of neural computation.

**Noah Goodman** — Professor, Stanford. Probabilistic programming, cognitive science, language models. Foundation Models report co-author.

### Notable Alumni (Percy Liang's Lab → CRFM-adjacent)

These alumni carry the CRFM intellectual DNA into new institutions:

| Person | Current Position | Connection |
|--------|-----------------|------------|
| **[[Jacob Steinhardt]]** | Assoc. Prof, UC Berkeley; CEO Transluce | PhD 2018; AI safety, interpretability |
| Pranav Rajpurkar | Assoc. Prof, Harvard Medical School | PhD 2021; SQuAD dataset; medical AI |
| Tatsunori Hashimoto | Asst. Prof, Stanford CS | Postdoc 2019; robustness/eval |
| Pang Wei Koh | Asst. Prof, University of Washington | PhD 2022; influence functions, robustness |
| Robin Jia | Asst. Prof, USC | PhD 2020; adversarial NLP |
| Mina Lee | Asst. Prof, University of Chicago | PhD 2023; writing AI, human-AI collab |
| He He | Asst. Prof, NYU | Postdoc; language robustness |
| Aditi Raghunathan | Asst. Prof, CMU | PhD 2021; adversarial robustness |
| Chris Donahue | Asst. Prof, CMU | Postdoc 2022; music AI |
| Stephen Mussmann | Asst. Prof, Georgia Tech | PhD 2021; active learning |
| John Thickstun | Asst. Prof, Cornell | Postdoc 2024; music AI |
| John Hewitt | Asst. Prof, Columbia | PhD 2024; probing, structural NLP |
| Fereshte Khani | Research Scientist, OpenAI | PhD 2021 |
| Ananya Kumar | Research Scientist, OpenAI | PhD 2023 |
| Shibani Santurkar | Research Scientist, OpenAI | Postdoc 2023 |
| Dimitris Tsipras | Research Scientist, OpenAI | Postdoc 2023 |
| Yuhuai (Tony) Wu | Co-founder, xAI (Elon Musk's AI) | Postdoc 2023 |
| Kelvin Guu | Research Scientist, Google DeepMind | PhD 2018 |
| Roy Frostig | Research Scientist, Google Research | PhD 2016 |
| Sida Wang | Research Scientist, Meta | PhD 2017 |
| Niladri Chatterji | Research Scientist, Meta | Postdoc 2023 |

The lab pipeline is extraordinary: 12+ faculty positions at top-10 CS departments, multiple OpenAI researchers, xAI co-founder. This network propagates CRFM's intellectual commitments into the institutions that matter most.

## Community Connections

### Stanford HAI
CRFM is formally embedded within [[Stanford HAI]] (Human-Centered AI Institute), founded 2019 by Fei-Fei Li and John Etchemendy. HAI provides institutional home, funding relationships, policy engagement infrastructure, and the broader university frame. CRFM represents the technical and governance work within HAI; HAI provides the political capital and policy infrastructure. Key overlapping figures: Percy Liang (Senior Member), Michael Bernstein (Senior Fellow), Rishi Bommasani (Senior Research Scholar). The relationship is symbiotic: CRFM produces the research, HAI translates it to policy.

### Stanford NLP Group
CRFM overlaps substantially with the Stanford NLP Group (Manning, Jurafsky, Potts). The NLP group is the technical foundation; CRFM adds the governance and societal framing. Many CRFM papers originate in NLP group work.

### Stanford HCI Group
[[Stanford HCI Group]] — Michael Bernstein and colleagues. The HCI connection is unusual for a foundation model center and reflects CRFM's genuine commitment to human-computer interaction questions. Generative Agents, Social Simulacra, Jury Learning, and many other papers came from this intersection. The fact that the most-cited AI/HCI paper of 2023 had Percy Liang as a co-author says something about CRFM's breadth.

### EleutherAI
Connected through open-source AI development community. CRFM and EleutherAI share the commitment to open AI development but approach it differently: EleutherAI is a distributed volunteer community; CRFM is an academic institution. They cite each other, use shared datasets (The Pile), and share the political commitment to open-source AI. Marin announcement explicitly lists EleutherAI as a peer open-source model project.

### Allen Institute for AI (AI2)
Explicitly listed as a peer open-weight model project in the Marin launch announcement. AI2 (OLMo, OLMOE models) and CRFM/Marin share the open-source AI development niche. Marin-32B-Base was benchmarked explicitly against OLMo 2 32B.

### Hugging Face
Partner in the open AI ecosystem. CRFM models (BioMedLM, Marin) are hosted on Hugging Face. Hugging Face scored in FMTI (scored highly, especially v1.1 with +32 point improvement). Multiple collaborations.

### MosaicML / Databricks
Partner for BioMedLM training (2022). MosaicML provided training infrastructure (now Databricks MosaicML). First major external partnership showing CRFM's ability to work with industry to produce open artifacts.

### AI Policy Institutions
Direct engagement across multiple governments and policy bodies:
- **EU AI Act**: FMTI indicators shaped the GPAI (General Purpose AI) Code of Practice. [[Rishi Bommasani]] co-chairs one of the working groups.
- **NTIA (US)**: Rishi Bommasani's testimony directly shaped the [NTIA Open Model Report](https://www.ntia.gov/sites/default/files/publications/ntia-ai-open-model-report.pdf) — the US federal government's position on open-source AI.
- **California**: California Report on Frontier AI Policy (2025); direct input to SB 53 (AI safety law). Co-authored by Liang, Bommasani, Li Fei-Fei, Dawn Song.
- **White House**: CRFM work cited in White House voluntary AI commitments.
- **G7 Hiroshima Process**: FMTI referenced in G7 AI Code of Conduct.
- **International Scientific Report on AI**: Rishi Bommasani contributing author (arXiv:2501.17805, 2025).

### Academic Peer Institutions
- **MIT AI Lab / CSAIL**: Cross-citations, some collaborations. MIT more engineering-focused.
- **UC Berkeley AI Research (BAIR)**: Strong connection through [[Jacob Steinhardt]] (PhD alumnus), Dawn Song (co-author), Chelsea Finn (joint faculty). CRFM and BAIR share the foundation model governance interest.
- **CMU ML Dept**: Multiple CRFM alumni now faculty there (Aditi Raghunathan, Chris Donahue). CMU less focused on governance, more on ML methods.
- **Princeton Center for Information Technology Policy (CITP)**: Arvind Narayanan on FMTI advisory board. CITP works on transparency and AI accountability — aligned with CRFM's FMTI agenda.

## Venue Circuit Analysis

CRFM researchers publish across an unusually wide range of venues, reflecting the genuine interdisciplinarity of the enterprise:

**Core ML/AI venues:**
- **NeurIPS** — Deep learning and systems work (DoReMi, AlpacaFarm, BioMedLM)
- **ICML** — ML theory and applications (influence functions Best Paper; Marin experiments)
- **ICLR** — Learning representations
- **AAAI** — Broader AI conference

**NLP venues:**
- **ACL, EMNLP, NAACL** — NLP work (SQuAD, semantic parsing, HELM follow-up)

**HCI venues (unusual for an ML center):**
- **UIST** — Generative Agents (Best Paper, 2023); Social Simulacra (2022)
- **CHI** — Writing AI, human-AI interaction (Mina Lee's work; Michelle Lam's work)
- **CSCW** — Social computing (Bernstein collaborations)

**Security venues:**
- **IEEE S&P, CCS, USENIX Security** — BountyBench, Cyberbench; Boneh and Song connections

**High-prestige science journals:**
- **Science** — Algorithmic polarization paper (Bernstein + Piccardi, 2025)
- **PNAS** — Ethical research practices

**Policy/law venues:**
- **Congressional testimony** — Rishi Bommasani, Percy Liang on AI policy
- **Stanford Law Review** — Copyright and fair use analysis (Henderson, Li, Jurafsky, Hashimoto, Lemley, Liang)
- **Science** (policy policy paper): "Evidence-based AI policy" paper (Bommasani, 2025 Science doi)

**The pattern**: Unlike most ML research centers, CRFM publishes where the questions lead — into law journals, into HCI conferences, into high-prestige science venues. This reflects the genuine interdisciplinarity of the "societal impact" pillar.

## Key Ideas & Intellectual Contributions

### 1. "Foundation Model" as a Conceptual Invention (2021)
Before CRFM, the field discussed "pretrained models," "GPT-style models," "large language models." These were understood as scaled-up versions of existing architectures. The Foundation Models report argued something stronger: **these models represent a new paradigm, not just better versions of old models**. They are trained once and adapted everywhere; they carry their biases and capabilities into every downstream deployment; they require a new research agenda that spans capabilities, limitations, risks, applications, and governance. The term "foundation model" was deliberately chosen: "foundation" to highlight the base-layer quality (models built on top), but also to invite scrutiny — foundations can be flawed and the flaws propagate upward.

This conceptual intervention had real institutional effects: it created a shared object of study across NLP, vision, robotics, medicine, and law. Papers now routinely describe their work as "evaluating/studying/deploying foundation models" because CRFM's framing made that sentence make sense.

### 2. Holistic Evaluation as Political Position (2022)
HELM is not just a bigger benchmark — it's a *political argument* about how AI systems should be evaluated. The claim: **evaluation with a single metric (accuracy, perplexity) is not just incomplete — it is actively misleading and allows companies to cherry-pick favorable results.** Real evaluation requires:
- Multiple scenarios (covering diverse uses, not just the ones developers want to highlight)
- Multiple metrics (accuracy + calibration + robustness + fairness + bias + toxicity + efficiency)
- Transparency about methodology (so scores can be scrutinized and debated)

This is a direct critique of the leaderboard culture that dominated NLP evaluation (GLUE, SuperGLUE, MMLU) where a single score creates a false sense of comprehensiveness. HELM's multi-metric approach forces trade-offs into visibility — if a model is accurate but biased, that should show up as a split score, not an average.

### 3. Transparency as Governance Precondition (2023)
FMTI's core argument: **you cannot govern what you cannot see, and you cannot see foundation models because developers do not disclose meaningful information.** The 100-indicator framework operationalizes transparency — not as an abstract value, but as specific disclosures that regulators, researchers, and civil society can demand.

The October 2023 finding (average score 37/100) was a governance indictment: the most powerful AI systems in the world are almost entirely opaque about their training data, compute, energy use, and downstream impact. The May 2024 improvement (average 58/100) shows that structured accountability mechanisms *work* — companies improved when they had specific indicators to address.

### 4. Open Science as Political Act (2025)
Marin represents the most radical articulation of CRFM's open-science commitment: **not just releasing weights, not just releasing code, but building AI in public, in real time, with every mistake documented**. This is different from "open-weight" models (Llama, Gemma) where weights are shared but the training process is opaque. Marin documents everything — including the failures, bugs, and abandoned experiments that normally stay inside companies.

The political argument: if AI systems are to be trusted and audited, the development process must be transparent, not just the final artifact. The Marin-8B-Base performance result (beats Llama 3.1 8B on 14/19 benchmarks) shows this is not just idealism — open science can produce competitive models.

### 5. Data Attribution and Copyright (2017, 2023)
Two linked contributions:
- **Influence functions** (arXiv:1703.04730, ICML 2017 Best Paper): A method to trace a model's prediction back to the specific training examples most responsible. Foundational for understanding *what in the data causes which model behavior* — relevant for debugging, bias auditing, copyright, and safety.
- **Foundation Models and Fair Use** (arXiv:2303.15715, 2023): The first serious academic treatment of training-data copyright. Conclusion: fair use is not a blanket shield. If a model reproduces copyrighted content in market-affecting ways, liability may exist. Directly relevant to ongoing litigation (Getty Images v. Stability AI, NYT v. OpenAI, etc.).

Together, these contributions establish that CRFM has thought carefully about the legal and ethical status of training data — a question that will reshape AI law over the next decade.

### 6. Social Simulation Architecture (2023)
The Generative Agents paper contributed something beyond a single paper's findings: an **architecture** for LLM-based social simulation. The memory store → reflection → planning pipeline is now the standard design for agents that need to behave believably over time. This architecture sits at the intersection of HCI (believable agents), AI (LLM capabilities), and social science (behavioral modeling). It unlocked a research trajectory: agents as social science instruments, not just task executors.

### 7. Ecosystem Mapping (2022)
Ecosystem Graphs makes the AI supply chain visible: which models depend on which training data, which APIs depend on which foundation models, which applications depend on which APIs. This infrastructure mapping is precondition for accountability — if a model is trained on data with copyright problems, or if a training data supplier disappears, the downstream effects need to be traceable. This is less celebrated than HELM or FMTI but is fundamental infrastructure for AI governance.

## Policy Impact

CRFM's policy footprint is remarkable for an academic institution:

- **EU AI Act**: FMTI indicators are explicitly referenced in the GPAI Code of Practice for foundation model providers. Rishi Bommasani co-chairs a working group developing the Code's technical standards. This is direct influence on legally binding regulation covering the world's largest market.

- **US NTIA**: CRFM research directly shaped the [NTIA AI Open Model Report](https://www.ntia.gov/sites/default/files/publications/ntia-ai-open-model-report.pdf) — the US federal government's position on open-source AI development. This report informed subsequent executive branch AI policy.

- **California SB 53 (2025)**: The California Report on Frontier AI Policy (co-authored by Liang, Bommasani, Li Fei-Fei, Dawn Song) directly fed into California's AI safety legislation — the most significant state-level AI law in the US.

- **White House voluntary AI commitments (2023)**: CRFM work and FMTI indicators cited in White House AI voluntary commitments from major companies.

- **Congressional testimony**: Percy Liang and Rishi Bommasani have testified before Congress on AI transparency and accountability.

- **G7 Hiroshima Process**: FMTI referenced in the G7 international AI Code of Conduct.

- **International Scientific Report on AI**: Rishi Bommasani contributing author to the landmark international scientific assessment of AI (arXiv:2501.17805, 2025).

## Open Calls / Getting Involved

- **CRFM is not explicitly a fellowship program**, but there are paths in:
  - PhD at Stanford in CS, Statistics, Law, Medicine — route to CRFM affiliation through any of the affiliated faculty labs
  - Stanford HAI Postdoctoral Fellowship — eligibility for CRFM-adjacent postdoc work
  - **Marin open contribution**: marin.community is explicitly open — anyone can join the GitHub, submit PRs, propose experiments. This is a real pathway for non-Stanford researchers to engage with CRFM work. Discord: discord.gg/J9CTk7pqcM
  - **HELM contributions**: Scenarios and metrics can be contributed externally; CRFM has extended HELM with community-contributed evaluations
  - **FMTI data use**: All FMTI data is public at github.com/stanford-crfm/fmti for researchers
- **No formal residency program** (unlike AI2, Anthropic, etc.)
- Contact: crfm-contact@stanford.edu (for research inquiries)

## Why Interesting to Amber

### Machine Behavior as Science — Alignment at the Field Level
CRFM's project is to study foundation models the way Iyad Rahwan argues we should study AI systems: empirically, behaviorally, as objects in the world with observable properties. HELM is a behavioral science instrument applied to LLMs. FMTI is an accountability framework. Generative Agents is a laboratory for emergent social behavior. All three are expressions of the same epistemology: don't take AI systems on faith; study them like you'd study any complex phenomenon.

This aligns precisely with Amber's interest in machine behavior, critical computing, and AI as social actor.

### Generative Agents as Social Simulation Infrastructure
The Generative Agents paper (Joon Sung Park + Michael Bernstein + Percy Liang) is the computational foundation for AI agent simulation at the social level. Its architecture — memory store, reflection mechanism, planning module — is now the standard blueprint. Anyone doing research on how AI agents behave in social contexts is building on or responding to this paper. For Amber's work on machine behavior, agent ethology, or parasitic agents, understanding this architecture is essential background.

The follow-up "Generative Agent Simulations of 1,000 People" (2024) shows the trajectory: population-scale behavioral simulation validated against real human data (General Social Survey). This is machine behavior research becoming a legitimate social science instrument.

### Open AI Governance as Critical Computing
CRFM's policy work (FMTI, California Report, EU AI Act engagement) is exactly the "critical computing" angle Amber values: asking who controls AI infrastructure, who is accountable when it fails, and what institutional mechanisms can create accountability. This isn't critique from outside the system — it's constructive engagement to build governance infrastructure before corporate power fully consolidates.

The Marin open lab is particularly interesting as a form of research infrastructure with explicit political stakes: building AI in public is a claim that transparency matters, that AI development doesn't have to be opaque, and that academic institutions can do production-quality work without Google-scale secrecy.

### HCI-ML Bridge — Rare Interdisciplinary Confluence
CRFM is unusual among foundation model research centers for taking HCI seriously as a discipline, not just an application area. The Generative Agents paper was explicitly designed for the CHI/UIST audience. Michael Bernstein is a core CRFM collaborator, not just an adjacent researcher. This means CRFM produces papers in venues Amber reads (CHI, UIST, CSCW) that have the technical depth to matter.

For Amber's research position — bridging HCI, art, and technology — CRFM is one of the few ML institutions that has built genuine infrastructure for that kind of crossover.

### Key Amber-Adjacent People in This Network
- **[[Michael Bernstein]]** — Generative Agents, social simulation, critical computing (Street-Level Algorithms), HCI. ⭐⭐⭐
- **[[Joon Sung Park]]** — Generative Agents and population-scale simulation. ⭐⭐⭐
- **[[Percy Liang]]** — Foundation model governance, open science, social simulation co-author. ⭐⭐⭐
- **[[Rishi Bommasani]]** — AI policy, transparency frameworks, bridge between ML and governance. ⭐⭐
- **[[Jacob Steinhardt]]** — AI safety, interpretability, Transluce. ⭐⭐⭐ (now Berkeley/Transluce)
- **Mina Lee** — Writing AI, human-AI collaboration, UChicago (near [[James Evans]]). Worth a stub.
- **[[Diyi Yang]]** — Social NLP, culturally-aware AI. ⭐⭐

## New Nodes to Research

### People (stubs to create)
- **Mina Lee** — PhD 2023, now asst prof at UChicago. Writing AI, HCI+NLP, human-AI collaboration. Interesting because she's at UChicago near James Evans and works on human-AI collaborative writing — directly relevant to Amber's interests. ⭐⭐
- **Tatsunori Hashimoto** — Stanford CS. LLM robustness, alignment, evaluation. Former Liang postdoc, now faculty. Productive co-author on many CRFM papers (AlpacaFarm, s1). ⭐ stub
- **Neel Guha** — CRFM PhD student. AI and law — "LegalBench" benchmarking legal reasoning in LLMs. Interesting at intersection of AI and legal institutions. ⭐ stub

### Communities (stubs to create)
- **Marin Community** (marin.community) — the open lab that spun out of CRFM for open-source foundation model training. Now technically separate from CRFM but intellectual successor. ⭐⭐ stub
- **Stanford RegLab** (law.stanford.edu/reg-lab) — Dan Ho's lab. AI + administrative law + governance. Closely connected to CRFM through FMTI advisory board and postdoc co-advising. ⭐ stub

### Venues (stubs if not present)
- Check if HELM or FMTI have their own notes — they probably should as key AI evaluation infrastructure projects.

## Research Log

*2026-02-26: Deep research complete. Phase 1: scraped crfm.stanford.edu, percy liang's website, rishi bommasani's site, marin.community, FMTI page, HELM page, levanter github, michael bernstein's site. Phase 2: mapped collaborators via foundation models paper (100+ co-authors), HELM paper (50+ co-authors), identified key alumni network. Phase 3: community connections mapped (Stanford HAI, Stanford NLP, HCI Group, EleutherAI, AI2, EU AI Act, NTIA, California policy). Phase 4: venue circuit analysis (NLP + ML + HCI + Security + Policy + Science journals). Phase 5: policy impact documented (EU AI Act, NTIA, California SB 53, White House). Phase 6: key ideas and intellectual contributions articulated. Phase 7: assembled note.*

*People notes already in graph: Percy Liang ⭐⭐⭐, Rishi Bommasani ⭐⭐, Michael Bernstein ⭐⭐⭐, Joon Sung Park ⭐⭐⭐, Jacob Steinhardt ⭐⭐⭐, Diyi Yang ⭐⭐. Communities already in graph: Stanford HAI. New stubs recommended: Mina Lee (⭐⭐), Marin Community (⭐⭐), Stanford RegLab (⭐), Tatsunori Hashimoto (⭐), Neel Guha (⭐).*
