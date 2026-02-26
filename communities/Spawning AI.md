---
rating: ⭐⭐⭐
url: https://spawning.ai/
based: Berlin, Germany (team distributed; Holly Herndon & Mat Dryhurst in Berlin)
added: 2026-02-26
last_researched: 2026-02-26
revisit_weeks: 4
next_research: 2026-03-26
tags: [ai-ethics, computational-creativity, critical-computing, machine-behavior, participatory]
deep_researched: true
---

# Spawning AI

## ⚡ Recent Updates
- **2026-02-26:** Full deep research. Expanded from stub to comprehensive profile. All key tools, history, publications, and policy contributions documented.

**"Building the consent layer for AI."** The most practically consequential artist-led AI ethics initiative of the 2020s. Spawning builds real infrastructure for artist data sovereignty in AI training — not just advocacy or critique, but working tools that major AI companies have adopted. Co-founded in September 2022 by [[Holly Herndon]], [[Mat Dryhurst]], Jordan Meyer, and Patrick Hoepner. Based between Berlin and the US.

## Mission & Objectives

**Core mission:** Build the consent infrastructure for AI training data. Make it possible for artists to know if their work was used, opt out of future training, and eventually be compensated for use.

**The key framing:** Dryhurst and Herndon coined the term "spawning" to distinguish AI data reproduction from 20th-century sampling and collage. Their argument: "A human piecing together a new work from snippets of older works is fundamentally distinct from the automated ability to spawn infinite works in the style or likeness of someone from training data." This distinction is politically and legally significant — it demands new frameworks, not extensions of old ones.

**Two-sided approach:** 
1. **Opt-out tools** — artists can register their consent preferences via machine-readable signals, checked by AI trainers
2. **Opt-in datasets** — curated, fully consenting/public-domain training data as an ethical alternative to scraping

**Not IP maximalism:** Spawning explicitly positions itself between "free culture" ideology and "rigid IP protectionism." The goal is a consent layer, not a copyright enforcement weapon. Dryhurst: "We're not looking to build tools for DMCA takedowns and copyright hell."

## History & Founding

**2016–2022:** Holly Herndon and Mat Dryhurst begin training neural networks in their Berlin studio, making the deliberate decision to use only consenting data — initially just their own voices and data from participants who explicitly agreed.

**2019:** Album *Proto* (Holly Herndon) introduces "Spawn" — an AI trained exclusively on consenting human voices through "training ceremonies." The name directly prefigures Spawning AI's philosophy.

