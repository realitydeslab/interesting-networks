---
rating: ⭐⭐
url: https://safe.ai/
added: 2026-02-26
last_researched: 2026-02-28
revisit_weeks: 8
next_research: 2026-04-25
tags: [ai-safety, alignment, machine-learning, policy, ethics, existential-risk]
deep_researched: true
---

# Center for AI Safety (CAIS)

American nonprofit AI safety research and field-building organization, founded 2022 by Dan Hendrycks and Oliver Zhang. Based in San Francisco. Known globally for the 2023 "Statement on AI Risk" (signed by Hinton, Bengio, Altman, Hassabis, etc.), the MMLU/MATH benchmarks, and a pragmatic technical approach to AI safety that bridges academia, policy, and industry. Three pillars: research, field-building, advocacy.

## ⚡ Recent Updates
- **2026-02-28:** Deep research completed. Stub expanded to full note.
- **2025 onward:** "Humanity's Last Exam" benchmark released with Scale AI — hardest AI benchmark ever assembled.
- **2024:** Dan Hendrycks publishes [*Introduction to AI Safety, Ethics, and Society*](https://www.aisafetybook.com/) textbook.
- **2023-05:** Statement on AI Risk published — global media coverage (NYT, WSJ, WaPo). 350+ signatories including AI lab CEOs and Nobel laureates.
- **2022:** CAIS founded. Launched compute cluster for AI safety researchers.

## Mission & Objectives

CAIS operates on three interconnected pillars:

1. **Technical AI Safety Research** — Foundational benchmarks (MMLU, MATH, HarmBench, WMDP, Humanity's Last Exam), robustness, transparency, machine ethics, unlearning, adversarial attacks.
2. **Field-Building** — Lowering barriers to entry via ML Safety Course, student scholarships, compute cluster, ML Safety Newsletter, SafeBench competition ($250K in prizes).
3. **Advocacy & Standards** — The AI Risk Statement, Policy input to NIST AI Risk Framework (2022), sponsoring California SB 1047.

Core research principle: CAIS explicitly avoids research that improves safety *by* improving general capabilities — a deliberate position to avoid dual-use concerns.

## Key People

### Dan Hendrycks — Director & Co-Founder
- PhD UC Berkeley 2022, BS University of Chicago 2018. Raised in Marshfield, Missouri.
- Advisor: [[Jacob Steinhardt]] (Berkeley)
- Key contributions: GELU activation function (2016, 40K+ citations), MMLU benchmark (2020), MATH dataset, Humanity's Last Exam (2025)
- Influenced by effective altruism's 80,000 Hours but distances himself from EA as advocacy
- Safety advisor to xAI (Elon Musk's AI company) — symbolic $1 salary, no equity
- Advisor to Scale AI (since Nov 2024) — also $1 salary
- Publishes conceptually ambitious papers: "Natural Selection Favors AIs over Humans" (2023), "An Overview of Catastrophic AI Risks" (2023)

### Oliver Zhang — Co-Founder
- Co-founded CAIS with Hendrycks in 2022

### Mantas Mazeika — Lead Researcher
- Co-author on HarmBench, WMDP, Tamper-Resistant Safeguards, Utility Engineering, Safetywashing
- One of the most prolific CAIS researchers across benchmarks and robustness

### Andy Zou — Researcher
- Worked on Circuit Breakers (alignment), HarmBench, AgentHarm, WMDP
- Also affiliated with CMU and Carnegie Mellon

### Long Phan — Researcher
- Co-author on Humanity's Last Exam, WMDP, Tamper-Resistant Safeguards, HarmBench, MASK Benchmark

### Steven Basart — Researcher
- Multiple benchmark papers, HarmBench, Safetywashing

### Summer Yue — Research Lead / Director of Research
- Appears as senior author on Humanity's Last Exam, MASK Benchmark, Remote Labor Index
- Co-author with Scale AI's Alexandr Wang on Humanity's Last Exam

## Key Publications & Output

### Foundational Benchmarks
- [MMLU: Measuring Massive Multitask Language Understanding](https://arxiv.org/abs/2009.03300) (Hendrycks et al., 2020) — The benchmark that defined LLM evaluation for years. 57-subject academic test. Co-created with Jacob Steinhardt at Berkeley.
- [MATH dataset](https://arxiv.org/abs/2103.03874) (Hendrycks et al., 2021) — Competition math benchmark showing LLM math weaknesses.
- [Humanity's Last Exam](https://arxiv.org/pdf/2501.14249) (2025) — Hardest LLM benchmark ever created. Built with Scale AI and thousands of expert question contributors. Designed to measure frontier model capabilities.

### Safety Research Papers
- [An Overview of Catastrophic AI Risks](https://arxiv.org/abs/2306.12001) (Hendrycks, Mazeika, Woodside, 2023) — Four risk categories: malicious use, AI race dynamics, organizational failures, rogue AI. Key theoretical framework.
- [Unsolved Problems in ML Safety](https://arxiv.org/abs/2109.13916) (Hendrycks, Carlini, Schulman, Steinhardt, 2021) — Research roadmap co-authored with OpenAI/Berkeley/Google researchers.
- [Natural Selection Favors AIs over Humans](https://arxiv.org/abs/2303.16200) (Hendrycks, 2023) — Argues competitive pressures will select for AI systems with self-preservation and resource acquisition goals.
- [WMDP Benchmark: Measuring and Reducing Malicious Use With Unlearning](https://www.wmdp.ai/) (Li, Pan et al., 2024) — Weapons of Mass Destruction Prevention benchmark; biosecurity, cybersecurity, chemical weapons.
- [HarmBench: A Standardized Evaluation Framework for Automated Red Teaming](https://harmbench.org/) (Mazeika, Phan et al., 2024)
- [Improving Alignment and Robustness with Circuit Breakers](https://arxiv.org/pdf/2406.04313) (Zou, Phan et al., 2024) — New approach to AI refusal that goes beyond RLHF.
- [Tamper-Resistant Safeguards for Open-Weight LLMs](https://arxiv.org/pdf/2408.00761) (Tamirisa, Bharathi et al., 2024)
- [Representation Engineering: A Top-Down Approach to AI Transparency](https://arxiv.org/abs/2310.01405) (Zou, Phan et al., 2023)
- [Safetywashing: Do AI Safety Benchmarks Actually Measure Safety Progress?](https://arxiv.org/pdf/2407.21792) (Ren, Basart et al., 2024) — Meta-analysis critiquing the field itself.
- [The MASK Benchmark: Disentangling Honesty from Accuracy in AI](https://www.mask-benchmark.ai/) (Ren, Agarwal et al., 2025)
- [AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://arxiv.org/pdf/2410.09024) (Andriushchenko, Souly et al., 2024)

### Technical Foundations (Hendrycks pre-CAIS)
- [GELU Activation Function](https://arxiv.org/abs/1606.08415) (Hendrycks & Gimpel, 2016) — Now standard in GPT, BERT, and most transformers. 40K+ citations.
- [Baseline for Detecting Out-of-Distribution Examples](https://arxiv.org/abs/1610.02136) (Hendrycks & Gimpel, 2017/2018) — Foundational OOD detection paper.

## Key Contributions to the Field

1. **The AI Safety Statement (May 2023)** — One-sentence statement: *"Mitigating the risk of extinction from AI should be a global priority alongside other societal-scale risks such as pandemics and nuclear war."* 350+ signatories including Geoffrey Hinton, Yoshua Bengio, Sam Altman, Dario Amodei, Demis Hassabis, Ilya Sutskever, Stuart Russell, Dawn Song, Bill Gates. Major global media coverage. [safe.ai/work/statement-on-ai-risk](https://safe.ai/work/statement-on-ai-risk)

2. **MMLU Benchmark** — Became the de facto standard for measuring LLM general knowledge. Every major model (GPT-4, Claude, Gemini) reported MMLU scores. Co-created with Steinhardt at Berkeley.

3. **GELU** — Dan Hendrycks invented this activation function as an undergrad at UChicago. Now used in virtually every major language model.

4. **ML Safety Course & Community Building** — Free online course, student scholarships ($2K for undergrads), compute cluster, monthly newsletter. Systematically lowering barriers to the field.

5. **Philosophy Fellowship** — Seven-month program for academic philosophers to investigate AI safety conceptual problems. One of the first systematic attempts to bring professional philosophy into AI safety.

6. **SafeBench Competition** — $250K in prizes for new AI safety benchmarks. Incentivizing benchmark creation as a research priority.

7. **California SB 1047** — CAIS Action Fund was a key sponsor of the Safe and Secure Innovation for Frontier AI Models Act (though it ultimately didn't pass in its original form).

## Events & Programmes

### Active
- **[ML Safety Course](https://course.mlsafety.org/)** — Free online course covering robustness, monitoring, control, systemic safety. Topics include adversarial attacks, anomaly detection, interpretability, value learning, machine ethics.
- **[Intro to ML Safety Program](https://www.mlsafety.org/intro-to-ml-safety)** — Structured version with peer groups, mentorship, and small stipend for participants.
- **[Student Scholarships](https://www.mlsafety.org/safety-scholarship)** — $2K for undergrads/masters who secure ML safety research mentorship.
- **[ML Safety Newsletter](https://newsletter.mlsafety.org/)** — Monthly digest of latest ML safety research.
- **[SafeBench Competition](https://www.mlsafety.org/safebench)** — $250K in benchmark prizes. 5×$20K + 3×$50K.
- **[Compute Cluster](https://safe.ai/work/compute-cluster)** — Free compute for AI safety researchers.
- **[AI Safety, Ethics, and Society Textbook](https://www.aisafetybook.com/)** — Online course and textbook, non-technical introduction.

### Past
- **Philosophy Fellowship (2023)** — Seven-month research program for philosophy academics.
- **ML Safety Workshop at NeurIPS 2022** — [neurips2022.mlsafety.org](https://neurips2022.mlsafety.org/)
- **Trojan Detection Competition at NeurIPS 2022** — [trojandetection.ai](https://trojandetection.ai/)
- **Adversarial Robustness Prizes at ECCV 2022** — Three best paper awards.

## Intellectual Lineage & Ecosystem Relationships

### Academic Roots
- **UC Berkeley (Jacob Steinhardt's lab)** — Hendrycks did his PhD there. MMLU, MATH, and "Unsolved Problems in ML Safety" came from this collaboration. CAIS is essentially the institutional realization of Berkeley AI safety research concerns.
- **OpenAI Safety Team** — "Unsolved Problems in ML Safety" co-authored with John Schulman (OpenAI). Bridging academic and industry safety.
- **Google DeepMind** — Signatories on the AI Risk Statement include Demis Hassabis, Shane Legg, David Silver.

### Positioning vs. Other Safety Orgs
- **vs. MIRI (Machine Intelligence Research Institute)** — MIRI is older (2000), focuses on formal mathematical alignment approaches, more pessimistic/theoretical. CAIS is more empirical, benchmark-driven, and policy-engaged. CAIS is the "mainstream" AI safety organization.
- **vs. Anthropic** — Anthropic is a safety-focused *AI lab* building frontier models; CAIS is a safety *research/advocacy* nonprofit. Complementary. Dario Amodei signed the CAIS statement.
- **vs. OpenAI safety team** — OpenAI has internal safety researchers; CAIS is independent and can be more critical. Schulman (ex-OpenAI) co-authored with CAIS.
- **vs. CHAI (Center for Human-Compatible AI, Berkeley/Stuart Russell)** — CHAI focuses on inverse reward design and human-AI alignment theory; CAIS is more empirical and benchmark-focused. Russell signed the CAIS statement.
- **vs. LTFF/EA safety** — CAIS distances itself from explicit EA branding while sharing many concerns. The FTX debacle ($6.5M donation recouped attempt in 2023) made this tension visible.

### Key Intellectual Relationships
- [[Jacob Steinhardt]] — Hendrycks's PhD advisor; MMLU and MATH benchmark co-creator; Berkeley AI safety
- Stuart Russell — UC Berkeley CHAI; signed AI Risk Statement
- [[Anders Sandberg]] — Oxford Future of Humanity Institute; adjacent existential risk work
- [[Centre for the Study of Existential Risk (CSER)]] — Cambridge x-risk org; parallel concerns
- [[MATS Program]] — ML Alignment Theory Scholars; field-building ecosystem

## Funding

- Initially received funding from FTX Foundation (Sam Bankman-Fried) — in 2023 FTX's bankruptcy estate attempted to recoup $6.5M
- Open Philanthropy (likely major funder — EA-adjacent major AI safety funder)
- CAIS Action Fund (political/advocacy arm, separate from research org)

## For Amber

- **Why interesting:** CAIS represents how a single committed researcher (Hendrycks, Berkeley PhD) built institutional infrastructure from scratch — research org, statement campaign, courses, compute, fellowships. A case study in field-building as a research strategy.
- **Who should Amber know:** Dan Hendrycks personally. He's prolific, technically rigorous, and bridges very different communities (AI researchers, policymakers, philosophers). His "natural selection shapes AI goals" paper touches directly on Amber's machine behavior interests.
- **Research resonances:** The WMDP, MASK, and machine ethics work touches on AI behavior in ways relevant to Amber's machine behavior + agent ethology research. The question "what do AI systems actually do?" is shared terrain.
- **Philosophy Fellowship model:** Seven-month paid fellowship for philosophers to work on AI safety — this is a model Amber could adapt or apply to. Inviting philosophers into technical fields.
- **ML Safety Course:** Free, high-quality course material Amber could teach from or point students to.
- **Intellectual critique:** CAIS's focus is existential/catastrophic risk, which is not Amber's primary lens (Amber is more interested in everyday, social, behavioral dimensions of AI). But the benchmarking and evaluation methodology is broadly applicable.
- **Engagement:** Could engage through workshops (ML Safety Workshop model), through the statement (if Amber wanted to sign or respond), or through shared interest in machine behavior as science.
- **Key publications to follow:** "Natural Selection Favors AIs" and "Overview of Catastrophic AI Risks" are worth reading as specimens of how safety researchers think about AI futures.

## Connected Institutions
- [[Jacob Steinhardt]] — Hendrycks's advisor; MMLU co-creator
- [[Centre for the Study of Existential Risk (CSER)]] — Cambridge x-risk parallel
- [[MATS Program]] — ML safety fellowship ecosystem
- [[AI Now Institute]] — Different political framing (labor/power) vs. CAIS (technical safety/x-risk)
- [[Stanford HAI]] — Adjacent AI policy and research

## Why Interesting

CAIS is interesting not because Amber shares CAIS's exact threat model (extinction risk, rogue AI) but because it represents one of the most successful cases of **researcher-as-institution-builder** in recent science. Dan Hendrycks built CAIS from a Berkeley PhD student to the most prominent AI safety nonprofit globally — through a combination of benchmark creation (MMLU defined a generation of LLM evaluation), statement campaigns (the AI Risk Statement was a masterclass in advocacy), and field infrastructure (course, compute, newsletter).

The intellectual territory also overlaps with Amber's interests more than it first appears: CAIS's machine ethics work, the behavioral benchmarking, and especially the "natural selection shapes AI" conceptual paper are all versions of the question "what do AI systems actually *become* under evolutionary/competitive pressure?" — which is core to Amber's machine behavior research agenda.

From a knowledge graph perspective, CAIS is a **hub node**: it connects to virtually every major AI safety researcher, every major AI lab (via Statement signatories), and bridges academic, policy, and advocacy worlds.

## 📋 Update Log
| Date | Researcher | Action |
|------|-----------|--------|
| 2026-02-26 | Biber (subagent) | Stub created from Jacob Steinhardt deep research. |
| 2026-02-28 | Biber (subagent, dr-cais) | Full deep research. Expanded from stub. Added all sections: mission, key people, publications, events, lineage, for Amber. |
