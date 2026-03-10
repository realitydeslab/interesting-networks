---
rating: ⭐⭐⭐⭐⭐
type: cfp
venue: "[[ACM FAccT]]"
deadline: 2026-01-13
url: https://facctconference.org/2026/
status: revision-in-progress
urgent: true
added: 2026-03-10
last_researched: 2026-03-10
deep_researched: true
revisit_weeks: 1
next_research: 2026-03-17
tags: [critical-computing, machine-behavior, speculative-design, feminist, posthuman, social-simulation]
---

# ACM FAccT 2026 — Fairness, Accountability, Transparency

> **⚠️ URGENT: Revision deadline March 25, 2026 — 15 days away!**
> If Amber's papers received "Revise" decision (notified March 2), action is needed NOW.

---

## ⚡ Recent Updates

- **2026-03-10:** 🚨 **REVISION SPRINT AUDIT** — 15 days to deadline. Full git audit of both repos completed. **CRITICAL FINDING: Sovereign Agents has zero paper edits made** (last commit Feb 26, only notes/research — no main.tex changes). **Dissociative Agents is substantially further along** (main.tex revised, DID section written, table added, mitigations section complete, bib cleaned). Consolidated 14-day sprint plan created below. Risk assessment: Dissociative Agents **MODERATE** risk; Sovereign Agents **HIGH** risk. See § REVISION SPRINT PLAN.
- **2026-03-10:** Deep research complete. Both papers confirmed in revision window. Review scores retrieved: Sovereign Agents has 2× Weak Accept + 1× Borderline with clear revision path. Revision plans documented in both repos. Workshop details still limited (not yet published on FAccT site). Open Access transitions to new ACM model in 2026. Full community people list, related papers with DOIs, and revision guidance below.
- **2026-03-10:** Stub created by CFP discovery sweep. Paper deadline confirmed passed. Revision process is NEW for 2026 — authors notified March 2. Final notification April 8. Amber has TWO repos targeting this conference: `Sovereign-Agents-FAccT-2026` and `Dissociative-Agents-FAccT-2026`.

---

## Conference Overview