**2021:** Holly+ launches — a deepfake voice synthesis tool with consent-based governance model. Herndon and Dryhurst win [2022 Ars Electronica STARTS Prize for Digital Art](https://starts-prize.aec.at/en/holly-plus/) for Holly+.

**September 2022:** Spawning formally launches. Herndon and Dryhurst team up with **Jordan Meyer** and **Patrick Hoepner** (founders of WolfBear software studio) to build the consent infrastructure at scale.

**October 2022:** [Have I Been Trained?](https://haveibeentrained.com/) launches — allows artists to search ~5.8 billion images in the LAION-5b dataset (used to train Stable Diffusion and Midjourney) and register consent preferences.

**December 2022:** Stability AI commits to honor Spawning's opt-out registry when training Stable Diffusion 3.

**March 2023:** Spawning announces 80 million artworks opted out of Stable Diffusion 3 training, through partnerships with ArtStation and Shutterstock plus 40,000+ direct requests. "This establishes a significant precedent towards realizing our vision of consenting AI."

**May 2024:** [Source.Plus](https://source.plus/) launches — a curation platform for fully consenting, non-infringing AI training data. Seeded with ~40 million public domain and CC0 images from libraries and museums worldwide.

**October 2024:** [Public Domain 12M (PD12M)](https://arxiv.org/abs/2410.23144) released — 12.4 million high-quality public domain and CC0 images curated from Source.Plus, designed for training text-to-image models. Published on [Hugging Face](https://huggingface.co/Spawning) under CDLA-Permissive-2.0.

**December 2024:** Public Diffusion — a foundation model trained exclusively on public domain and CC0 images — enters private beta. Designed for fine-tuning, so artists' fine-tuned models are entirely theirs.

**As of 2026:** Source.plus domain listed for sale; Have I Been Trained? and spawning.ai in maintenance mode. The Do Not Train registry (~2 billion rights reservations) continues to operate.

## Key People

- **[[Holly Herndon]]** ⭐⭐⭐ — Co-founder. American composer and artist, PhD Stanford (Computer Music). Based Berlin. Long-term conceptual architect of AI consent philosophy. *Proto* and Spawn as precursors to Spawning's mission.
- **[[Mat Dryhurst]]** ⭐⭐⭐ — Co-founder. British artist, technologist, cultural theorist. Based Berlin. Primary public intellectual voice for Spawning. Author of "[AI Art and the Problem of Consent](https://artreview.com/ai-art-and-the-problem-of-consent/)" (Art Review, 2023). Previously built Saga (2015), a self-hosting framework for artists. Teaches at NYU Clive Davis Institute.
- **Jordan Meyer** ⭐⭐ — Co-founder (technical lead). Musician background, photojournalism track at UNC Chapel Hill. Led PD12M dataset curation and Public Diffusion model development. Submitted the PD12M arXiv paper.
- **Patrick Hoepner** ⭐⭐ — Co-founder. Also from WolfBear software studio alongside Meyer.
- **Laura Exline** — Communications/editorial lead. Writes the Spawning Substack.
- **Nick Padgett** — Engineer. Co-developer of Public Diffusion with Jordan Meyer. Has fine arts background (originally planned to study art before CS).
- **Cullen Miller** — Legal/policy researcher. Wrote the analysis of the Hamburg Court's LAION ruling (2024).

## Key Publications & Output

### Tools
- **[Have I Been Trained?](https://haveibeentrained.com/)** — Search engine for ~5.8 billion images in LAION-5b dataset. Artists can register consent preferences (opt in/out).
- **[Do Not Train Registry](https://spawning.ai/)** — Machine-readable registry of ~2 billion rights reservations. AI trainers can query this database to respect artist wishes.
- **[Source.Plus](https://source.plus/)** — Platform to curate, enrich, and download non-infringing media collections for AI training. Seeded with ~40 million public domain/CC0 images from libraries and museums worldwide.

### Datasets (via Hugging Face)
- **[PD12M](https://huggingface.co/datasets/Spawning/PD12M)** — 12.4 million public domain/CC0 image-text pairs for training text-to-image models. Designed as consent-compliant replacement for CC12M and CC3M.
- **[PD3M](https://huggingface.co/datasets/Spawning/PD3M)** — 3.3 million aesthetically curated subset of PD12M.
- **[megalith-cc0](https://huggingface.co/datasets/Spawning/megalith-cc0)** — 2.39M CC0 images.

### Models
- **Public Diffusion** — Foundation model trained exclusively on public domain/CC0 data. Designed for fine-tuning by artists who want to own the result. Beta launched late 2024.

### Papers
- [*A Highly Aesthetic Image-Text Dataset with Novel Governance Mechanisms*](https://arxiv.org/abs/2410.23144) (Meyer et al., arXiv 2410.23144, 2024) — PD12M paper. Novel dataset governance mechanisms including community flagging and versioning.

### Writing & Policy
- **Mat Dryhurst**, "[AI Art and the Problem of Consent](https://artreview.com/ai-art-and-the-problem-of-consent/)" (Art Review, 2023) — Key philosophical essay framing "spawning" vs. sampling, arguing for new consent protocols
- **[Spawning Substack](https://spawning.substack.com/)** — Regular posts on rights reservations, TDM law, dataset curation
- **EU AI Act policy** — Spawning's approach cited by [Open Future](https://openfuture.eu/blog/protecting-creatives-or-impeding-progress) as instructive for EU text and data mining policy under the Copyright in the Digital Single Market Directive (Articles 3 & 4)

## Key Contributions

1. **Have I Been Trained?** — First searchable dataset transparency tool for artists at scale. Made invisible AI training visible to creators.
2. **Do Not Train Registry** — Machine-readable consent infrastructure. First major AI companies (Stability AI) have committed to honoring it.
3. **80 million opt-outs** (March 2023) — Concrete precedent: showed that opt-out at scale works when partnered with platforms.
4. **Source.Plus / PD12M** — Viable ethical alternative to web scraping. Proof-of-concept that you can train competitive models on fully consenting data.
5. **Conceptual framing** — "Spawning" as distinct from sampling; the argument for a third way between IP maximalism and free culture. Cited by EU policy researchers.
6. **Hamburg Court analysis** — Commentary on LAION ruling (2024), establishing importance of "time-of-training compliance" in AI data governance.

## Philosophy & Key Arguments

**"Spawning ≠ Sampling":** The reproductive scale of AI training is categorically different from human creative borrowing. One person sampling another's work is different from training a model that can then infinitely replicate styles and voices.

**The Ted Nelson argument:** Dryhurst traces the problem to Tim Berners-Lee's decision to use one-directional links (HTML) rather than Ted Nelson's bi-directional hypertext (Xanadu). If the web had attribution baked in from the start, AI training data provenance would be tractable. Spawning is trying to retrofit this.

**Consent → trust → participation:** Dryhurst believes more artists will ultimately *opt in* than out, but consent must come first to establish trust. "More will ultimately opt in than out, but first we have to establish a common respect."

**Not anti-AI:** Explicitly pro-AI-augmentation. "I am a deep believer in AI-augmented expression, and have no desire to limit experimentation or enshrine outdated IP laws." The goal is to fix the consent layer so artists can participate willingly.

**Community model of value:** Holly Herndon's "training ceremonies" for Spawn — communal singing events to train the AI — point to an alternative model where AI training is participatory and consensual, not extractive.

## Connected Institutions

- **[Stability AI](https://stability.ai/)** — First major AI company to commit to Spawning's opt-out registry for Stable Diffusion 3
- **[ArtStation](https://www.artstation.com/)** / **[Shutterstock](https://www.shutterstock.com/)** — Platform partners for the 80M opt-out campaign
- **[LAION](https://laion.ai/)** — Dataset that HaveIBeenTrained searches; subject to Hamburg court ruling (2024)
- **[WolfBear Studio](http://wolfbearstudio.com/)** — Software studio of co-founders Jordan Meyer and Patrick Hoepner
- **[AWS Open Data Sponsorship Program](https://aws.amazon.com/opendata/open-data-sponsorship-program/)** — Partners for hosting PD12M dataset (~30TB)
- **[Open Future](https://openfuture.eu/)** — EU digital policy think tank that has cited Spawning's approach

## For Amber

### Why Interesting
Spawning is the exemplary case of **practical critical computing**: artists building the infrastructure they need rather than just critiquing what exists. This is precisely what Amber's research taste signals as most interesting — not just asking "who benefits?" but building an answer.

**Direct relevance to Amber's work:**
- **AI ethics as design problem** — Spawning treats consent infrastructure as a design challenge. The tools (Have I Been Trained, Do Not Train registry, Source.Plus) are designed artifacts that embody an ethical position.
- **Participatory approach** — The "training ceremonies" for Spawn are participatory design applied to AI. A community of humans teaching a machine together, consensually.
- **Critical computing in action** — Not just critique of AI power structures, but building alternative infrastructure. The model: identify a structural problem → build the missing layer.
- **Policy traction** — Spawning's work has directly shaped EU AI Act and CDSM Directive interpretation. Shows how artist-built tools can have legislative impact.

### How Can Amber Engage
- **Research citation** — Spawning's approach is directly relevant to Amber's critical AI work. Cite HaveIBeenTrained and the "spawning vs. sampling" distinction in publications.
- **Tools for research** — Use Source.Plus / PD12M as ethically sound resources for any AI research that requires image training data.
- **Holly Herndon & Mat Dryhurst direct connection** — Both deeply engaged with academic communities (Dryhurst teaches at NYU, lectures at European Graduate School). Amber's work bridges the same art-AI-ethics territory.
- **Interdependence Podcast** — Their podcast ([launched April 2020](https://pitchfork.com/news/holly-herndon-launches-new-podcast-with-mat-dryhurst/)) features artists, technologists, and theorists at the frontier of AI and art. Potential guest slot as Amber's profile grows.
- **Publication targets** — Art Review (where Dryhurst published "AI Art and the Problem of Consent") publishes at the intersection of art and AI that Amber could target.

### Who Should Amber Know
- **[[Mat Dryhurst]]** — primary intellectual architect. His writing on consent, attribution, and the political economy of AI training data is closest to Amber's critical computing interest.
- **[[Holly Herndon]]** — artist-researcher model Amber could learn from. The PhD + practice combination, the "training ceremonies" as participatory methodology.
- **Jordan Meyer** — technical lead. If Amber's work moves toward empirical AI research or dataset ethics, Meyer is a collaborator to know.

### Key Publications to Be Part Of
- **Art Review** — Dryhurst's platform for critical AI/art writing. High profile, right community.
- **[The Creative Independent](https://thecreativeindependent.com/)** — Published Dryhurst's foundational essay "On Redesigning the System" (2019). Art-tech-critical-theory sweet spot.
- **[Rhizome](https://rhizome.org/)** — Has featured both Herndon and Dryhurst on net art, digital culture, AI.

### Collaboration Potential
**High.** Spawning occupies the exact overlap of Amber's core threads: critical computing + participatory design + computational creativity + machine behavior. The specific gap Amber could fill: **academic legitimation**. Spawning has built brilliant tools and made compelling arguments but primarily from artist/activist positioning. Academic research framing (with proper citations, empirical backing, design methodology) would strengthen their policy traction and is the thing Amber is specifically positioned to contribute.

## Recent Events That Matter

- **October 2024:** PD12M published on arXiv and Hugging Face — major milestone for ethical training data at scale
- **October 2024:** Hamburg Court LAION ruling — established legal precedent for time-of-training compliance, directly validating Spawning's approach
- **December 2024:** Public Diffusion private beta — proof-of-concept that fully-consenting models can be competitive
- **2023:** EU AI Act debate — Spawning's approach cited as instructive model for European TDM rights reservations
- **March 2023:** 80 million opt-out milestone — first demonstration of opt-out at scale working

## Why Interesting

**Artist-built critical infrastructure.** Spawning is the best current answer to the question: "What does it look like when artists build the tools they need instead of waiting for tech companies or regulators?" It's not just advocacy — it's working code, running datasets, and real policy impact.

**Edge of chaos.** The AI training data consent question is one of the fastest-evolving legal/ethical/political disputes of the 2020s. Spawning sits at the exact center: watching multiple forces (EU AI Act, US fair use lawsuits, model company policies, artist movements) collide in real time.

**The "third way" conceptual move.** The framing — between IP maximalism and free culture, consent not censorship — is genuinely new thinking. Not just "artists vs. AI companies" but building a consent layer that enables productive AI development while protecting creators. This is the kind of ideologically sophisticated problem-solving that Amber's research taste gravitates toward.

**Connects to Amber's deepest interests:** The "training ceremony" concept (participatory, communal, embodied AI interaction) is directly adjacent to more-than-human design, participatory methodologies, and the question of what it means to include non-human actors in co-creation.

## 📋 Update Log
| Date | Researcher | Action |
|------|-----------|--------|
| 2026-02-26 | Biber (subagent) | Initial community note created. Discovered during Holly Herndon research. |
| 2026-02-26 | Biber (subagent) | Full deep research. Expanded to gold standard. Added full history, tools, datasets, policy contributions, key people bios, EU policy connections, publication details. |
