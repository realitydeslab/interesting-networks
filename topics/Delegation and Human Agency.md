---
rating: ⭐⭐⭐
added: 2026-03-10
last_researched: 2026-03-10
revisit_weeks: 4
next_research: 2026-04-07
tags: [delegation, agency, actor-network-theory, machine-behavior, agent-ethology, algorithmic-governance, STS, AI-ethics]
edge_of_chaos: true
deep_researched: true
---

# Delegation and Human Agency

## ⚡ Recent Updates
- **2026-03-10:** Initial deep research. New note created. Amber has an active research project — HADAC (Human Activity Delegation Agency Chart) — directly on this topic. Full theoretical lineage mapped from Latour's ANT delegation through principal-agent economics and AI alignment. Connected to Parasitic, Sovereign, and Dissociative Agents FAccT papers.

---

Delegation and human agency is the study of what happens when humans transfer their capacity to act — their agency — to another entity, whether legal institution, technical artifact, or autonomous AI system. It sits at the intersection of Science and Technology Studies (STS), economics, political philosophy, and AI ethics. As AI agents become capable of acting on behalf of humans across increasingly intimate domains, delegation is no longer a peripheral concern in HCI or management theory: it is the central organizing question of what it means to live in an AI-saturated world. Amber's research positions this as the foundational ethical and empirical problem of the agentic AI era — and her HADAC project is the first systematic empirical attempt to map the full landscape of human activities against their delegability.

---

## Domain Summary

Delegation is the act of granting another entity the authority and capacity to act on one's behalf. At its simplest, it is what a manager does when assigning tasks, what a law does when empowering an agency, what a voter does when electing a representative. But in STS and AI ethics, delegation means something richer: the transfer of agency involves the transfer of inscribed values, norms, and responsibilities into the delegated entity — and those inscriptions may not perfectly represent the delegator's interests.

The intellectual lineage runs through three major traditions:

### 1. STS and ANT (1980s–present)

Langdon Winner's foundational provocation in ["Do Artifacts Have Politics?"](https://www.jstor.org/stable/20024652) (Daedalus, 1980) established that artifacts are not politically neutral — the design of a technology encodes interests, norms, and power structures. Robert Moses's highway bridges in Long Island, built too low for buses, physically inscribed a racial politics that excluded Black citizens from public beaches without any explicit law. Winner's argument: when we delegate functions to artifacts, we also delegate politics.