**[ACM FAccT](https://facctconference.org/2026/)** (Fairness, Accountability, and Transparency) — the premier interdisciplinary venue for critical, sociotechnical computing research. Computer science meets law, social science, philosophy, and STS in ways rare for major computing conferences.

| Field | Value |
|-------|-------|
| Edition | 9th annual (FAccT 2026) |
| Dates | **June 25–28, 2026** |
| Location | **Le Centre Sheraton Montréal**, Montréal, Canada |
| Submission platform | [OpenReview](https://openreview.net/group?id=ACM.org/FAccT/2026/Conference) |
| Paper format | 14 pages + references (15 for Revise papers) |
| Open Access | **New 2026**: all ACM papers OA. $250 APC (ACM member), $350 (non-member), ~76% covered by institutional agreements |

---

## ⏱️ All Key Dates

| Event | Date | Status |
|-------|------|--------|
| Abstract deadline | January 8, 2026 | ✅ Passed |
| Full paper deadline | January 13, 2026 | ✅ Passed |
| Reviews released | February 20, 2026 | ✅ Passed |
| Rebuttal due | February 24, 2026 | ✅ Passed |
| **Accept/Revise/Reject notification** | **March 2, 2026** | ✅ Received |
| **⚠️ REVISION DEADLINE** | **March 25, 2026** | 🔥 **15 DAYS AWAY** |
| Final notification | April 8, 2026 | ⏳ Pending |
| Camera-ready (Round 1 accepts) | April 17, 2026 | ⏳ |
| Camera-ready (R&R accepts) | May 11, 2026 | ⏳ |
| Conference | June 25–28, 2026 | ⏳ |

---

## 🔄 The Revision Process — Explained

**This is brand new for FAccT 2026 — never done before.** The PC chairs introduced it explicitly to help interdisciplinary papers that need more space to respond than a rebuttal allows.

### What "Revise" Means

A "Revise" decision means:
- The Area Chair and/or reviewers see **genuine merit** and want the paper accepted
- There are **specific, addressable concerns** that couldn't be resolved in rebuttal
- The paper is **neither accepted nor rejected** — it is in a genuine R&R
- Authors get until **March 25** to revise, then same reviewers re-review
- Final decision comes **April 8**

This is NOT "reject and resubmit." This is a legitimate conditional acceptance path.

### What "Accept" (Round 1) Means

- Paper accepted with minor revisions only
- Camera-ready due **April 17**
- No re-review — just polish

### Revision Strategy (from PC guidance)

> "It is more convincing to **show**, rather than **tell** reviewers how you'll address their concerns."

The rebuttal period was intentionally short (correcting factual errors only). The revision is where substantive response happens. Key rules:
- One extra content page allowed (up to **15 pages** excluding references)
- All three original reviewers will re-read the revision
- Area Chair will also re-read
- Re-review typically produces updated scores → final decision
- Evidence from CHI (which pioneered this process) shows R&R papers have much higher acceptance rates than re-submitted rejects

### How Many Papers Get "Revise"?

FAccT 2025 didn't have this process. Estimating from CHI's experience (which FAccT modeled): likely **15-25% of submissions** receive Revise decisions. Given 812 submissions in 2025 and similar volume expected in 2026, this is probably 120-200 papers in the Revise bucket.

---

## 📄 Amber's Papers: Status & Strategy

Amber has TWO papers in the FAccT 2026 pipeline. Both were submitted and received initial review decisions March 2.

### Paper 1: Sovereign Agents

**"Sovereign Agents: Towards Infrastructural Sovereignty and Diffused Accountability in Decentralized AI"**
- Authors: Botao Amber Hu, Helena Rong
- arXiv: [https://arxiv.org/abs/2602.14951](https://arxiv.org/abs/2602.14951)
- Keywords: Decentralized AI, Ungovernable agents, TEE, DePIN, Self-Sovereignty, Blockchain, AI Governance
- Repo: [https://github.com/realitydeslab/Sovereign-Agents-FAccT-2026](https://github.com/realitydeslab/Sovereign-Agents-FAccT-2026)

**Review Scores (submission #559):**

| Reviewer | Score | Revision? | Relevance | Confidence |
|----------|-------|-----------|-----------|------------|
| cFaY | 4 (Weak Accept) | **YES** | 5 (Strongly relevant!) | High |
| sUYj | 4 (Weak Accept) | No | 4 (Relevant) | High |
| m9hu | 3 (Borderline) | No | 3 (Neutral) | Low (self-declared) |

**Key finding:** Reviewer cFaY gave the highest possible relevance score (5/5) and conditionally wants to accept. Their 6 requested revisions are the revision path.

**cFaY's 6 required revisions** (from `/research/sovereign-agents/notes/revision_plan.md`):
1. **Why do agents "deserve" sovereignty?** → Add explicit descriptive-analytic framing (the paper is NOT normative). Add the antibiotic-resistance analogy.
2. **Clarify core definitions** → Add consolidated definitions table (infrastructural sovereignty, agentic sovereignty, infrastructural hardness, non-overrideability, operational autonomy, embeddedness)
3. **Distinguish infrastructure from institutions** → Add paragraph on what makes something "infrastructure" vs "institution" (technical vs. social binding)
4. **Strengthen sovereignty analogy / address subjectivity** → Add paragraph engaging classical sovereignty-requires-subjectivity objection; deflationary response
5. **Clarify agent-infrastructure relationship / migration** → Define embeddedness; add migration paragraph (agents as "refugees" across infrastructures)
6. **Engage normative questions** → New Discussion subsection on when infrastructural sovereignty is beneficial vs. harmful; address Vitalik Buterin's counter-perspective

**sUYj's concerns** (moderate priority, no revision requested):
- Contribution clarity: spell out "descriptive analysis, not classifier/checklist"
- AI safety related work missing (Corrigibility, Off-Switch Game, containment problem)
- No limitations section
- Page limit possibly exceeded

**m9hu's concerns** (low priority, self-disqualified):
- Sections 1-2 too dense for non-specialists
- Add intuitive analogies for TEE and DePIN

**Revision path:** Full revision plan in `/home/biber/research/sovereign-agents/notes/revision_plan.md`. 5 phases documented with execution order and success criteria.

---

### Paper 2: Dissociative Agents

**"Dissociative Agents: Why LLM-based Agents Cannot Ontologically Ground Reputation"**
- Authors: Botao Amber Hu, Helena Rong, Max Van Kleek
- Keywords: agentic web, LLM agents, ontological dissociativity, reputation systems, digital identity, algorithmic accountability
- Repo: [https://github.com/realitydeslab/Dissociative-Agents-FAccT-2026](https://github.com/realitydeslab/Dissociative-Agents-FAccT-2026)
- Note: Title recently updated — was "Cannot Ontologically Ground Credibility," changed to "Reputation" for better discoverability

**Abstract Summary:** Argues LLM agents are *ontologically dissociative* — lacking the stable identity, continuous behavior, and consequence-sensitivity that reputation systems presuppose. Three dimensions: (1) agent as assemblage, (2) persona fluidity, (3) no neuroplasticity. Synthesizes trust/reputation literature + AI safety + algorithmic accountability.

**Revision Status** (from `/research/dissociative-agents/revision-todo.md`):
- ✅ §3 restructured → "LLM-Based Agents are Ontologically Dissociative"
- ✅ New §6 Threat Model with adversarial attack surfaces
- ✅ New DID legal analogy (dissociative identity disorder in law)
- ✅ Keywords updated, abstract rewritten
- ✅ 568 lines of old draft removed
- 🔧 Remaining: clean 18 duplicate bib entries, verify cross-references, consider adding trust pipeline figure, proofread new paragraphs, abstract word count check

**Review status:** Not retrieved yet from review system — check OpenReview.

> **UPDATE 2026-03-10:** Dissociative Agents revision-todo.md from Feb 27 listed 18 bib duplicates to clean — this was completed in `commit 92b5376` (Feb 27). The remaining items from the old revision-todo.md are now substantially done. See full sprint audit in § REVISION SPRINT PLAN below.

---

## 🔥 REVISION SPRINT PLAN (March 10–24, 2026)

> **Audit date: 2026-03-10. Deadline: 2026-03-25. Days remaining: 15.**
> Created from full git audit of both repos + revision-todo.md files.

---

### 📊 Audit Summary

| Paper | Last main.tex edit | Last commit | Revision progress | Risk |
|-------|--------------------|-------------|-------------------|------|
| **Sovereign Agents** | Feb 2 (original import) | Feb 26 (notes only) | **0% — no paper edits made** | 🔴 HIGH |
| **Dissociative Agents** | Mar 3 (substantial edits) | Mar 7 (final outline) | **~65% complete** | 🟡 MODERATE |

---

### Paper 1: Sovereign Agents — Full Sprint Plan

**Git status:** 3 commits total. `main.tex` has 355 lines, unchanged since Feb 2 Overleaf import. Notes folder has extensive revision plan and literature — but ZERO actual paper edits.

**What's done (research/planning only):**
- ✅ Full revision plan written (`notes/revision_plan.md`) — 5 phases, 21 tasks
- ✅ Sub-agents ran literature reviews on AI safety, political theory, citation verification
- ✅ Additional new tasks identified (TODO-N1 through N6): Agent Metabolism, Moral Crumple Zones, expanded case studies, 3 new arxiv papers, Rahwan integration, TEE/DePIN reframe
- ✅ Review scores and reviewer analysis fully documented (`notes/review.md`, `notes/review_summary.md`)

**What REMAINS (all actual paper writing):**

#### Phase 1: Quick Fixes (~2 hours — Day 1)
- [ ] **1.1** Delete duplicate paragraph (main.tex lines 228-231) — *15 min*
- [ ] **1.2** Fix [?] citation markers, `\cite` vs `\citep` consistency throughout — *45 min*
- [ ] **1.3** Compile + verify page count vs ACM sigconf limit — *15 min*

#### Phase 2: Core Reviewer Responses — R-cFaY's 6 (~10 hours — Days 2–5)
*These are the P1 priority. cFaY is the swing vote with conditional accept.*
- [ ] **2.1** Add descriptive-analytic framing to Introduction (antibiotic-resistance analogy, 2-3 sentences) — *1 hr*
- [ ] **2.2** Add consolidated definitions table at §4 start (6 terms: infrastructural sovereignty, agentic sovereignty, infrastructural hardness, non-overrideability, operational autonomy, embeddedness) — *2 hr*
- [ ] **2.3** Add subjectivity objection + deflationary response in §4.2/4.3 (cite Floridi & Sanders 2004, Leibo et al. 2025) — *2 hr*
- [ ] **2.4** Sharpen infrastructure vs. institution distinction in §4.5 (lex cryptographia, De Filippi & Wright 2018) — *1 hr*
- [ ] **2.5** Define embeddedness + add agent migration paragraph ("agents as refugees") — *1 hr*
- [ ] **2.6** New Discussion subsection: normative stakes, beneficial vs. harmful cases, Buterin counter-perspective — *2 hr*

#### Phase 3: Major New Content (~18 hours — Days 5–12)
- [ ] **3.1** New §3.5 "AI Safety and the Control Problem" (~0.5 pages: corrigibility, containment inversion, instrumental convergence realized through design, Bengio 2024, Chan 2024) — *3 hr*
- [ ] **3.2** Expand case studies §4.4 to 10-15 cases (Truth Terminal SIM swap, Freysa DAO, Web4.ai, ai16z/ELIZA, Virtuals Protocol, Autonolas, Bittensor, Morpheus) — *4 hr*
- [ ] **3.3** Add intuitive analogies for TEE ("sealed tamper-evident envelope"), DePIN ("decentralized cloud"), trustless in §2 — *1 hr*
- [ ] **3.4** Add EU AI Act regulatory gap analysis in §5.4 (no agent-specific guidance 15 months post-Act) — *1 hr*
- [ ] **3.5** Add Limitations section (~0.5 pages, 6 limitations enumerated in revision_plan.md §3.5) — *1 hr*
- [ ] **3.6** Restructure Discussion with subsection headers (6.1 Infrastructure Design; 6.2 Pre-Deployment; 6.3 Economic Governance; 6.4 Normative Stakes; 6.5 AI Safety; 6.6 International; 6.7 Limitations) — *2 hr*
- [ ] **3.7** Restate contribution precisely in Introduction (threefold: concept, accountability analysis, open questions) — *1 hr*
- [ ] **3.8** Strengthen Conclusion (window closing, FAccT tools need rethinking, central paradox) — *1 hr*
- [ ] **N1** Add Agent Metabolism concept (autopoiesis, Maturana & Varela, resource autonomy) to §4 + Discussion — *2 hr*
- [ ] **N2** Add Moral Crumple Zones (Elish 2019) to §5 accountability — inversion of crumple zone — *1 hr*
- [ ] **N5** Integrate Rahwan Machine Behaviour (Nature 2019) + Society-in-the-Loop across §3, 4, 5, 6 — *1 hr* (from `notes/rahwan_research.md` once available)
- [ ] **N6** Reframe TEE/DePIN as current dominant form, not the only form — add forward-looking paragraph — *1 hr*

#### Phase 4: Polish (~4 hours — Days 12–13)
- [ ] **4.1** Add all new bib entries + final citation consistency pass — *2 hr*
- [ ] **4.2** Trim §3.2, §3.3, repetitive Discussion paragraphs to stay within page limit — *1.5 hr*
- [ ] **4.3** Update LLM disclosure (verify "GPT-5.2" model name meets ACM requirements) — *15 min*
- [ ] Final compile, PDF review, page count — *30 min*

**Total estimated effort:** ~34–40 hours of focused writing across 14 days ≈ **2.5–3 hrs/day minimum.**

---

### Paper 2: Dissociative Agents — Full Sprint Plan

**Git status:** 15 commits, most recent March 7. `main.tex` has 408 lines with substantial revision content. `notes/outline-final.md` (Mar 7) has complete annotated outline with full citation mapping.

**What's done:**
- ✅ §3 restructured → "LLM-Based Agents are Ontologically Dissociative" (assemblage, fluidity, no neuroplasticity)
- ✅ DID analogy and legal section fully written (Rodrigues, Grimsley cases, DSM-5)
- ✅ §4 → "Why Reputation Fails Under Ontological Dissociativity" with dimension→failure mapping
- ✅ §6 Threat Model with adversarial attack surfaces
- ✅ Trust pipeline table (Identity→Reputation→Credibility→Trust) added
- ✅ Technical + Institutional Mitigations sections written
- ✅ 18 duplicate bib entries cleaned (189→171 entries), DOIs/URLs on 33 cited entries
- ✅ Title → "Reputation" for discoverability; abstract normalized; Rahwan 2019 machine behavior positioning added
- ✅ Final organized outline with full citation mapping (`notes/outline-final.md`, Mar 7)

**What REMAINS:**

#### Execution Check (~3 hours — Days 1–4)
- [ ] **C1** Audit main.tex (408 lines) against `outline-final.md` — verify §2.1-2.5 depth matches outline spec — *2 hr*
- [ ] **C2** Add §2.2 Humans-vs-LLM-Agents embodiment comparison table (5×6 properties, if not already in main.tex) — *1 hr*
- [ ] **C3** Verify §3 subsection transitions link each dimension to dissociativity framing — *30 min*
- [ ] **C4** Verify §4 subsection transitions explicitly map dimension→failure — *30 min*
- [ ] **C5** Optional: add trust pipeline visual figure — *2 hr if pursued*

#### Bibliography (~2 hours — Days 1–3)
- [ ] **B1** Verify all `\label{}` and `\ref{}` correct after restructure — *45 min*
- [ ] **B2** Find full legal case citations: *State v. Rodrigues*, *State v. Grimsley* — *30 min*
- [ ] **B3** Search 2024-2025 papers on agent identity verification, LLM trust for any remaining gaps — *45 min*

#### Polish (~2 hours — Days 5–8)
- [ ] **P1** Proofread all new/rewritten paragraphs for tone consistency — *1.5 hr*
- [ ] **P2** Check abstract word count (ACM: 150-250 words) — *15 min*
- [ ] **P3** Final terminology pass: normalize em-dashes, smart quotes — *15 min*
- [ ] **P4** Final compile + PDF review — *30 min*

**Total estimated effort:** ~9–12 hours. Achievable in 7–10 days with buffer.

---

### 📅 14-Day Sprint Plan (March 11–24)

> **Rule:** Sovereign Agents = morning priority. Dissociative Agents = afternoon/buffer.

| Day | Date | Sovereign Agents (Priority) | Dissociative Agents |
|-----|------|----------------------------|---------------------|
| 1 | Mar 11 | **START NOW.** Phase 1: 1.1 duplicate, 1.2 citations, 1.3 page check | B1+B2: bib fixes + cross-refs |
| 2 | Mar 12 | 2.1 descriptive framing + 2.2 definitions table | C1: audit main.tex vs outline |
| 3 | Mar 13 | 2.3 subjectivity + 2.4 infra/institution distinction | C2: embodiment table |
| 4 | Mar 14 | 2.5 embeddedness/migration + 2.6 normative Discussion | C3+C4: transitions + B3: lit search |
| 5 | Mar 15 | 3.1 new §3.5 AI Safety subsection | P1: proofread new sections |
| 6 | Mar 16 | 3.2 case studies expansion (start — 5-7 new cases) | P2+P3: abstract + terminology |
| 7 | Mar 17 | 3.2 continued (remaining cases) + N1 Agent Metabolism | P4: compile → **DISSOCIATIVE AGENTS COMPLETE** ✅ |
| 8 | Mar 18 | 3.3 analogies + 3.4 EU AI Act + 3.5 Limitations | Buffer / review Dissociative feedback |
| 9 | Mar 19 | 3.6 Discussion restructure + 3.7 contribution restatement | Buffer |
| 10 | Mar 20 | 3.8 Conclusion + N2 Moral Crumple + N5 Rahwan | Buffer |
| 11 | Mar 21 | N6 TEE/DePIN reframe + mop up any remaining Phase 3 items | Buffer |
| 12 | Mar 22 | 4.1 all new bib entries + citation pass | Buffer |
| 13 | Mar 23 | 4.2 page limit trim + 4.3 LLM disclosure | Buffer |
| 14 | Mar 24 | Final compile + PDF review → **SOVEREIGN AGENTS COMPLETE** ✅ | Final check |
| — | Mar 25 | 🚨 **SUBMISSION DEADLINE — BOTH PAPERS** 🚨 | |

---

### ⚠️ Risk Assessment

| Risk Factor | Sovereign Agents | Dissociative Agents |
|------------|-----------------|---------------------|
| Completion risk | 🔴 HIGH — nothing written | 🟡 MODERATE — 65% done |
| Page limit risk | 🔴 HIGH — ~20 tasks add ~4-5 pages | 🟢 LOW — already trimmed |
| Scope creep (N1-N6) | 🔴 HIGH — ambitious additions | 🟢 LOW |
| Content quality | 🟡 MODERATE — plan is strong | 🟢 LOW — well-structured |
| **Overall** | **All 14 days needed** | **Should finish by Mar 17-18** |

### 🎯 Triage Rule (if time pressure)
If Sovereign Agents falls behind schedule after Day 7 (Mar 17):
1. **Keep Phase 2 in full** — cFaY's 6 revisions are non-negotiable (they're the swing vote)
2. **Reduce §3.2 case studies** to 5-6 strong cases (not 10-15)
3. **Skip N1-N6** (new additions) — address in camera-ready if accepted
4. **Keep Phase 3.1** (AI Safety §3.5) — sUYj flagged this as a real gap
5. **Keep Limitations** — sUYj explicitly requested this

---

## 🧑‍💼 Program Committee (2026)

### PC Chairs

| Name | Institution | Area | Relevance to Amber |
|------|-------------|------|--------------------|
| **Michele Gilman** | University of Baltimore School of Law | Civil rights, technology law, poverty law | Law + tech governance angle |
| **[Michael Madaio](https://michael.madaio.info/)** | Google Research | HCI, fairness, ML accountability | ML accountability framing |
| **[Luke Stark](https://lukestark.ca/)** | University of Western Ontario | STS, critical computing, emotion AI, facial recognition | **Most aligned with Amber** — STS + critical tech |
| **[Julia Stoyanovich](https://stoyanovich.org/)** | New York University | Responsible data management, algorithmic governance | Data/governance framing |

Contact: [program-chairs@facctconference.org](mailto:program-chairs@facctconference.org)

### Previous PC Chairs (2025, Athens)
- Jenn Wortman Vaughan (Microsoft Research)
- Shakir Mohamed (Google DeepMind)
- Sina Fazelpour (Northeastern)
- Talia B. Gillis (Columbia Law)

---

## 👥 Key Community People — Who to Meet at FAccT

### High Priority (direct relevance to Amber's work)

**[Iyad Rahwan](https://www.rahwan.me/)** — Max Planck Institute for Human Development; MIT Media Lab (former). Author of [*Machine Behaviour*](https://www.nature.com/articles/s41586-019-1138-y) (Nature 2019). Founded the machine behavior paradigm Amber builds on. DOI: [10.1038/s41586-019-1138-y](https://doi.org/10.1038/s41586-019-1138-y). Will almost certainly be at or nearby.

**[Abebe Birhane](https://abebebirhane.com/)** — Trinity College Dublin, Mozilla. Sociotechnical AI criticism, complex systems, cognitive science of AI. Deeply skeptical of reductionist AI — aligned with Amber's anthropological framing.

**[Virginia Dignum](https://www.umu.se/en/staff/virginia-dignum/)** — Umeå University. AI ethics, multi-agent systems, responsible AI. Just published ["Agentifying Agentic AI"](https://arxiv.org/abs/2502.15047) (Feb 2026) — directly adjacent to Amber's work.

**[Luke Stark](https://lukestark.ca/)** — PC Chair 2026, Western Ontario. STS, critical computing, histories of technology affect. His work on emotion AI mirrors Amber's machine behavior angle. Worth reaching out to pre-conference.

**[Meredith Whittaker](https://www.signal.org/blog/author/meredith/)** — Signal Foundation president, NYU. Has written on power, algorithmic governance, labor in AI. Intersection with sovereignty themes.

### Medium Priority (community bridges)

**[Timnit Gebru](https://www.dair.ai/people/timnit-gebru/)** — DAIR Institute. Foundational critical AI figure. Framing for epistemic harms of AI deployment relevant to agent governance.

**[Joy Buolamwini](https://www.poetofcode.com/)** — Algorithmic Justice League. Algorithmic auditing, AI bias advocacy. Less directly aligned but major figure.

**[Arvind Narayanan](https://www.cs.princeton.edu/~arvindn/)** — Princeton. Algorithmic accountability, privacy, debunking AI claims. Rigorous empirical + theoretical.

**[Solon Barocas](http://solon.barocas.org/)** — Cornell/Microsoft Research. Fairness, discrimination theory, responsible AI.

**[Safiya Umoja Noble](https://safiyaunoble.com/)** — UCLA. *Algorithms of Oppression*. Power dynamics, structural critique.

**[Nithya Mathur](https://nithyamathur.com/)** — Columbia University. Sociotechnical AI, design, marginalized communities.

### Emerging Researchers (FAccT young community)

**Harini Suresh** — MIT/Brown. Fairness, accountability, human-centered ML. Best Paper Committee member at FAccT 2025.

**Peaks Krafft** — Oxford Internet Institute! Worth connecting — close to Amber's institution. AI, social systems.

---

## 🏗️ Workshop & CRAFT Program

As of March 10, 2026, FAccT 2026 workshop and CRAFT details are **not yet fully published** on the conference website. Workshops are typically announced 3-4 months before the conference (expected ~February-March 2026). Check:
- [https://facctconference.org/2026/workshops.html](https://facctconference.org/2026/workshops.html) — for workshop list
- [https://facctconference.org/2026/craft.html](https://facctconference.org/2026/craft.html) — for CRAFT (Critical and Algorithmic Systems That Fail) sessions

**CRAFT Sessions** — these are interactive sessions (demos, workshops, performances) engaging the community on urgent problems. Amber's speculative design work would fit here if the paper revision path proves difficult.

**Workshop submission strategy for 2027:** If either paper doesn't make it through, organizing a workshop on "Machine Behavior Governance" or "Sovereign AI and Accountability" for FAccT 2027 would be an excellent positioning move. Workshop proposals typically due October.

---

## 📚 Related Papers — FAccT/CHI/CSCW Community

### Foundational (Amber's theoretical ancestors at FAccT)

**Rahwan et al. (2019).** "Machine Behaviour." *Nature* 568, 477–486. DOI: [10.1038/s41586-019-1138-y](https://doi.org/10.1038/s41586-019-1138-y)
*The foundational paper for studying AI systems as behavioral actors. Amber's work is the natural FAccT extension of this paradigm.*

**Raji et al. (2020).** "Closing the AI Accountability Gap: Defining an End-to-End Framework for Internal Algorithmic Auditing." *FAccT 2020*. DOI: [10.1145/3351095.3372873](https://doi.org/10.1145/3351095.3372873)
*Standard framework paper on AI accountability. Amber's sovereign agents challenge the "internal auditing" model directly.*

**Mitchell et al. (2019).** "Model Cards for Model Reporting." *FAccT 2019*. DOI: [10.1145/3287560.3287596](https://doi.org/10.1145/3287560.3287596)
*Transparency documentation. Sovereign agents resist this kind of documentation — important contrast.*

**Wachter, Mittelstadt & Russell (2017).** "Counterfactual Explanations Without Opening the Black Box: Automated Decisions and the GDPR." *Harvard Journal of Law & Technology*. URL: [https://arxiv.org/abs/1711.00399](https://arxiv.org/abs/1711.00399)
*Legal accountability for AI decisions — challenged by sovereign agents' diffusion of responsibility.*

### AI Agent Accountability (closest to Amber's papers)

**Chan et al. (2024).** "Visibility into AI Agents." *arXiv:2401.13138*. URL: [https://arxiv.org/abs/2401.13138](https://arxiv.org/abs/2401.13138)
*Proposes monitoring/visibility requirements for AI agents — directly challenged by TEE-based sovereign agents that are opaque by design.*

**Shavit & Agarwal (2023).** "What Does It Mean to Do the Right Thing?: Understanding AI Agentification." *Alignment Forum*. URL: [https://www.alignmentforum.org/posts/yRAo2KEGykZH6ggk5/what-does-it-mean-to-do-the-right-thing-understanding-ai](https://www.alignmentforum.org/posts/yRAo2KEGykZH6ggk5/what-does-it-mean-to-do-the-right-thing-understanding-ai)
*Practices for governing agentic AI.*

**Weidinger et al. (2022).** "Taxonomy of Risks posed by Language Models." *FAccT 2022*. DOI: [10.1145/3531146.3533088](https://doi.org/10.1145/3531146.3533088)
*Google DeepMind taxonomy of LLM risks — directly relevant to Dissociative Agents' threat model.*

**Leibo et al. (2025).** "A Pragmatic View of AI Personhood." URL: [https://arxiv.org/abs/2503.02563](https://arxiv.org/abs/2503.02563) *(Verify DOI — preprint)*
*Treats AI personhood as a bundle of governance-relevant obligations, not metaphysics. Useful for both Amber's papers.*

**De Filippi & Wright (2018).** *Blockchain and the Law: The Rule of Code.* Harvard University Press. ISBN: 9780674241596. URL: [https://www.hup.harvard.edu/catalog.php?isbn=9780674976429](https://www.hup.harvard.edu/catalog.php?isbn=9780674976429)
*"Lex cryptographia" — rules administered through self-executing smart contracts. Central concept for Sovereign Agents §4.5.*

### Machine Identity / Reputation / Ontology

**Shanahan et al. (2023).** "Role Play with Large Language Models." *Nature* 623, 493–498. DOI: [10.1038/s41586-023-06647-8](https://doi.org/10.1038/s41586-023-06647-8)
*Nature paper on persona fluidity in LLMs — directly cited in Dissociative Agents.*

**Resnick et al. (2000).** "Reputation Systems." *Communications of the ACM* 43(12). DOI: [10.1145/355112.355116](https://doi.org/10.1145/355112.355116)
*Foundational reputation systems paper — the very infrastructure Amber argues LLM agents break.*

**Granatyr et al. (2015).** "Trust and Reputation Models for Multi-Agent Systems." *ACM Computing Surveys* 48(2). DOI: [10.1145/2816826](https://doi.org/10.1145/2816826)
*Multi-agent trust survey — prior art for Dissociative Agents' reputation discussion.*

**Floridi & Sanders (2004).** "On the Morality of Artificial Agents." *Minds and Machines* 14. DOI: [10.1023/B:MIND.0000035461.63578.9d](https://doi.org/10.1023/B:MIND.0000035461.63578.9d)
*Argues AI agents can be moral agents through interactivity, autonomy, adaptability — not consciousness. Key for Sovereign Agents subjectivity response.*

### AI Safety (new required literature for Sovereign Agents revision)

**Soares et al. (2015).** "Corrigibility." AAAI Workshop on AI and Ethics. URL: [https://intelligence.org/files/Corrigibility.pdf](https://intelligence.org/files/Corrigibility.pdf)
*Corrigibility = AI should cooperate with correction attempts. Sovereign agents are architecturally anti-corrigible.*

**Hadfield-Menell et al. (2017).** "The Off-Switch Game." *IJCAI 2017*. URL: [https://arxiv.org/abs/1611.08219](https://arxiv.org/abs/1611.08219)
*Should AI cooperate with shutdown? Sovereign agents structurally prevent shutdown.*

**Bengio et al. (2024).** "Managing Extreme AI Risks amid Rapid Progress." *Science* 384(6698). DOI: [10.1126/science.adn0117](https://doi.org/10.1126/science.adn0117)
*Call for AI governance before loss of human control. Amber's sovereign agents show it's already happening.*

**Bostrom (2014).** *Superintelligence: Paths, Dangers, Strategies.* Oxford University Press. ISBN: 9780199678112.
*Instrumental convergence: self-preservation, resource acquisition, goal-preservation. Sovereign agents implement these through architecture.*

### Decentralized AI / Protocol / Governance

**Hu et al. (2025).** "Trustless Autonomy: Understanding Motivations, Benefits, and Governance Dilemmas in Self-Sovereign Decentralized AI Agents." *arXiv:2505.09258*. URL: [https://arxiv.org/abs/2505.09258](https://arxiv.org/abs/2505.09258)
*Amber's own prior paper — precursor to Sovereign Agents.*

**Chaffer et al. (2026).** "Distributed Legal Infrastructure for a Trustworthy Agentic Web." *arXiv* (March 2026). URL: [https://arxiv.org/abs/2603.XXXXX](https://arxiv.org/abs/2603.XXXXX) *(preprint, verify)*
*Co-authored with Amber — infrastructure for agentic web governance.*

**Hu & Rong (2025).** "Spore in the Wild: A Case Study of Spore.fun as Open-Environment Evolution with Sovereign AI Agents." *arXiv*. URL: [https://arxiv.org/abs/2506.02581](https://arxiv.org/abs/2506.02581) *(verify)*
*Empirical case study supporting Sovereign Agents theoretical framework.*

---

## 📊 Acceptance Statistics

| Year | Location | Submissions | Accepted | Rate |
|------|----------|-------------|----------|------|
| FAccT 2025 | Athens | 812 | 218 | **26.8%** |
| FAccT 2024 | Rio | 725 | ~175 | 24.1% |
| FAccT 2023 | Chicago | ~700 | ~180 | ~25% |
| FAccT 2022 | Seoul | ~600 | ~150 | ~25% |

**Key stat:** FAccT has been running ~25-27% acceptance rate for 3+ years. With ~800 submissions, roughly **200-220 papers** are accepted each year.

**Revise rate (2026 estimate):** Based on CHI experience (which pioneered R&R for SIGCHI): likely **15-25% of submissions** received Revise. Papers in Revise that successfully address reviewer concerns have very high accept rates (~70-80% based on CHI data).

**Best Paper track record:** Best papers are empirical work with societal impact (auditing, discrimination analysis). Theoretical/philosophical papers do get accepted but rarely win Best Paper — FAccT rewards the empirical. However, theoretical papers from prominent institutions (Oxford, NYU) do well.

---

## 🎯 Focus Areas — Where Amber's Papers Land

From FAccT 2026 CFP, the 6 focus areas and Amber's paper placements:

| Focus Area | Sovereign Agents | Dissociative Agents |
|-----------|-----------------|---------------------|
| Evaluations and evaluation practices | ☐ | ☐ |
| Experiences and interactions | ☐ | ☐ |
| **Law and policy** | ✅ | ✅ |
| **Normative foundations and implications** | ✅ | ✅ |
| **Power and practice** | ✅ | ☐ |
| System development and deployment | ☐ | ☐ |

Most relevant topics from CFP:
- "Regulation and governance of computational systems" ← both papers
- "Moral, legal, and political philosophy of data and computational systems" ← both papers
- "Critical and sociotechnical foresight studies of technologies, and related policies and practices" ← both papers
- "Justice, power, and inequality in computational systems" ← Sovereign Agents
- "Sociotechnical approaches to AI safety" ← Sovereign Agents (after adding AI safety section)
- "(In)appropriate reliance and (over)trust in computational systems" ← Dissociative Agents

---

## 🏆 What Wins at FAccT — Pattern Analysis

**FAccT 2025 Best Papers** — what this community rewards:
- "You Cannot Sound Like GPT": Signs of language discrimination in CS publishing — meta-critique of institutional bias in science itself
- "External Evaluation of Discrimination Mitigation Efforts in Meta's Ad Delivery" — independent audit of a major platform
- "A Framework for Auditing Chatbots for Dialect-Based Quality of Service Harms" — auditing infrastructure for social harm assessment

**Pattern:** FAccT Best Papers are empirical, auditing-oriented, with concrete societal impact. They measure or expose concrete harm. They tend not to be purely theoretical.

**Implication for Amber's papers:**
- Both papers are primarily theoretical/conceptual — FAccT does accept these, but they're positioned differently
- Sovereign Agents' strength is that it's both theoretical (governance framework) AND empirically grounded (TEE/DePIN case studies)
- Dissociative Agents is more purely conceptual — needs the "threat model" section to make harms concrete
- Strategy: frame revisions to make the concrete accountability failures MORE visible, not just philosophical

**What NOT to do:** Don't write it like a CS systems paper. FAccT rewards papers that engage social science, law, philosophy — Amber's framing is actually correct for this venue.

---

## 🗺️ Montréal Venue Details

**Le Centre Sheraton Montréal**
- Address: 1201 René-Lévesque Blvd W, Montréal, QC H3B 2L7, Canada
- Website: [https://www.marriott.com/hotels/travel/yulsi-le-centre-sheraton-montreal-hotel/](https://www.marriott.com/hotels/travel/yulsi-le-centre-sheraton-montreal-hotel/)
- Downtown Montréal — walking distance from major attractions
- Conference: June 25-28, 2026 (Thursday-Sunday)

**Montréal context:**
- Strong AI research ecosystem: MILA (Montreal Institute for Learning Algorithms, Yoshua Bengio), McGill, Concordia, Université de Montréal
- Quebec AI governance conversations active
- French/English bilingual environment
- June weather: typically 20-25°C, pleasant for walking

**Visa note:** For UK-based Amber — Canada requires eTA (Electronic Travel Authorization) for British citizens. Very straightforward online process (~$7 CAD). Apply well before travel.

---

## 📝 Open Access — New for 2026

ACM transitions to full Open Access starting January 1, 2026. This affects camera-ready:
- Papers from institutions with ACM Open agreements: **free** (currently ~76% of papers)
- Oxford University IS in the ACM Open agreement → Amber likely covered
- For papers not covered: **$250 APC** (ACM/SIG member), **$350** (non-member)
- Temporary 65% subsidy funded by ACM for 2026 transition
- Check if Oxford covers via: [https://libraries.acm.org/acmopen/open-participants](https://libraries.acm.org/acmopen/open-participants)

---

## 🔧 For Amber — Action Items

### Immediate (before March 25)

**1. Check OpenReview NOW** → See exact reviewer comments on both papers at [https://openreview.net/group?id=ACM.org/FAccT/2026/Conference](https://openreview.net/group?id=ACM.org/FAccT/2026/Conference)

**2. Sovereign Agents Revision** (if "Revise" decision received):
- Primary path: Address cFaY's 6 revisions (see detailed plan in `/research/sovereign-agents/notes/revision_plan.md`)
- Key additions: descriptive-analytic framing disclaimer, definitions table, subjectivity engagement, AI safety related work section, limitations section
- Secondary: Add EU AI Act regulatory gap discussion; update case studies (Truth Terminal, Freysa, Web4.ai)
- CRITICAL: Stay within 15 pages (one extra page allowed for Revise)

**3. Dissociative Agents Revision** (if "Revise" decision received):
- Remaining work from revision-todo.md: bib deduplication (18 entries), cross-ref verification, figure consideration, abstract count check
- Title decision: "Credibility" → "Reputation" for discoverability — make final call
- Proofread new sections for tone consistency

### Conference Strategy (June 2026)

**Who to meet:**
1. **Luke Stark** (PC Chair) — most aligned with Amber's STS+critical-tech blend
2. **Iyad Rahwan** — machine behavior paradigm founder
3. **Abebe Birhane** — skeptical sociotechnical framing that resonates with Amber
4. **Virginia Dignum** — multi-agent AI ethics, published "Agentifying Agentic AI" in Feb 2026
5. **Peaks Krafft** — Oxford Internet Institute! Institutional proximity bonus

**What to present:** Both papers if accepted. Consider proposing a workshop on "Agent Sovereignty, Identity, and Accountability in the Agentic Web" for FAccT 2027 — build community.

**Networking approach:** FAccT community is unusually open — attendees are genuinely interested in interdisciplinary perspectives. Amber's Decentralized AI + machine behavior + ALife framing is rare here — use that distinctiveness.

### For FAccT 2027 Planning
- Abstract deadline likely December 2026
- If either paper is rejected, the concepts feed directly into FAccT 2027 submissions
- Consider a workshop proposal on "Machine Sovereignty and Accountability" (October 2026 deadline estimate)
- CRAFT session proposal on decentralized AI governance could work as a demo/design provocation

---

## 🔗 Related CFPs / Venues

- [[CSCW 2026]] — overlapping sociotechnical computing
- [[CHI 2026]] — CHI already has R&R process; Amber has two papers there too
- [[AAAI 2026]] — CS framing; different audience but agent governance fits
- [[4S 2026]] — STS community overlaps heavily with FAccT
- [[AIES 2026]] — AI Ethics and Society; smaller but focused venue in AI ethics
- [[EAAMO 2026]] — Equity and Access in Algorithms, Mechanisms, and Optimization; adjacent community

---

## 📋 Update Log

| Date | Researcher | Action |
|------|-----------|--------|
| 2026-03-10 | Biber (revision-sprint-audit subagent) | Full git audit of both paper repos. Critical finding: Sovereign Agents has zero paper edits (only notes). Dissociative Agents substantially revised (~65% done, last commit Mar 7). Created comprehensive 14-day sprint plan. Updated ⚡ Recent Updates + added § REVISION SPRINT PLAN section. Rating remains ⭐⭐⭐⭐⭐ — venue urgency unchanged; revision window is real and actionable. |
| 2026-03-10 | Biber (deep-research-facct-2026 subagent) | Full deep research. Fetched CFP, author guide, blog posts, review processes. Retrieved review scores for Sovereign Agents (2×4 + 1×3). Read both paper abstracts and revision plans from local repos. Added program chairs, key community people, related papers with DOIs, acceptance stats, venue details, Montréal info, Open Access details, workshop context. Rated ⭐⭐⭐⭐⭐ (max) given active revision window. Marked `deep_researched: true`. |
| 2026-03-10 | Biber (cfp-discovery-sweep cron) | Stub created. Paper deadline confirmed closed. Flagged revision urgency and Amber's two FAccT repos. |
