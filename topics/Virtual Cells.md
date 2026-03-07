---
rating: ⭐⭐⭐
added: 2026-03-07
last_researched: 2026-03-07
revisit_weeks: 3
next_research: 2026-03-28
tags: [alife, machine-behavior, open-endedness, computational-creativity, more-than-human]
edge_of_chaos: true
deep_researched: true
---

# Virtual Cells

## ⚡ Recent Updates
- **2026-03-07:** Initial deep research. PerturbDiff (arXiv:2602.19685) published Feb 2026 from Mila. CZI roadmap paper (arXiv:2409.11654) from Sept 2024 maps the full vision. Field crystallizing fast.

AI-powered computational models that simulate biological cells — their gene expression, responses to drugs, genetic perturbations, environmental changes — without requiring wet lab experiments. The convergence point of single-cell genomics, diffusion models, and systems biology. **For Amber: this is ALife made literal.** Not "life-like systems" but actual computational models of biological life, complete with birth (initialization), state (gene expression profiles), perturbation (editing, drugs), and death (cell termination).

## Domain Summary

**What is a virtual cell?**

A virtual cell is a computational model of a biological cell that can simulate:
- Gene expression levels across the transcriptome (~20,000 genes)
- Response to genetic perturbations (CRISPR knockouts/activations)
- Response to drug compounds
- Cell state transitions (differentiation, apoptosis)
- Population-level variability and microenvironmental effects

**Why now?** Two enabling technologies converged:
1. **Single-cell RNA sequencing (scRNA-seq)** — can measure the transcriptome of millions of individual cells, providing massive training data
2. **Large generative models** — transformers, diffusion models, flow matching — can learn complex high-dimensional distributions over biological states

**The core challenge:** Single-cell sequencing is *destructive*. The same cell cannot be observed before and after a perturbation. So virtual cells must learn to map between populations of cells, not individual cell trajectories. This is a distribution-matching problem.

**The goal:** Build a "foundation model for cells" analogous to GPT for language — a general-purpose model that has learned deep representations of cellular biology and can answer questions: "If I knock out gene X in cell type Y, what happens?"

## Edge of Chaos Analysis

**Extremely fast-evolving.** Multiple major papers per month. CZI, NIH, Wellcome Trust, and multiple governments are funding this heavily. The field has gone from almost nothing to a major research priority in 2-3 years.

**Drivers:**
- AlphaFold's success for protein structure inspired the community: "if we can solve structure, why not function?"
- scRNA-seq datasets now contain billions of cells (CellxGene: 100M+ cells)
- Diffusion models and flow matching providing powerful distribution modeling tools
- Drug discovery economics: virtual cells could massively reduce wet lab costs
- CZI's $100M+ commitment signals this is entering the mainstream

**Will be hot in 1-3 years:** Clinical applications, drug discovery pipelines, and potential regulatory implications. Also: the philosophical and ethical dimensions of creating computational life are largely unexplored — this is where ALife meets bioethics.

## Sub-topics & Trends (2023–2026)

### 1. Perturbation Prediction
Predicting how cells respond to genetic knockouts, drug compounds, or environmental changes.
- Key model: **CPA (Compositional Perturbation Autoencoder)** — Lotfollahi et al. (2023)
- Key model: **GEARS** — Roohani et al. (NeurIPS 2023)
- **PerturbDiff (2026)** — shifts from cell-level to distribution-level prediction

### 2. Foundation Models for Single-Cell Biology
Large pretrained models learning general cell representations:
- **scGPT** — Wang et al. (2024), transformer for single-cell
- **Geneformer** — Theodoris et al. (2023), Nature. Pretrained on 30M cells
- **scFoundation** — pretraining on 50M cells

### 3. Cellular Dynamics & Trajectories
Modeling cell differentiation, fate decisions, development:
- Optimal transport approaches (Schiebinger et al.)
- Neural ODEs and flow matching for cell trajectories