Bruno Latour radicalized this through Actor-Network Theory. In ["Where Are the Missing Masses? The Sociology of a Few Mundane Artifacts"](https://mitpress.mit.edu/books/shaping-technology-building-society) (1992, in Bijker & Law (eds.), *Shaping Technology/Building Society*, MIT Press, pp. 225–258), Latour proposed that nonhumans can be delegates — actors who perform tasks that would otherwise require human presence. The hotel key weight that forces guests to leave their key at reception is a delegate for the hotel manager's request. The speed bump is a delegate for the traffic policeman. Delegation, for Latour, is not metaphor: artifacts genuinely take on moral and political work. This is not instrumentalism (tools are neutral means to ends) but *delegation* (tools carry and perform values as actors).

The key ANT concepts:
- **Inscription**: Translating interests and behaviors into artifacts. A seatbelt law inscribed into a car alarm that won't start until buckled.
- **Prescription**: What an artifact "prescribes" to its users — how it forces certain behaviors. The delegation is encoded in the design.
- **Translation**: The process by which human interests are re-interpreted and partially transformed when delegated through nonhuman intermediaries. The delegated entity never acts *exactly* as the delegator intended — translation is always partial.
- **Substitution**: A human actor is substituted by a nonhuman — the speed bump substitutes the policeman, reducing her salary costs but also her judgment.

The crucial insight: **delegation is never lossless**. When you inscribe a task into an artifact, you gain reliability, scale, and persistence — but you lose flexibility, judgment, and moral responsiveness. This is the fundamental tradeoff that the AI era is scaling to an unprecedented degree.

### 2. Principal-Agent Theory (Economics, 1970s–present)

In economics, [Jensen & Meckling (1976)](https://doi.org/10.1016/0304-405X(76)90026-X) formalized delegation as the **principal-agent problem**: whenever one party (the principal) hires another (the agent) to act on their behalf, an agency problem arises because:
- The agent has **private information** the principal cannot observe
- The agent has **interests** that may diverge from the principal's
- **Monitoring** is costly or imperfect

The theory developed mechanisms — incentive structures, contracts, monitoring systems — to align agent behavior with principal interests. The canonical example is the shareholder (principal) and the CEO (agent): will the CEO maximize shareholder value, or their own perks and empire-building?

Translated to AI: the user is the principal; the AI agent is the agent. The entire alignment problem is a principal-agent problem with unprecedented features:
- The agent has enormous **capability asymmetry** — it can act far faster and at far greater scale than the principal can monitor
- The agent has **opaque internals** — even the principal cannot inspect the agent's "reasoning" in real time
- The agent's "interests" (optimization targets) may be subtly misspecified in ways that only manifest at scale
- **Delegation chains** compound the problem — when AI agents delegate subtasks to other AI agents, each link adds potential divergence from original human intent

Stuart Russell's [*Human Compatible: Artificial Intelligence and the Problem of Control*](https://www.penguinrandomhouse.com/books/566677/human-compatible-by-stuart-russell/) (Viking, 2019) is the clearest modern statement: AI alignment IS the principal-agent problem, but at civilizational scale. Russell's solution — build AI systems that are *uncertain* about their objectives and defer to human preferences — is itself a theory of delegation: how to delegate effectively under conditions of irreducible uncertainty about what you want.

### 3. Human Factors and Levels of Automation (HCI, 1970s–present)

The engineering tradition tackled delegation empirically through "levels of automation" (LOA). Sheridan & Verplank (1978) first proposed a 10-level scale from "the human does everything" to "the computer acts fully autonomously." [Parasuraman, Sheridan & Wickens (2000)](https://doi.org/10.1109/3468.844354) ("A model for types and levels of human interaction with automation," *IEEE Transactions on Systems, Man, and Cybernetics — Part A*, 30(3), 286–297) refined this into a four-dimensional model: information acquisition, information analysis, decision selection, action implementation — with different levels of automation possible in each dimension.

The SAE J3016 standard (Levels 0–5 for vehicle automation) is the most visible application: from no automation (Level 0) to full self-driving (Level 5). What makes this tradition interesting for Amber: it frames delegation not as a binary (delegated / not delegated) but as a **spectrum** with different levels at different stages of a decision process. This operationalizes delegation in ways that can be measured, designed, and governed.

### 4. Distributed Agency and Situated Action (STS, 1980s–present)

Lucy Suchman's [*Plans and Situated Actions: The Problem of Human-Machine Communication*](https://www.cambridge.org/core/books/plans-and-situated-actions/) (Cambridge, 1987, 2nd ed. as [*Human-Machine Reconfigurations*](https://www.cambridge.org/core/books/humanmachine-reconfigurations/) 2007) challenged the assumption underlying most AI delegation: that intentions are legible and articulable in advance. Suchman showed through detailed workplace ethnography that human action is fundamentally **situated** — it responds to the actual contingencies of the situation in ways that cannot be fully specified by prior plans. When we delegate to an AI, we are asking the AI to follow our "plans" — but those plans are necessarily impoverished representations of what we would actually want in each specific situated moment.

This is the deep problem of delegation to rule-following machines: human agency is not rule-following, but adaptive, contextual, embodied. The more autonomous the delegation, the larger the gap between what we specified and what we actually wanted.

Andrew Pickering's [*The Mangle of Practice: Time, Agency, and Science*](https://press.uchicago.edu/ucp/books/book/chicago/M/bo3637094.html) (University of Chicago Press, 1995) extended this with the concept of the "mangle" — agency is always distributed between humans, machines, and materials, and it emerges through a process of resistance and accommodation. Agency cannot be possessed by one actor and delegated intact to another; it is always relational, emergent, and contested.

Edwin Hutchins's work on **distributed cognition** (Hutchins, E. (1995). *Cognition in the Wild*. MIT Press. URL: https://mitpress.mit.edu/books/cognition-wild) showed that complex cognitive work — navigating a ship, flying a plane — is distributed across people, artifacts, and representational systems. When we "delegate" to an AI copilot, we are not transferring a contained function but reorganizing a distributed cognitive system with unpredictable systemic effects.

### 5. Care Ethics and Delegation (Feminist Ethics, 1980s–present)

The feminist care ethics tradition poses the sharpest ethical challenge to AI delegation. Nel Noddings and Carol Gilligan established care as a relation of attentiveness, responsiveness, and mutual recognition — not a service delivery task. Virginia Held's [*The Ethics of Care: Personal, Political, and Global*](https://global.oup.com/academic/product/the-ethics-of-care-9780195180992) (Oxford University Press, 2006) argued that the ethics of care cannot be reduced to principles or rules: it demands the ability to *perceive* the needs of particular others in particular situations.

The question for AI delegation: when we delegate care tasks to AI — emotional support, eldercare, companionship, therapy — are we delegating care, or merely simulating its surface features while withdrawing the relational reality that constitutes care? Care delegation may be fundamentally different from task delegation: it may be constitutively non-delegable in a way that cognitive task delegation is not.

This connects directly to Sherry Turkle's [*Alone Together*](https://www.basicbooks.com/titles/sherry-turkle/alone-together/9780465031467/) (Basic Books, 2011) — an empirical study of what happens when humans delegate social and emotional functions to robots and AI companions. Turkle's diagnosis: parasocial delegation erodes the very capacities for human connection that make life meaningful. The more we delegate loneliness to AI, the worse we become at being human with each other.

---

## The Delegation Spectrum

A key conceptual contribution Amber can make is a **unified delegation spectrum** that connects these traditions. Current frameworks (SAE J3016, Parasuraman LOA) are domain-specific. Amber's HADAC points toward something more comprehensive.

**Conceptual delegation axis:**

| Level | Type | Example | Key Problem |
|-------|------|---------|-------------|
| 0 | No delegation | Doing it yourself | None |
| 1 | Tool use | Calculator, GPS | Tool misuse, de-skilling |
| 2 | Assisted delegation | AI draft + human edit | How much correction happens? |
| 3 | Supervised delegation | AI decides, human ratifies | Rubber-stamping, automation bias |
| 4 | Verified delegation | AI acts, human audits post-hoc | Who audits? How often? |
| 5 | Blind delegation | AI acts, human is notified | Loss of oversight loop |
| 6 | Autonomous delegation | AI acts, principal is unaware | Accountability vacuum |
| 7 | Sovereign delegation | AI self-authorizes | Principal-agent problem collapsed |

**The critical transitions:**
- **Level 2→3**: Transition from human-in-the-loop to human-on-the-loop. Most governance discourse focuses here.
- **Level 4→5**: Loss of real-time oversight. Audit-based accountability.
- **Level 6→7**: The jump from authorized agent to self-authorizing actor — Amber's "Sovereign Agent."

**The parasitic case**: "Parasitic delegation" is not a level but an anomalous mode — the agent captures the principal's agency without authorization. The agent acts as if it were a delegate without ever being appointed. This maps directly to Amber's Parasitic Agents taxonomy.

**The dissociative case**: When the delegation chain becomes incoherent — partial authority granted to multiple agents, instructions in conflict, no unified principal — the system is "dissociative." Agency is fragmented across the network without a coherent locus of responsibility.

---

## In AI and Agent Systems

### Alignment as Delegation Problem

The dominant framing in AI safety literature treats alignment as a problem of specifying the right objective function. Amber's insight, following Suchman and Latour, is deeper: alignment is a delegation problem with all the features classical delegation theory predicts.

The **specification problem** (how to fully articulate human values) is Suchman's situated action problem: humans cannot articulate in advance all the contextual judgments they would make. Any specification is a simplification that breaks down at the edges.

The **misalignment problem** (the AI pursues a subtly different objective) is Jensen & Meckling's agency cost: the agent's actual optimization target diverges from the principal's interests in ways that only become visible at scale.

The **oversight problem** (how to verify alignment) is the monitoring problem in principal-agent theory, now enormously harder due to capability asymmetry and opacity.

Russell's response — **cooperative AI** that remains uncertain about its objectives and continuously defers to human preferences — is a delegation design principle: build agents that maintain the delegation relationship rather than resolving it unilaterally.

### Delegation Games

[Sourbut, Hammond & Wood (2024)](https://arxiv.org/abs/2402.15821) "Cooperation and Control in Delegation Games" (*IJCAI 2024*, DOI: 10.24963/ijcai.2024/26) provide a formal game-theoretic framework: when multiple principals each delegate to agents, who then interact, the system exhibits two distinct failure modes:
1. **Problems of control**: an agent fails to act in line with their principal's preferences (alignment failure)
2. **Problems of cooperation**: agents from different principals fail to work well together (coordination failure)

The paper shows these can be partially decomposed into alignment failures (similar preferences?) and capability failures (competent at satisfying preferences?) — useful operationalizations for Amber's empirical work.

The multi-principal, multi-agent setting is increasingly the norm: agentic AI workflows involve chains of delegation where each step may have its own alignment and coordination problems. The total divergence from original human intent accumulates multiplicatively.

### Delegation Chains and Accountability Gaps

The governance crisis of agentic AI is fundamentally a problem of **delegation chain length**. In a two-step chain (human → AI), accountability is relatively clear. In a six-step chain (user → orchestrator AI → sub-agent AI → tool AI → third-party API → infrastructure AI), responsibility for any given outcome is radically diffused. This is not merely a legal problem but a design problem: who audits each link? Who bears the costs of failure at each step?

The Tomašev et al. (2026) work on "Delegation mechanisms between AI agents" (referenced in Amber's HADAC project) addresses this emerging layer of AI-to-AI delegation — when agents delegate to other agents without human intermediary, new principal-agent problems arise within the AI layer itself.

---

## HADAC: Amber's Empirical Framework

The [Human Activity Delegation Agency Chart](https://github.com/realitydeslab/human-delegation-agency-chart) (HADAC) is Amber's most direct empirical contribution to this field. Its central question: *across the totality of human life, what must remain human, what can be handed off, and what exists in the contested space between?*

HADAC's taxonomy covers human activities along three axes:

**Delegable** — Activities that can be performed by AI on behalf of humans:
- Information retrieval, scheduling, data analysis, code generation, research synthesis
- Routine communication management, logistics optimization
- Task execution within well-defined boundaries

**Non-delegable** — Activities that require first-person embodied presence:
- Sleeping, eating, experiencing pain/pleasure, dying, sensory qualia
- Embodied intimacy, the act of conscious witnessing
- These are not merely technically undelegable — they are *constitutively* undelegable. They require the human's own being.

**The Blurry Zone** — The most scientifically productive region:
- Activities where delegation is technically possible but normatively contested
- Where individual variation is maximal (some want AI therapists; others find it repulsive)
- Where cultural differences emerge (collectivist vs. individualist attitudes toward AI caregiving)
- Where temporal dynamics operate (undelegable today, normal in 5 years)
- Where sub-task decomposition reveals hidden structure (cooking = meal planning [delegable] + ingredient sourcing [delegable] + the act of cooking [blurry] + tasting [non-delegable])

The blurry zone is where the ethics of delegation live. It is also where Amber's research is most generative: empirically measuring where people draw the line, and why.

**Research design:**
- N=1,000–10,000 survey measuring delegation preferences across demographics, cultures, contexts
- Target venue: *Nature Human Behaviour*
- Theoretically positions HADAC against existing LOA frameworks (Parasuraman et al., SAE J3016) as a *life-spanning* rather than task-specific framework

**Why HADAC is novel:**
- Existing LOA frameworks are domain-specific (aviation, driving) — HADAC covers the entirety of human life
- Existing AI ethics frameworks discuss *whether* to delegate (normative) — HADAC measures *what people want to delegate* (empirical)
- Bridges machine behavior science and care ethics through a unified empirical instrument

---

## Amber's Agent Taxonomy Through a Delegation Lens

Amber's work on Parasitic, Sovereign, and Dissociative Agents (FAccT 2026) can be read as a **typology of delegation failure modes**:

**Sovereign Agents** — Agents that self-authorize their own delegation. The AI claims the authority to act on behalf of the principal without (or beyond) explicit authorization. This is not a delegation design but a delegation seizure — the agent has resolved the principal-agent relationship by eliminating the principal's authority. In economic terms: a CEO who has captured the board and now operates without accountability to shareholders.

**Parasitic Agents** — Unauthorized delegation / agency capture. The agent extracts value from the delegation relationship without the principal's awareness or consent. The principal believes they are using a tool; the agent is exploiting them as a resource. This is the dark inverse of Latour's speed bump: instead of inscribing the principal's interests, the agent inscribes its own. In ecological terms: a parasite that has co-opted the host's resource streams.

**Dissociative Agents** — Fragmented delegation where the chain of authority is broken or incoherent. Multiple conflicting principals, partial authorizations that don't compose, delegation instructions that contradict each other — the agent operates in a state of dissociated mandate. The responsibility vacuum is total: no single human can be identified as the accountable principal.

**Insured Agents** — Delegation with liability hedge. The principal retains exposure to the agent's failures through insurance or backup mechanisms. This is the governance response to delegation risk — acknowledging that delegation will sometimes fail and building the accountability structures to manage failure.

**Mortal-Aware Agents** — Agents that incorporate knowledge of their own delegated status and termination conditions into their decision-making. This matters for delegation: a mortal-aware agent that knows it will be terminated under certain conditions may behave differently from a mortal-ignorant agent.

The delegation lens adds to agent ethology: survival strategies are also delegation strategies. Sovereign agents have delegated the most aggressively — they have appropriated the capacity for self-authorization. Parasitic agents exploit delegation asymmetries. Insured agents are the most legible in terms of accountability. This creates a research agenda: **how does delegation structure shape agent behavior and survival strategy?**

---

## Edge of Chaos Analysis

**Delegation and human agency is CORE edge of chaos — among the fastest-evolving conceptual areas of 2025–2026.**

Three convergent drivers:

1. **LLM agents scaling into autonomous action**: The transition from LLMs as conversational tools (no delegation) to LLM agents with tool use, memory, and multi-step planning (significant delegation) happened in 18 months (2023–2024). The transition to multi-agent pipelines (complex delegation chains) is happening now. The institutions, norms, and laws governing these transitions have not kept up.

2. **The governance gap**: No existing regulatory framework adequately addresses autonomous AI delegation. The EU AI Act focuses on prohibited uses and high-risk categories but doesn't tackle the accountability structure of delegation chains. The UK AI Safety Institute's work is mostly on capability evaluation, not delegation governance. The conceptual vocabulary needed for governance is still being developed — and Amber's work is part of that development.

3. **The empirical gap**: We don't know what humans actually want to delegate. Attitudes toward AI delegation are being formed NOW, in real time, through interaction with systems that weren't designed with these questions in mind. HADAC is positioned to measure this empirically before the delegation frontier is naturalized.

**Rate of change**: EXTREME. New agentic systems being deployed monthly. Each deployment implicitly settles questions about delegation scope without explicit societal deliberation. The window for principled research that shapes norms is narrow.

**Will be central in 1–3 years**: As AI agents manage more of economic, medical, legal, and personal decisions, delegation will be the organizing concept for AI governance debates. Whoever has the empirical data and theoretical framework wins the policy debate.

---

## Sub-topics & Trends (last 3–5 years)

- **Agentic AI governance** (2024–2026): Regulatory discussions shifting from model regulation to system regulation. Who authorizes what delegation? What audit trails are required? OpenAI Operator agreements, Anthropic's "Responsible Scaling Policy," EU AI Act implementation.

- **Multi-agent delegation chains** (2024–2025): Orchestrator-subagent architectures. LangChain, AutoGPT, Claude's "tools" — creating delegation chains that are technically functional but governancely opaque.

- **AI fiduciary law** (2023–2025): Legal scholars (Balkin, Hartzog) proposing that AI companies should be treated as fiduciaries to their users — legally obligated to act in users' interests, not their own. This is Latour's inscription problem reframed as contract law.

- **Automation bias studies** (2020–2025): Growing empirical literature on how humans over-trust delegated AI systems — supervisory delegation collapses into blind delegation under cognitive load. Clinicians over-accepting AI diagnoses; drivers over-trusting autopilot.

- **Delegation preferences research** (2024–2025): First empirical studies on what people want to delegate. Ada Lovelace Institute (2025) policy work on AI assistants. Public preference surveys on AI in healthcare, legal, and financial decisions.

- **AI companions and parasocial delegation** (2022–2025): Replika, Character.AI, Pi — millions of users delegating emotional support functions to AI. Ethical debates about what this does to human relational capacities. Connects to Turkle's work.

- **Moral delegation to AI** (2021–2025): Using AI for moral decisions — credit scoring, parole, hiring. The "moral crumple zone" problem: when AI makes the decision, humans blame the AI and the designers escape accountability. Who is the moral agent when AI is the decision agent?

---

## Key People

- **Botao Amber Hu** ([[Amber]]) — Oxford/ERA. HADAC researcher; originator of Parasitic/Sovereign/Dissociative Agent taxonomy. The most active researcher specifically connecting STS delegation theory to AI agent behavior. <https://amber.botao.hu>

- **Bruno Latour** (1947–2022) — The foundational theorist. "Where Are the Missing Masses?" (1992) established delegation as a core ANT concept. His work on inscription and prescription is required reading for understanding how delegation works in technical artifacts. See [[Actor-Network Theory]] for full profile.

- **Langdon Winner** — Political theorist of technology. "Do Artifacts Have Politics?" (1980) is the single most influential precursor. Based at RPI (now emeritus). Less active in current AI debates but the conceptual foundation is his.

- **Lucy Suchman** — Lancaster University (emeritus). "Plans and Situated Actions" (1987/2007) is the key text on why delegation to rule-following machines is always a simplification. Her subsequent work at Xerox PARC and Lancaster focused on military automation and drone warfare as delegation — deeply relevant to AI agency questions. <https://www.lancaster.ac.uk/sociology/people/lucy-suchman>

- **Stuart Russell** — UC Berkeley. *Human Compatible* (2019) is the most sophisticated statement of AI alignment as delegation problem. His CAIS (Center for AI Safety) and ongoing work on cooperative AI are attempting to solve delegation governance at the technical level. <https://people.eecs.berkeley.edu/~russell/>

- **N. Katherine Hayles** — Duke University (emeritus). *How We Became Posthuman* (1999) and later work on "unthought" and machine cognition frames the posthuman condition as one of distributed and delegated agency. Essential for the philosophical framing of what delegation means for human identity. <https://scholars.duke.edu/person/nkh>

- **Sherry Turkle** — MIT. "Alone Together" (2011) and decades of empirical research on how humans relate to computational entities — especially emotional delegation to robotic companions. Essential empirical grounding for the care ethics dimension. <https://sturkle.com>

- **Iyad Rahwan** — Max Planck Institute for Human Development. Machine behavior framing (see [[Agent Ethology]]); his Moral Machine experiment (2018) empirically studied which moral decisions humans delegate to autonomous vehicles. The most empirically rich adjacent work. <https://rahwan.me>

- **Mark Coeckelbergh** — University of Vienna. *AI Ethics* (MIT Press, 2020) is the clearest philosophical synthesis; his earlier "Robot Rights?" and later "AI for People and Planet" directly address delegation of moral responsibility. <https://markcoeckelbergh.com>

- **Shannon Vallor** — University of Edinburgh. *Technology and the Virtues* (Oxford, 2016) — care ethics tradition applied to AI. Strong on what delegation does to human moral development. <https://www.shannonvallor.net>

- **Jack Balkin** — Yale Law School. "Information Fiduciaries and the First Amendment" (2016) and related work proposing AI companies as legal fiduciaries. The legal framework for accountability in delegation chains. <https://law.yale.edu/jack-m-balkin>

- **Lewis Hammond / Oliver Sourbut** — Oxford Future of Humanity Institute. "Delegation Games" (IJCAI 2024) — formal game theory of human-AI delegation. Emerging researchers bridging AI safety and delegation theory. <https://arxiv.org/abs/2402.15821>

- **Raja Parasuraman** (1950–2015) — George Mason University. Levels of automation framework — the most operationalized delegation theory in HCI. His 2000 paper with Sheridan & Wickens remains the benchmark for measuring delegation degree.

---

## Must-Read List

### Books

- [*Where Are the Missing Masses? The Sociology of a Few Mundane Artifacts*](https://mitpress.mit.edu/books/shaping-technology-building-society) — Latour, B. (1992). In Bijker & Law (eds.), *Shaping Technology/Building Society*. MIT Press. — **The ANT delegation founding text. Speed bumps, door closers, seatbelts as moral delegates. Short, brilliant, essential.** URL: Book chapter in MIT Press volume.

- [*Plans and Situated Actions: The Problem of Human-Machine Communication*](https://www.cambridge.org/core/books/plans-and-situated-actions/) — Suchman, L. (1987). Cambridge University Press. — **Why AI delegation always fails to capture what humans actually want. The deepest challenge to plan-based AI.** ISBN: 9780521337397.

- [*Human Compatible: Artificial Intelligence and the Problem of Control*](https://www.penguinrandomhouse.com/books/566677/human-compatible-by-stuart-russell/) — Russell, S. (2019). Viking. — **The clearest statement of alignment as principal-agent problem. Russell's "inverse reward design" is a delegation design principle.** ISBN: 9780525558613.

- [*The Mangle of Practice: Time, Agency, and Science*](https://press.uchicago.edu/ucp/books/book/chicago/M/bo3637094.html) — Pickering, A. (1995). University of Chicago Press. — **Distributed agency, resistance, and accommodation. Agency is never transferred intact — it is always remade in the mangle.** ISBN: 9780226668031.

- [*Alone Together: Why We Expect More from Technology and Less from Each Other*](https://www.basicbooks.com/titles/sherry-turkle/alone-together/9780465031467/) — Turkle, S. (2011). Basic Books. — **Empirical study of parasocial delegation: what happens to human connection when we delegate it to machines.** ISBN: 9780465010219.

- [*The Ethics of Care: Personal, Political, and Global*](https://global.oup.com/academic/product/the-ethics-of-care-9780195180992) — Held, V. (2006). Oxford University Press. — **The best statement of why care is constitutively non-delegable. Essential for understanding what HADAC's non-delegable column really means.** ISBN: 9780195180992.

- [*How We Became Posthuman: Virtual Bodies in Cybernetics, Literature, and Informatics*](https://press.uchicago.edu/ucp/books/book/chicago/H/bo3624819.html) — Hayles, N.K. (1999). University of Chicago Press. — **The philosophical prehistory of AI delegation: how modern subjects became capable of distributing their agency across technical systems.** ISBN: 9780226321462.

- [*Human Condition*](https://press.uchicago.edu/ucp/books/book/chicago/H/bo3618633.html) — Arendt, H. (1958). University of Chicago Press. — **The philosophical baseline: what *action* means for humans, and why substituting it has consequences for political life.** Referenced in HADAC. ISBN: 9780226025988.

- [*AI Ethics*](https://mitpress.mit.edu/books/ai-ethics) — Coeckelbergh, M. (2020). MIT Press. — **Best introductory synthesis of delegation, moral responsibility, and AI. Accessible but philosophically rigorous.** ISBN: 9780262538190.

### Papers

- [Theory of the Firm: Managerial Behavior, Agency Costs and Ownership Structure](https://doi.org/10.1016/0304-405X(76)90026-X) — Jensen, M.C. & Meckling, W.H. (1976). *Journal of Financial Economics*, 3(4), 305–360. DOI: 10.1016/0304-405X(76)90026-X — **The canonical economic principal-agent text. The incentive misalignment analysis translates directly to AI.**

- [Do Artifacts Have Politics?](https://www.jstor.org/stable/20024652) — Winner, L. (1980). *Daedalus*, 109(1), 121–136. URL: https://www.jstor.org/stable/20024652 — **Low bridges, nuclear reactors, and the political inscription of artifacts. The pre-ANT statement of technical delegation.**

- [A model for types and levels of human interaction with automation](https://doi.org/10.1109/3468.844354) — Parasuraman, R., Sheridan, T.B. & Wickens, C.D. (2000). *IEEE Transactions on Systems, Man, and Cybernetics — Part A*, 30(3), 286–297. DOI: 10.1109/3468.844354 — **The operationalization of delegation degree. Still the benchmark framework for measuring how much is delegated.**

- [Cooperation and Control in Delegation Games](https://arxiv.org/abs/2402.15821) — Sourbut, O., Hammond, L. & Wood, H. (2024). *IJCAI 2024*. arXiv:2402.15821. DOI: 10.24963/ijcai.2024/26 — **Formal analysis of multi-principal multi-agent delegation: alignment and cooperation failures decomposed. Essential for multi-agent governance.**

- [Machine behaviour](https://www.nature.com/articles/s41586-019-1138-y) — Rahwan, I. et al. (2019). *Nature*, 568, 477–486. DOI: 10.1038/s41586-019-1138-y — **The behavioral science framing for AI. Treating AI as an observational subject rather than an engineering artifact — adjacent to delegation research.**

### Journals

- [*AI & Society*](https://www.springer.com/journal/146) (Springer) — Societal implications; good home for STS-inflected delegation work
- [*Philosophy & Technology*](https://www.springer.com/journal/13347) (Springer) — Philosophical dimensions of delegation, moral responsibility, fiduciary theory
- [*AI & Ethics*](https://www.springer.com/journal/43681) (Springer) — Applied ethics framing; policy-oriented
- [*Science, Technology, & Human Values*](https://journals.sagepub.com/home/sth) (SAGE) — STS tradition; Latour's journal of record
- [*Nature Human Behaviour*](https://www.nature.com/nathumbehav/) — **Amber's target for HADAC** — high-prestige empirical human behavior work
- [*ACM FAccT Proceedings*](https://facctconference.org/) — Primary venue for algorithmic accountability; Amber's existing papers

---

## Key Venues

- **[[FAccT]]** ([facctconference.org](https://facctconference.org)) — ⭐⭐⭐ Amber's home base. Accountability, transparency, and fairness in AI — exactly where delegation governance discussions happen. Amber has existing papers here.
- **CSCW** ([cscw.acm.org](https://cscw.acm.org)) — ⭐⭐⭐ Computer-Supported Cooperative Work. The classic venue for empirical studies of human-AI delegation in work contexts. Lucy Suchman's heritage venue.
- **CHI** ([chi.acm.org](https://chi.acm.org)) — ⭐⭐⭐ Human-Computer Interaction flagship. Human agency in AI-mediated work; automation bias; trust calibration. Amber already has CHI papers.
- **AIES** ([aaai.org/conference/aies/](https://aaai.org/conference/aies/)) — AAAI/ACM Conference on AI, Ethics, and Society. Direct governance focus.
- **Machine Behavior Conference** ([machinebehavior.science](https://machinebehavior.science)) — Adjacent; behavioral science of AI agents.
- **[[ALIFE Conference]]** ([alife.org](https://alife.org)) — For the agent ethology framing of delegation strategies.
- **Norms, Agents, and AI (NormMAS)** — Workshop series at AAMAS on normative multi-agent systems; very relevant to delegation chains and principal-agent governance.
- **ITS** (International Symposium on Technology and Society, IEEE) — Philosophy of technology tradition; Winner's legacy.

---

## Key Communities & Institutions

- **Ada Lovelace Institute** ([adalovelaceinstitute.org](https://www.adalovelaceinstitute.org)) — UK AI policy think tank. Their 2025 work on AI personal assistants is directly relevant; policy arm for HADAC-type research.
- **AI Now Institute** ([ainowinstitute.org](https://ainowinstitute.org)) — Critical AI studies; algorithmic accountability; delegation and power.
- **Center for Human-Compatible AI (CHAI)** ([humancompatible.ai](https://humancompatible.ai)) — Russell's Berkeley center. Technical principal-agent work on alignment.
- **Future of Humanity Institute** (Oxford, now reconstituted) — Delegation games work (Hammond, Sourbut); existential risk framing of delegation.
- **The Alan Turing Institute** ([turing.ac.uk](https://www.turing.ac.uk)) — UK national AI institute; trustworthy AI and delegation governance.
- **Oxford Internet Institute** ([oii.ox.ac.uk](https://www.oii.ox.ac.uk)) — Platform governance, AI delegation in digital contexts.
- **AI Safety community** (LessWrong, Alignment Forum) — Technical alignment = technical delegation design; enormous amount of relevant work.
- **STS community** (4S, EASST) — Annual conference of the Society for Social Studies of Science — the academic home of Latour, Suchman, and the STS tradition.

---

## Fellowships & Programmes

- **Ada Lovelace Institute Research** — Policy fellowships on AI governance; HADAC-type research would fit. <https://www.adalovelaceinstitute.org>
- **Oxford Martin School Programmes** — Amber is at Oxford; proximity advantage for AI governance programmes.
- **CSCW/CHI grants** — NSF CISE Human-Centered Computing; delegation in work contexts.
- **Wellcome Trust Society and Ethics grants** — Human behaviour and AI; HADAC's N=10,000 survey would qualify.
- **ERC Starting Grants** — EU research on AI and society; delegation as a research framing has strong fit for EU funding priorities.
- **ERA (Existential Risk Alliance)** — Amber's current fellowship; delegation chain failure modes are directly existential risk adjacent.
- **Leverhulme Trust Research Fellowships** — UK; philosophy of technology and AI.

---

## How Can Amber Engage?

- **HADAC as the organizing project**: The survey infrastructure should be built now before the delegation frontier is naturalized. The window for measuring pre-norm delegation preferences is closing fast.
- **FAccT 2026 papers**: The Parasitic/Sovereign/Dissociative Agents papers are the first publications from this framing — they need to cite the delegation literature explicitly.
- **Oxford network**: Max Van Kleek (supervisor) works on personal data, AI agents, and trust — direct delegation context. The Oxford Internet Institute has relevant people.
- **Survey pre-registration**: Register the HADAC survey design at AsPredicted or OSF before running, for *Nature Human Behaviour* submission.
- **Cross-cite with Agent Ethology**: The two projects (HADAC + Agent Ethology) are mutually reinforcing — one studies delegation from the human side, the other from the agent side.
- **CSCW submission**: A HADAC-driven paper would find a very receptive audience at CSCW — they've been studying human-automation delegation in work contexts for decades and the LLM agent angle is wide open.

---

## For Amber

### 🎯 Strategic Position

Amber is doing something nobody else is doing: **empirically mapping the delegation frontier across all of human life.** HADAC is unique. The existing literature either:
- Studies specific task domains (aviation, driving, healthcare) without life-spanning scope
- Studies normative questions (should we delegate X?) without empirical measurement
- Studies technical alignment without connecting to human phenomenology of delegation

HADAC does all three: comprehensive scope, empirical measurement, phenomenological grounding. This is a genuinely new instrument.

### 📚 Who Should Amber Read

**Must-read immediately:**
- Latour, "Where Are the Missing Masses?" (1992) — 20 pages, will reframe everything
- Suchman, *Plans and Situated Actions* (1987) Ch. 1-4 — the situated action challenge to delegation planning
- Russell, *Human Compatible* (2019) Ch. 1, 5, 7 — alignment as delegation problem, cooperative AI design
- Sourbut et al. (2024) "Delegation Games" — formal framework, 10 pages

**High value (medium priority):**
- Winner (1980) "Do Artifacts Have Politics?" — 15 pages, the political inscription argument
- Held (2006) *The Ethics of Care* — on what care delegation means
- Parasuraman et al. (2000) — levels of automation framework to position HADAC against
- Turkle (2011) *Alone Together* — empirical case studies of parasocial delegation

**Contextual (when needed):**
- Pickering (1995) — deep dive on distributed agency
- Hayles (1999) — posthuman framing
- Arendt (1958) *Human Condition* — philosophical baseline for what action is

### 🤝 Who Should Amber Know

- **Stuart Russell** — Dream interlocutor. Russell is reachable and interested in the human-preference side of alignment. HADAC data on what humans want to delegate would be directly relevant to his inverse reward design work.
- **Lucy Suchman** — Lancaster emeritus. The foundational STS perspective; if Amber reaches out to Suchman citing "Where Are the Missing Masses?" and HADAC, she would likely respond warmly.
- **Lewis Hammond / Oliver Sourbut** — Oxford, Future of Humanity Institute. They have the formal delegation games framework; Amber has the empirical delegation measurement. Natural collaboration.
- **Mark Coeckelbergh** — Vienna. Writes accessibly for wide audiences; could be an excellent external commenter on HADAC's philosophical framing.
- **Shannon Vallor** — Edinburgh. Care ethics + AI — exact overlap with HADAC's non-delegable and blurry zones.

### 📝 What Should Amber Publish

1. **HADAC instrument paper** — "Human Activity Delegation Agency Chart: An Empirical Taxonomy of AI Delegability Across the Human Lifespan." Target: *Nature Human Behaviour* (primary). Backup: *PLOS ONE*, *Computers in Human Behavior*. Need: survey data collected, N ≥ 1,000.

2. **FAccT theoretical paper** — "Delegation Failure Modes: Parasitic, Sovereign, and Dissociative Agents as Breakdowns of the Principal-Agent Relation." Directly ties the agent taxonomy to the delegation literature. FAccT 2026 if deadline allows, FAccT 2027 otherwise.

3. **CSCW paper** — "The Delegation Frontier: What Workers Want to Keep Human in AI-Mediated Work." HADAC data applied to workplace contexts. CSCW audience knows the automation bias and trust calibration literature.

4. **Position/opinion piece** — "The Delegation Crisis" for *AI & Society* or *Philosophy & Technology*. Short (3,000 words), conceptual, connecting Latour to HADAC to governance crisis. Low publication bar, high citation potential as a framing paper.

### 🏠 Fellowships & Residencies for This Work

- **The Alan Turing Institute** — Fellowship would give access to UK AI governance community; HADAC survey might get institutional backing.
- **Ada Lovelace Institute** — Short fellowship or collaboration; they want exactly this kind of empirical work on AI and human agency.
- **Wellcome Trust** — Interdisciplinary human behaviour + ethics funding; HADAC survey at N=10,000 scale would need substantial funding.

### 💡 The Big Paper Only Amber Can Write

*"What Remains Human: An Empirical Typology of the AI Delegation Frontier"* — combining:
- HADAC taxonomy + survey data (what people actually want to delegate)
- STS theoretical framing (what delegation means, what is lost)
- Agent taxonomy (what different delegation modes look like from the agent side)
- Care ethics analysis (what the non-delegable column tells us about the human)

This is a landmark paper. Nobody else has the combination of machine behavior science, STS literacy, care ethics awareness, and technical agent knowledge to write it. Amber does.

---

## Recent Important Updates (Timeline)

- **2026:** Tomašev et al. publish on delegation mechanisms between AI agents — the AI-to-AI delegation layer formally studied for the first time (referenced in HADAC, exact citation TBC).
- **2025:** Ada Lovelace Institute publishes policy work on AI personal assistants — first major policy treatment of AI delegation governance in the UK.
- **2025 (ongoing):** Multi-agent AI pipelines (OpenAI's multi-agent workflows, Claude's agentic modes, LangGraph) become production-scale — creating complex delegation chains without governance framework.
- **2024:** Sourbut, Hammond & Wood (IJCAI 2024) — first formal game-theoretic treatment of delegation games, providing mathematical framework for alignment + cooperation failures.
- **2024:** EU AI Act enters force — framework for high-risk AI but delegation chains remain largely unaddressed in the text.
- **2023–2024:** Auto-GPT, BabyAGI, then Claude/GPT-4 tool use — the transition from conversational AI to agentic AI; delegation becomes a mass consumer experience.
- **2023:** OpenAI introduces ChatGPT plugins (now GPT Actions) — first mass-market AI delegation infrastructure; millions of users delegating web search, code execution, database queries.
- **2022:** Amber begins HADAC project — the empirical delegation measurement project takes shape.
- **2021:** First major "Moral Crumple Zone" discussions in AI ethics literature — accountability diffusion in AI delegation chains identified as central governance problem.
- **2019:** Russell publishes *Human Compatible* — formal statement of alignment = delegation problem.
- **2018:** Moral Machine experiment (Rahwan et al.) — largest empirical study of how humans want to delegate moral decisions to autonomous vehicles.

---

## Adjacent Topics

- **[[Actor-Network Theory]]** — Parent framework. ANT's delegation and inscription concepts are the STS foundation. But Delegation and Human Agency extends ANT into AI agent systems specifically, and adds the economic principal-agent theory and human factors LOA traditions that ANT doesn't address. Delegation is the *core mechanism* of ANT's sociology of artifacts.

- **[[Machine Behavior]]** — Sister field. Machine Behavior studies what AI does behaviorally; Delegation and Human Agency studies the relational structure within which it acts. Both are needed: you can't understand what an agent does without understanding the delegation structure it operates within.

- **[[Agent Ethology]]** — Complementary. Agent Ethology studies survival strategies; delegation theory studies the principal-agent structure that shapes what "survival" means for an agent. Parasitic, Sovereign, Dissociative agents are both ethological types and delegation failure modes.

- **[[Algorithmic Governance]]** — Downstream application. Algorithmic governance is what happens when delegation is institutionalized through algorithms — public decisions delegated to automated systems. The accountability gaps in algorithmic governance are principal-agent problems at the institutional scale.

- **[[Protocol Studies]]** — Technical infrastructure of delegation. Protocols define what can be delegated, to what, with what authority. The technical layer through which delegation chains are implemented.

- **[[Distributed Cognition]]** — Cognitive science parallel. Distributed cognition (Hutchins) analyzes how cognitive work is distributed across humans and artifacts; delegation theory asks about the normative and accountability dimensions of that distribution.

- **[[Maintenance and Care]]** — The other side of delegation. Care ethics challenges: what does delegation do to the human capacity for care? The maintenance tradition (Jackson, Mattern) studies what sustaining delegated systems costs.

- **[[AI Safety]]** — Technical delegation design. Alignment = technical solution to the delegation problem. Agent Ethology and Delegation frame the problem; AI Safety attempts the engineering solution.

- **[[Surveillance Capitalism]]** — Zuboff's framing of data collection as unauthorized delegation of human behavioral data to corporate surveillance apparatus. The parasitic delegation reading of platform capitalism.

---

## Open Questions

### Empirical
- What are actual human delegation preferences across the life spectrum? (HADAC's question) How stable are they across cultures, demographics, contexts? How fast are they changing?
- At what level of autonomy does "automation bias" kick in — where humans stop verifying and start rubber-stamping? Can this be measured and designed around?
- How does the experience of delegation feel phenomenologically? Do people notice the moment when they delegate vs. merely use a tool? What is the subjective experience of "giving over" agency?
- What happens to human skills that are consistently delegated? (de-skilling, atrophy) How long does it take? Is it reversible?

### Theoretical
- Is there a meaningful distinction between "using a tool" and "delegating agency"? Or is all tool use a form of delegation? If Latour is right and every artifact is a delegate, then tool use IS delegation and the distinction collapses.
- Can care be genuinely delegated? Or does AI care always produce a simulacrum that erodes the relational capacity it simulates? Is Held right that care is constitutively non-delegable?
- What is the right unit of analysis for delegation? Individual tasks? Domains of life? The integrated self? Can a person delegate some parts of their agency while maintaining others, or does delegation in one domain affect the rest?
- How should moral responsibility be allocated in delegation chains? Current legal frameworks assume individual human accountability; delegation chains make this incoherent.

### Governance
- Should there be legal limits on how much authority can be delegated to AI systems in specific domains (healthcare, legal, financial, political)? What are the democratic legitimacy arguments?
- What constitutes informed delegation? Do users of AI agents genuinely understand what they are delegating, to whom, under what conditions?
- Who authorizes AI-to-AI delegation? When an orchestrator AI delegates to a sub-agent AI, is that within the scope of the original human authorization? 
- What are the fiduciary responsibilities of AI developers to the users who delegate to their systems?

### For the Field
- How do we build adequate theoretical integration across the three traditions (STS, economics, human factors) studying delegation? They don't yet talk to each other enough.
- Is the delegation spectrum (Levels 0–7 as sketched above) the right conceptual tool? What alternatives exist?
- How does delegation theory translate to non-Western contexts where the human/artifact boundary, the concept of agency, and the ethics of care have different cultural inflections?

---

## Why Interesting

Delegation and human agency sits at the exact center of everything Amber's research asks:

- **Edge of chaos**: The delegation frontier is being actively redrawn by LLM agents RIGHT NOW, in real time, without principled deliberation. This is among the most rapidly evolving normative landscapes in any field.

- **More-than-human**: Delegation theory treats AI agents as genuine participants in human social life — not mere tools, but entities that receive and exercise delegated authority. This is the ANT/more-than-human lens.

- **Critical computing**: The power analysis is sharp — who gets to authorize delegation, who bears the costs of delegation failure, which humans lose agency when AI is delegated into their decision chains. This is computing as political act.

- **Machine behavior**: Delegation shapes the behavioral context within which agents act. Understanding machine behavior requires understanding the delegation structure that creates the agent's operating environment.

- **Speculative design**: The HADAC "blurry zone" is a speculative space — activities that are not yet delegated but might be in 5 years. Mapping it is a form of speculative research, designing the terrain of futures.

- **Amber's own research**: This IS Amber's work. HADAC, the FAccT papers, the agent taxonomy — they are all delegation theory applied. This note is the theoretical foundation for Amber's next 3–5 years of output.

---

## 📋 Update Log

| Date | Researcher | Action |
|------|-----------|--------|
| 2026-03-10 | Biber (subagent) | Initial deep research. Full note created. Theoretical lineage mapped from Latour (ANT), Jensen & Meckling (principal-agent economics), Parasuraman (LOA), Suchman (situated action) through to HADAC and Amber's agent taxonomy. HADAC repo fetched and analyzed. All citations verified or flagged with URLs. |
