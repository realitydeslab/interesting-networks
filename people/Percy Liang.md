---
rating: ⭐⭐⭐
affiliation: Stanford University
website: https://cs.stanford.edu/~pliang/
born: ~1981 (estimated; no public record)
education:
  - BS Computer Science, MIT (2004)
  - MEng Computer Science, MIT (2005)
  - PhD Computer Science, UC Berkeley (2011)
based: Stanford, CA
added: 2026-02-26
tags: [machine-learning, foundation-models, nlp, ai-safety, ai-policy, benchmarking, open-source-ai, reproducibility]
deep_researched: true
last_researched: 2026-02-26
revisit_weeks: 4
next_research: 2026-03-26
---

# Percy Liang

The architect of the "foundation model" concept and the person most responsible for the institutional infrastructure around evaluating and governing them. Associate Professor of CS at Stanford, founding Director of [[CRFM Stanford|CRFM]] (Center for Research on Foundation Models), and one of the most quietly influential people in AI right now. His lab has produced an extraordinary number of people now shaping AI at OpenAI, Google DeepMind, top universities — and Joon Sung Park, the co-creator of Generative Agents, was his PhD student. Bridging technical ML, social simulation, and AI policy in a way almost nobody else does at this scale.

## Background

- **B.S. Computer Science, [MIT](https://mit.edu/)**, 2004. Silver and bronze medals at the **[International Olympiad in Informatics](https://ioinformatics.org/)** (IOI) — elite competitive programmer before becoming an academic. The kind of technical foundation that makes everything else go faster.
- **M.Eng. Computer Science, [MIT](https://mit.edu/)**, 2005.
- **Ph.D. Computer Science, [UC Berkeley](https://eecs.berkeley.edu/)**, 2011. Dissertation: *Probabilistic Models with Latent Structure*. Advisors: **[Michael I. Jordan](https://people.eecs.berkeley.edu/~jordan/)** (one of the most influential ML researchers alive — Jordan invented variational inference, EM algorithm applications, graphical models) and **[Dan Klein](https://people.eecs.berkeley.edu/~klein/)** (NLP, probabilistic parsing). This combination shaped everything: statistical rigor + language understanding.
- **Postdoctoral researcher, Google**, 2011–2012. Brief industry stint before returning to academia.
- **Faculty, [Stanford University](https://stanford.edu/)**, 2012–present. Associate Professor of Computer Science (and by courtesy, Statistics).

## Positions

- **Associate Professor, [CS Department](https://cs.stanford.edu/), Stanford University**
- **Founding Director, [Center for Research on Foundation Models (CRFM)](https://crfm.stanford.edu/)** — launched August 2021, same time as the landmark Foundation Models paper
- **Senior Member, [Stanford HAI](https://hai.stanford.edu/)** (Human-Centered AI Institute)
- Member of [Stanford AI Lab (SAIL)](https://ai.stanford.edu/), [NLP Group](https://nlp.stanford.edu/), [ML Group](https://ml.stanford.edu/)

## Research Themes

Liang works at the intersection of machine learning, NLP, and societal impact. He describes his approach as: "I am drawn to simple things, want to understand things deeply, and like to build useful systems." Three big arcs:

**1. Foundation Models as a Research Object**
Coined (with collaborators) the term "foundation model" in the 2021 report — arguing that large pretrained models that are adapted to many tasks deserve their own research paradigm. His central question: what are the capabilities, limitations, and risks of these systems, studied systematically rather than anecdotally?

**2. Evaluation as Infrastructure**
HELM (Holistic Evaluation of Language Models) is not just a benchmark — it's an argument that evaluation should be comprehensive, multi-dimensional, and transparent. He doesn't just build leaderboards; he argues about what counting should look like.

**3. Reproducibility and Open Science**
CodaLab Worksheets (reproducible research platform) and Marin (open lab for training foundation models from scratch) reflect a philosophy: ML progress should be verifiable and collaborative, not locked inside corporate servers.

## Key Works & Papers

### Landmark Papers

**[On the Opportunities and Risks of Foundation Models](https://arxiv.org/abs/2108.07258)** (2021)  
arXiv:2108.07258. The paper that coined "foundation model" — Rishi Bommasani, Liang, and 100+ Stanford co-authors. 200-page report analyzing LLMs and other large pretrained models across every dimension: data, compute, capabilities, safety, ethics, economics, law. Published exactly as CRFM launched. Over 4,000 citations. Became the conceptual frame for the entire field.

**[Holistic Evaluation of Language Models (HELM)](https://arxiv.org/abs/2211.09110)** (2022)  
arXiv:2211.09110. Liang, Rishi Bommasani, Tony Lee, Dimitris Tsipras, and 50+ co-authors. Evaluated 30+ LLMs across 42 scenarios and 7 metrics (accuracy, calibration, robustness, fairness, bias, toxicity, efficiency). Live benchmark at [crfm.stanford.edu/helm](https://crfm.stanford.edu/helm/latest/). The argument: you can't evaluate a language model with one number. HELM is the counter-attack against simplistic leaderboards.

**[Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)** (2023)  
arXiv:2304.03442. Liang, **Joon Sung Park**, Joseph C. O'Brien, Carrie J. Cai, Meredith Rinne Jones, **Michael Bernstein**. Published UIST 2023. One of the most-read AI papers of 2023 (~9,000 citations). Created a virtual town of 25 LLM-powered agents that plan, remember, reflect, and form social behaviors. Agents spread party invitations, asked each other on dates, formed opinions — emergent social behavior from architecture, not rule-coding. This paper is the formal foundation for the entire "generative agents / AI social simulation" research trajectory.

**[Understanding Black-box Predictions via Influence Functions](https://arxiv.org/abs/1703.04730)** (ICML 2017, **Best Paper**)  
arXiv:1703.04730. **Pang Wei Koh** and Liang. Applied classical robust statistics technique (influence functions) to modern ML: trace a model's prediction back to the specific training examples most responsible. Foundational for data attribution — understanding *which data causes which model behavior*. >3,000 citations. Still a key method for AI interpretability and data poisoning detection.

**[SQuAD: 100,000+ Questions for Machine Comprehension of Text](https://arxiv.org/abs/1606.05250)** (EMNLP 2016)  
arXiv:1606.05250. Pranav Rajpurkar, Jian Zhang, Konstantin Lopyrev, Liang. Stanford Question Answering Dataset. 100K+ crowdsourced Q&A pairs on Wikipedia. Became the de facto NLP reading comprehension benchmark for years, driving huge advances in language understanding. Dataset at [stanford-qa.com](https://stanford-qa.com).

**[Foundation Models and Fair Use](https://arxiv.org/abs/2303.15715)** (2023)  
arXiv:2303.15715. Peter Henderson, Xuechen Li, Dan Jurafsky, Tatsunori Hashimoto, Mark Lemley, Liang. Analyzes US copyright law and fair use doctrine as applied to foundation model training. Argues fair use is not guaranteed — if a model reproduces copyrighted content, especially affecting market value, it's at risk. Experiments confirm models *can* reproduce copyrighted text. Proposes technical and legal co-evolution.

**[The Foundation Model Transparency Index (FMTI)](https://arxiv.org/abs/2310.12941)** (2023)  
arXiv:2310.12941. CRFM team, led by Liang and Rishi Bommasani. 100 fine-grained transparency indicators across upstream (data, labor, compute), model (size, capabilities, risks), and downstream (distribution, policies). Scored OpenAI, Google, Meta, Anthropic and 6 others. Finding: no developer disclosed significant information about downstream impact. Establishing accountability baseline for AI governance.

**[DoReMi: Optimizing Data Mixtures Speeds Up Language Model Pretraining](https://arxiv.org/abs/2305.10429)** (NeurIPS 2023)  
arXiv:2305.10429. Sang Michael Xie, Hieu Pham, Xuanyi Dong, Nan Du, Hanxiao Liu, Yifeng Lu, Percy Liang et al. Domain Reweighting with Minimax Optimization: use a small proxy model to find optimal data domain weights (Wikipedia vs. books vs. web text) before training a large model. 2.6x fewer training steps to match baseline. Directly practical for foundation model training.

**[MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation](https://arxiv.org/abs/2310.03302)** (2023)  
arXiv:2310.03302. Qian Huang, Jian Vora, Liang, Jure Leskovec. 13 ML tasks (CIFAR-10 to recent research problems) where agents can read/write files, execute code, inspect outputs. Can Claude, GPT-4, Gemini do ML research? Best result: Claude 3 Opus, 37.5% success rate. The "AI doing science" benchmark.

**[s1: Simple Test-Time Scaling](https://arxiv.org/abs/2501.19393)** (2025)  
arXiv:2501.19393. Niklas Muennighoff, Zitong Yang, Weijia Shi, Xiang Lisa Li, Li Fei-Fei, Liang, Tatsunori Hashimoto et al. A small open-source reasoning model that approaches o1 performance by distilling a dataset of 1K hard problems. Budget forcing technique: extend thinking time at inference.

### Key Research Tools

**[HELM (Holistic Evaluation of Language Models)](https://crfm.stanford.edu/helm/latest/)**  
Live leaderboard evaluating models across dozens of scenarios. The field's most comprehensive open benchmark. Updated regularly.

**[CodaLab Worksheets](https://worksheets.codalab.org/)**  
Reproducible research platform Liang co-created. Tracks complete experiment provenance from raw data to results. Many of his papers are "executable papers" on CodaLab — you can reproduce results directly.

**[Marin](https://marin.community/)** (launched 2025)  
Open lab for training foundation models from scratch. Every experiment is documented as a GitHub issue, every model is shared. "We invite anyone who shares our vision of open science." His most ambitious open-source commitment. Trains models openly, shares all code/data/logs/mistakes. Training models in public is a political act as much as a scientific one.

**[Ecosystem Graphs](https://crfm.stanford.edu/ecosystem-graphs/)**  
Maps the supply chain of foundation models — what data, compute, models are connected to what applications. The infrastructure layer of the AI economy made visible.

## CRFM — What Is It and Who's In It

The **[Center for Research on Foundation Models](https://crfm.stanford.edu/)** was founded August 2021, co-launched with the "Opportunities and Risks" paper. It's an interdisciplinary initiative within Stanford HAI spanning 10+ departments.

**Mission pillars:**
1. *Technical foundations* — data, systems, architectures, training, evaluation, interpretability
2. *Beneficial applications* — law, music, robotics, biomedicine  
3. *Societal impact* — transparency, supply chains, openness, copyright, privacy, systemic risk
4. *AI policy* — direct government engagement across multiple jurisdictions

**Key faculty/researchers in CRFM orbit:**
- **[Li Fei-Fei](https://profiles.stanford.edu/fei-fei-li)** — Stanford HAI co-director, vision AI, Foundation Models paper co-author, California AI policy report
- **[Dan Jurafsky](https://web.stanford.edu/~jurafsky/)** — linguistics/NLP, HELM co-author
- **[Chris Manning](https://nlp.stanford.edu/manning/)** — NLP, co-advisor of several Liang students
- **[Tatsunori Hashimoto](https://thashim.github.io/)** — Stanford asst prof, former Liang postdoc, robustness/distribution shift
- **[Chelsea Finn](https://ai.stanford.edu/~cbfinn/)** — robotics/meta-learning, co-advises several Liang students
- **[Jure Leskovec](https://cs.stanford.edu/people/jure/)** — graph ML, co-advises Qian Huang
- **[Sanmi Koyejo](https://cs.stanford.edu/~sanmi/)** — fairness/safety, co-advises Ahmed Ahmed and Ken Liu
- **[Michael Bernstein](https://hci.stanford.edu/msb/)** — HCI, Generative Agents co-author, see [[Michael Bernstein]]
- **[Dan Ho](https://law.stanford.edu/daniel-e-ho/)** — law + AI, policy, co-advises postdocs

*The CRFM website was designed by Joon Sung Park — even the infrastructure shows the density of collaboration.*

## Awards & Recognition

- **[Presidential Early Career Award for Scientists and Engineers (PECASE)](https://www.nsf.gov/honorary-awards/pecase/recipients/percy-liang)**, 2019 — the highest honor the US government gives early-career scientists
- **[IJCAI Computers and Thought Award](https://ijcai.org/about/awards/computers_and_thought)**, 2016 — AI's premier award for outstanding young researcher (past winners: Alan Kay, Ed Feigenbaum, Drew McDermott, etc.)
- **[NSF CAREER Award](https://www.nsf.gov/funding/pgm_summ.jsp?pims_id=503214)**, 2016
- **[Alfred P. Sloan Research Fellowship](https://sloan.org/fellowships)**, 2015
- **[Microsoft Research Faculty Fellowship](https://www.microsoft.com/en-us/research/academic-program/microsoft-research-faculty-fellowship/)**, 2014
- **Best Paper Awards** at: ACL, EMNLP, ICML (2017 — influence functions), COLT, ISMIR (music), CHI, UIST (Generative Agents), RSS (Robotics)
- **IOI** (International Olympiad in Informatics): bronze and silver medals — rare crossover between competitive programming and research academia

## Teaching & Courses

- **[CS 221: Artificial Intelligence: Principles and Techniques](https://cs221.stanford.edu/)** — Stanford's intro AI course
- **[CS 324: Advances in Foundation Models](https://cs324.stanford.edu/)** — deep dive on foundation models
- **[CS 336: Language Models from Scratch](https://cs336.stanford.edu/)** — understanding LLMs by building them from first principles. This course is particularly unusual — almost no university teaches "build your own LLM" at this depth.

## Key Collaborators

### Core Collaborators (already in graph)
- **[[Joon Sung Park]]** ⭐⭐⭐ — PhD student 2025, Generative Agents lead author, now startup founder. The student whose work became the most-read paper of 2023. Liang co-advised with Bernstein.
- **[[Michael Bernstein]]** ⭐⭐⭐ — Stanford HCI professor, Generative Agents co-author, CRFM adjacent. The HCI voice that made the Generative Agents paper land outside ML.

### Key Collaborators Worth Adding
- **[[Rishi Bommasani]]** ⭐⭐ — PhD student 2025 (co-advised with Dan Jurafsky). Led the Foundation Models report and HELM. Now senior research scholar at Stanford HAI. The intellectual architect of CRFM's public-facing work. Prolific on AI policy and transparency.
- **[[Jacob Steinhardt]]** ⭐⭐⭐ — PhD student 2018 (co-advised with John Duchi). Now assistant professor at UC Berkeley and founder of [Transluce](https://transluce.org/) (AI interpretability startup). One of the most serious AI safety researchers. His "forecasting" work on ML progress is widely cited.
- **[Pang Wei Koh](https://koh.pw/)** ⭐⭐ — PhD student 2022. Influence functions paper, now assistant professor at University of Washington. Works on ML robustness and subpopulation performance.
- **[Pranav Rajpurkar](https://pranavrajpurkar.com/)** ⭐⭐ — PhD student 2021 (co-advised with Andrew Ng). SQuAD dataset. Now associate professor at Harvard Medical School, applying AI to healthcare. Unusually fast academic ascent.
- **[Tatsunori Hashimoto](https://thashim.github.io/)** ⭐⭐ — postdoc 2019. Now assistant professor at Stanford CS. Robustness, distribution shift, LLM evaluation. Frequent Liang paper co-author.
- **[Yuhuai (Tony) Wu](https://yuhuaiwu.github.io/)** — postdoc 2023. Now co-founder of **xAI** (Elon Musk's AI company). Signal: Liang's lab pipeline has reached even xAI.
- **[He He](https://hhexiy.github.io/)** — postdoc. Now assistant professor at NYU. Language model robustness, adversarial NLP.
- **[Mina Lee](https://minalee-research.github.io/)** — PhD 2023. Now assistant professor at University of Chicago (next to [[James Evans]]). HCI + NLP — writing assistance systems, human-AI collaboration.
- **[Li Fei-Fei](https://profiles.stanford.edu/fei-fei-li)** — Stanford HAI co-director. Foundation Models paper co-author. Co-signed the California AI Policy report 2025. The central node connecting Liang to Stanford's AI-policy machine.
- **[Michael I. Jordan](https://people.eecs.berkeley.edu/~jordan/)** — PhD advisor at Berkeley. The godfather of statistical ML. Having Jordan as an advisor is itself a signal of Liang's technical pedigree.
- **[Dan Klein](https://people.eecs.berkeley.edu/~klein/)** — PhD co-advisor at Berkeley. NLP, probabilistic parsing. Explains Liang's deep linguistic foundations.

## The Lab as a Pipeline

Liang's lab has been extraordinarily productive not just in papers but in people. A sampling of where PhD students and postdocs have ended up:

- **OpenAI**: Daniel Selsam, Fereshte Khani, Shibani Santurkar, Dimitris Tsipras, Ananya Kumar, Michi Yasunaga, Shiori Sagawa, Yann Dubois, Nelson Liu
- **xAI** (Elon Musk): Yuhuai (Tony) Wu (co-founder)
- **Google DeepMind**: Kelvin Guu
- **Meta**: Sida Wang, (Sang) Michael Xie, Niladri Chatterji
- **Top universities** (CMU, UW, NYU, Harvard, USC, Cornell, Columbia, Georgia Tech, ETH, Berkeley, Stanford): 12+ faculty positions
- **Startups**: Joon Sung Park (generative agents startup), Transluce (Jacob Steinhardt)

This is exceptional placement. The Liang lab is a known training ground for foundation model researchers.

## Conference / Venue Circuit

**Primary venues:**
- **[NeurIPS](https://neurips.cc/)** — deep learning and ML systems work (DoReMi, etc.)
- **[ICML](https://icml.cc/)** — core ML theory and applications (influence functions Best Paper here)
- **[ICLR](https://iclr.cc/)** — learning representations
- **[ACL](https://aclweb.org/)** / **[EMNLP](https://aclweb.org/portal/emnlp)** / **[NAACL](https://aclweb.org/naacl)** — NLP venues (semantic parsing, SQuAD)
- **[COLT](https://learningtheory.org/)** — computational learning theory

**HCI crossover (unusual for ML):**
- **[UIST](https://uist.acm.org/)** (User Interface Software and Technology) — Generative Agents (Best Paper)
- **[CHI](https://chi.acm.org/)** (Computer-Human Interaction) — Mina Lee's writing assistance work

**Robotics:**
- **[RSS](https://roboticsconference.org/)** (Robotics: Science and Systems) — recent robotics evaluation work

**Policy forums:**
- Congressional testimony, EU AI Act consultations, multi-jurisdictional government engagement through CRFM
- California AI Policy Report (2025) with Li Fei-Fei, Dawn Song, others

**Media:**
- [The Gradient Podcast](https://thegradient.pub/) — interview on machine learning research
- [TWIML AI Podcast](https://twimlai.com/) — foundation models
- [Andrey Kurenkov interview](https://www.skynettoday.com/editorials/liang) on foundation models research vision

*Note: Liang does not appear at art/media/interdisciplinary venues — he's purely academic/policy circuit. But his students and collaborators do bridge (Joon Sung Park now leads an HCI-adjacent startup; Mina Lee is at Chicago near HCI researchers).*

## Ideas & Intellectual Positions

**The "foundation model" concept (2021)**  
Before Liang et al.'s naming, the field talked about "pretrained models," "large language models," "GPT-style models." The term "foundation model" was a deliberate intervention: these models are a *new paradigm*, not just bigger versions of old models. They're trained once, deployed everywhere. They carry biases and capabilities that propagate at scale. This naming has done real intellectual work — it unified disparate communities (NLP, vision, robotics, law, medicine) around a shared object of study.

**Evaluation should be holistic**  
HELM's argument: evaluating a model on one task (MMLU, HellaSwag) tells you almost nothing useful. Real evaluation needs multiple scenarios, multiple metrics (not just accuracy), and transparency about methodology. This is a political position as much as a technical one — against the leaderboard culture that lets companies cherry-pick metrics.

**Transparency as precondition for governance**  
FMTI's argument: you cannot regulate what you cannot see. The 100-indicator transparency framework is designed to give regulators and the public specific things to demand. No developer currently discloses downstream impact — that's a governance failure, not just a disclosure gap.

**Open science as political act**  
Marin is Liang's strongest statement on open AI development: build models in public, share every experiment, make mistakes visible. This directly counters the OpenAI model (closed development, selective disclosure). It's Liang betting that open science produces better and safer outcomes.

**Data attribution matters**  
The influence functions work (2017) and subsequent data attribution research address a fundamental question: *what in the training data caused this model behavior?* This is becoming critical for copyright law, bias auditing, and safety verification.

**Copyright and fair use require new frameworks**  
"Foundation Models and Fair Use" is one of the first serious academic treatments of training-data copyright. The conclusion is uncomfortable: fair use is not a blanket shield. Models that reproduce training data in market-affecting ways may face liability. This intersects with ongoing lawsuits (Getty Images v. Stability AI, New York Times v. OpenAI).

## Why Interesting to Amber

### Machine Behavior as Science
Liang's approach to foundation models is scientific in Rahwan's sense: studying AI systems as objects in the world with behaviors, capabilities, failure modes — not just building tools. HELM is essentially behavioral ecology for LLMs. This aligns directly with [[Iyad Rahwan]]'s "machine behavior" program.

### Social Simulation Connection
Generative Agents is *the* technical paper behind the social simulation of AI agents — directly relevant to any research on how AI populations behave in simulated societies. The architecture (observation → memory → reflection → planning) is now widely used. Percy Liang's lab created the computational substrate that Amber's work on machine behavior in social contexts requires.

### HCI-ML Bridge
The Generative Agents paper was explicitly designed as a CHI/UIST submission — it's ML research built for HCI audiences. The co-authorship with Michael Bernstein shows the intentional bridge between CS systems work and human-computer interaction. Mina Lee (PhD 2023) continues this bridge, now at UChicago.

### Foundation Models Governance
CRFM is the academic counterweight to industry-driven AI development. The policy work (FMTI, California AI Policy Report, government engagement) represents exactly the "critical computing" angle Amber values — asking who benefits, who's harmed, what accountability looks like.

### Open Science Model
Marin is an interesting experiment: what does it look like to build foundation models publicly, with all decisions documented? This is a form of research infrastructure building with political stakes — relevant to Amber's interest in communities as research infrastructure.

## New Nodes to Research

**People:**
- **[[Rishi Bommasani]]** (stub created) — Foundation Models + HELM architect, now Stanford HAI. Bridge between technical and policy.
- **[[Jacob Steinhardt]]** (stub created) — AI safety, Transluce, Berkeley prof. Deep ML theory + safety forecasting.
- **[Mina Lee](https://minalee-research.github.io/)** — now at UChicago. Writing AI, HCI+NLP. Potentially interesting for human-AI collaboration research.

**Communities:**
- **[[CRFM Stanford]]** (stub created) — the organizational unit around foundation models research at Stanford
- **[[Stanford HAI]]** (stub created) — Human-Centered AI, umbrella for multiple AI research threads

## Research Log

*2026-02-26: Deep research complete. Primary sources: cs.stanford.edu/~pliang/, crfm.stanford.edu, profiles.stanford.edu/percy-liang, Wikipedia, arxiv.org for all cited papers, marin.community. All URLs verified. Stubs created for Rishi Bommasani, Jacob Steinhardt, CRFM Stanford, Stanford HAI.*