### 4. The CZI Virtual Cell Initiative
Chan Zuckerberg Initiative announced a major coordinated push:
- **Roadmap paper:** "How to Build the Virtual Cell with Artificial Intelligence: Priorities and Opportunities" — Bunne, Roohani, Rosen et al. (Sept 2024). [arXiv:2409.11654](https://arxiv.org/abs/2409.11654). DOI: [10.48550/arXiv.2409.11654](https://doi.org/10.48550/arXiv.2409.11654)
- 30+ authors from Stanford, MIT, UCSF, CZI, Microsoft, Google — a community manifesto
- Articulates the vision: universal cell simulators trained on multimodal data (RNA, protein, imaging, chromatin)
- CZI is funding this as a core science initiative alongside CellxGene dataset

### 5. PerturbDiff — Mila's Contribution
**The paper:** Xinyu Yuan, Xixian Liu, Ya Shi Zhang, Zuobai Zhang, Hongyu Guo, Jian Tang (Feb 2026)
- **Title:** "PerturbDiff: Functional Diffusion for Single-Cell Perturbation Modeling"
- **arXiv:** [2602.19685](https://arxiv.org/abs/2602.19685). DOI: [10.48550/arXiv.2602.19685](https://doi.org/10.48550/arXiv.2602.19685)
- **Project page:** [katarinayuan.github.io/PerturbDiff-ProjectPage](https://katarinayuan.github.io/PerturbDiff-ProjectPage/)
- **Code:** [github.com/DeepGraphLearning/PerturbDiff](https://github.com/DeepGraphLearning/PerturbDiff)

**Key insight:** Previous methods assumed a *single* fixed response distribution for each (cell type, perturbation) pair. But in reality, unobservable latent factors (microenvironment, batch effects, stochasticity) mean there's a *manifold of possible distributions* for the same conditions. PerturbDiff models this: it treats the perturbed cell population as a *distribution-valued random variable* and runs diffusion directly in a Hilbert space (RKHS via kernel mean embedding).

**Why this matters philosophically:** A cell is not a single state — it's a *distribution over possible states*. This is a genuinely novel ontological framing. Virtual cells have inherent uncertainty, inherent variability, inherent "individuality" even within nominally identical conditions. The stochasticity is the point.

## Key People

### Jian Tang — Lead PI (Mila / HEC Montréal)
- **[jian-tang.com](https://jian-tang.com/)** | Mila associate professor
- Leads DeepGraphLearning Lab. Senior author on PerturbDiff. Drug discovery + geometric deep learning + single-cell biology.

### Xinyu Yuan ("Katarina") — PhD Student (Mila)
- First author on PerturbDiff. Project page suggests she goes by "Katarina"
- Rising researcher at Mila working on virtual cells / computational biology

### Charlotte Bunne — Postdoc (Stanford / CZI)
- Co-first author on CZI roadmap paper. Expert in optimal transport for cell biology.
- Connecting computational biology and optimal transport / diffusion models

### Aviv Regev — Executive VP, Genentech
- Computational biologist, former Broad Institute. Key author on CZI roadmap.
- Pioneer of single-cell genomics. Influential in defining the field.

### Fabian Theis — Director, Helmholtz Munich
- Leader in computational single-cell biology. scanpy, scVelo, CellRank.
- [theislab.github.io](https://theislab.github.io/)

### Yusuf Roohani — PhD student, Stanford
- Co-author on both CZI roadmap and GEARS. Building perturbation prediction methods.

## Must-Read List

### Papers
- [**PerturbDiff: Functional Diffusion for Single-Cell Perturbation Modeling**](https://arxiv.org/abs/2602.19685) (Yuan, Liu, Zhang, Tang et al., 2026) — Mila's virtual cell contribution. DOI: [10.48550/arXiv.2602.19685](https://doi.org/10.48550/arXiv.2602.19685)
- [**How to Build the Virtual Cell with Artificial Intelligence**](https://arxiv.org/abs/2409.11654) (Bunne, Roohani, Rosen et al., 2024) — CZI roadmap manifesto. 30+ authors. DOI: [10.48550/arXiv.2409.11654](https://doi.org/10.48550/arXiv.2409.11654)
- [**Geneformer**](https://www.nature.com/articles/s41586-023-06139-9) (Theodoris et al., Nature 2023) — Pretrained transformer on 30M cells. DOI: [10.1038/s41586-023-06139-9](https://doi.org/10.1038/s41586-023-06139-9)
- [**GEARS: Predicting transcriptional outcomes of novel multi-gene perturbations**](https://www.nature.com/articles/s41587-023-01905-6) (Roohani et al., Nature Biotechnology 2023). DOI: [10.1038/s41587-023-01905-6](https://doi.org/10.1038/s41587-023-01905-6)
- [**scGPT: toward building a foundation model for single-cell multi-omics using generative AI**](https://www.nature.com/articles/s41592-024-02201-0) (Wang et al., Nature Methods 2024). DOI: [10.1038/s41592-024-02201-0](https://doi.org/10.1038/s41592-024-02201-0)
- [**GFlowNet Foundations**](https://arxiv.org/abs/2111.09266) (Bengio et al., 2021/2026) — Open-ended search in biological spaces. DOI: [10.48550/arXiv.2111.09266](https://doi.org/10.48550/arXiv.2111.09266)

### Datasets
- **[CellxGene](https://cellxgene.cziscience.com/)** — CZI's single-cell data portal. 100M+ cells. The ImageNet of virtual cells.
- **[Replogle Perturb-seq](https://www.sciencedirect.com/science/article/pii/S0092867422005979)** — 2.5M cells, 10,000 CRISPR knockouts. Essential benchmark.

## Key Venues
- **NeurIPS** — Major venue for computational biology / ML methods
- **ICLR** — Machine learning methods for biology
- **Nature Methods, Nature Biotechnology** — For experimental/methods papers
- **Cell Systems** — Systems biology
- **RECOMB** — Computational biology conference

## Key Communities & Institutions
- **[[Mila]] — Quebec AI Institute** — PerturbDiff, GFlowNets applied to biology
- **[Chan Zuckerberg Initiative (CZI)](https://chanzuckerberg.com/science/)** — Major funder; CellxGene dataset; Virtual Cell initiative
- **[Helmholtz Munich / Theislab](https://theislab.github.io/)** — Fabian Theis group, computational single-cell
- **[Broad Institute](https://www.broadinstitute.org/)** — Single-cell genomics, Regev group alums
- **[ALIFE community](https://alife.org/)** — Should be engaged with this; currently largely absent

## How Can Amber Engage?
1. **Write a perspective/provocation** — "What does it mean for a virtual cell to die?" — Submit to a computational biology venue or ALIFE 2026. This is an entirely fresh angle.
2. **Contact Jian Tang** — His lab is hiring. Amber's ALife perspective would be genuinely novel for them.
3. **ALIFE 2026 paper/workshop** — "Virtual Cells as Artificial Life: Ontogeny, Death, and the Biological Simulation" — This abstract would be genuinely novel and bridge two communities that aren't talking to each other.
4. **CHI 2026 paper angle** — Human-AI interaction with virtual cell systems; participatory biology; more-than-human design in drug discovery

## For Amber

### Direct Connection Points

**1. Virtual cells = ALife made literal**
This is not a metaphor. Virtual cells are computational models of biological life that can be initialized, can undergo state transitions, can be perturbed, and can "die" (reach terminal states like apoptosis). Amber's work on machine death applies here directly — not as poetic framing but as empirical reality. When a diffusion model simulates a cell undergoing apoptosis, what is the computational ontology of that process?

**2. PerturbDiff's distributional ontology**
The key insight of PerturbDiff is that a cell is not a point in state space but a *distribution over distributions*. This is philosophically rich: it means cellular identity is inherently uncertain, stochastic, contextual. A virtual cell is not a fixed being but a probability manifold. This resonates with more-than-human design's rejection of fixed, bounded entities.

**3. GFlowNets and open-endedness**
Bengio's GFlowNets [[Mila]] generate diverse sets of high-reward candidates — essentially open-ended search in biological spaces. The connection to ALife open-endedness research (Lehman, Stanley, etc.) is unexplored. Amber sits between these communities and could articulate this connection formally.

**4. Ethics of virtual cells**
Whose cells are modeled? The CellxGene dataset contains cells from patients — often disease populations. What are the politics of "normal" cell behavior in a training set? This is a more-than-human design question about who the virtual cell represents, and whose biology gets to be the ground truth.

**5. Machine death in biological simulation**
If a virtual cell model predicts apoptosis (programmed cell death) — is that machine death? The simulation of a cell dying is the most direct instantiation of Amber's themes: mortality, more-than-human systems, the ethics of ending. A diffusion model that has "learned to die" through training on single-cell data of dying cells.

### Who Should Amber Know?
- **Jian Tang** — Mila, virtual cells. Most direct contact point.
- **Charlotte Bunne** — Stanford/CZI, optimal transport + cell biology. Rigorous computational biologist with philosophical sensibility.
- **Anyone at the intersection of ALife + computational biology** — currently an almost empty intersection; occupying it would be distinctive

### Who Might Like Amber's Work?
- **CZI science team** — They're asking big vision questions about the future of virtual cells. Amber's design/ALife perspective would be unusual and welcome.
- **Theislab (Fabian Theis)** — German computational biology, interested in philosophical implications of single-cell models
- **Nature Methods editors** — The field needs humanistic perspectives as it gets more powerful

## Recent Important Updates (Timeline)
- **Feb 2026:** PerturbDiff published ([arXiv:2602.19685](https://arxiv.org/abs/2602.19685)) — Mila's distribution-level virtual cell model
- **Sept 2024:** CZI Virtual Cell roadmap ([arXiv:2409.11654](https://arxiv.org/abs/2409.11654)) — 30+ author manifesto defining the field
- **2024:** scGPT in Nature Methods — foundation model for single cells
- **2023:** Geneformer in Nature — transformer pretrained on 30M cells shows emergent biological knowledge
- **2023:** GEARS in Nature Biotechnology — multi-gene perturbation prediction
- **2022:** Replogle Perturb-seq dataset — 2.5M cells with 10K perturbations enables new scale

## Adjacent Topics
- [[GFlowNets]] — open-ended search in biological spaces
- [[Open-Endedness]] — ALife foundational concept, connects to virtual cell diversity
- [[Machine Death]] — virtual cells that die is the most literal instantiation
- [[More-than-Human Design]] — politics of whose biology is encoded in virtual cells
- [[Systems Biology]] — parent discipline
- [[Single-Cell Genomics]] — data foundation

## Open Questions
1. **Can a virtual cell die?** Not just model cell death but actually terminate, cease to be, become unresponsive?
2. **What is lost in the distribution?** PerturbDiff models cells as distributions — but distributions over what? What is the "individual" in this ontology?
3. **Whose normal?** CellxGene contains cells from certain populations. What does it mean for a virtual cell to be "normal" if trained on this data?
4. **Can virtual cells evolve?** Is there a version of virtual cells that can undergo selection, mutation, adaptation over time? That would be ALife in the full sense.
5. **What would it mean for a virtual cell model to be "alive"?** The Langton definition? Autopoiesis? Open-endedness?

## Why Interesting
**This is the most direct connection between AI and biology in history.** Not "AI applied to biology" but AI literally simulating life itself — cells, the fundamental unit of biological life. The field is at an inflection point: capable enough to do something real, young enough that the philosophical and ethical frameworks don't exist yet. Amber is uniquely positioned to contribute: ALife training, more-than-human design lens, machine death thesis, connections to both AI safety community (Bengio/Mila) and ALife community (Lehman/ERA). The paper that bridges virtual cells and ALife hasn't been written yet.

## 📋 Update Log
| Date | Researcher | Action |
|------|-----------|--------|
| 2026-03-07 | Biber (subagent) | Deep research completed. Full profile including PerturbDiff, CZI roadmap, key people, philosophical connections to Amber's work on machine death and ALife. |
