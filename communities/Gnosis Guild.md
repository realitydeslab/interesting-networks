---
rating: ⭐⭐⭐
url: https://www.gnosisguild.org/
added: 2026-02-26
last_researched: 2026-03-01
revisit_weeks: 8
next_research: 2026-04-26
tags: [critical-computing, participatory]
deep_researched: true
---

# Gnosis Guild

## ⚡ Recent Updates
- **2026-03-01:** Initial deep research. Comprehensive profile written. Key pivot: Enclave (FHE+ZKP+MPC for encrypted execution environments) identified as major 2024-2025 development beyond Zodiac.
- **2024:** Enclave protocol open-sourced — new direction toward Encrypted Execution Environments (E3) using fully homomorphic encryption.
- **2022:** ERC-5005 (Zodiac Modular Accounts) submitted to Ethereum Improvement Proposals by Auryn Macmillan + Kei Kreutler.
- **2021:** Zodiac protocol released (September 2021). MIT Computational Law Review paper published.

Small, philosophically-grounded team of ~6-10 builders that created the Zodiac open standard — the dominant composable governance infrastructure for DAOs — and more recently, the Enclave protocol for privacy-preserving computation. Built out of Gnosis (Berlin, 2017–2022), now independent. One of the most intellectually serious organizations in the crypto-governance space.

## Mission & Objectives

**Mission:** To build composable, modular, open-source software for organizations — tools that empower organizations to customize governance rather than lock them into monolithic platforms.

**Two product eras:**

**Era 1 — Zodiac (2021–present):** Composable governance infrastructure for DAOs. The Zodiac protocol (ERC-5005) establishes a standard that separates the "avatar" (the programmable account/treasury) from its authorization and execution logic, allowing any combination of governance modules to be added, removed, or replaced. This is analogous to how plug-in architecture works in software design — applied to organizational governance.

**Era 2 — Enclave (2024–present):** Open-source protocol for Encrypted Execution Environments (E3). Combines Fully Homomorphic Encryption (FHE), Zero Knowledge Proofs (ZKPs), and Multi-Party Computation (MPC) to enable collaborative confidential computation with cryptographic (not hardware-based) integrity and privacy guarantees.

**Core philosophy:** Composable design = organizational freedom. Organizations shouldn't be locked into monolithic governance platforms. Like Christopher Alexander's pattern language for architecture, Gnosis Guild builds a pattern language for organizations — modular, recombineable, context-specific solutions to governance problems.

## Key People

### Kei Kreutler — Co-creator / Philosopher-in-Residence
[keikreutler.net](https://keikreutler.net) | GitHub: [@keikreutler](https://github.com/keikreutler)
- Co-created Gnosis Guild while at Gnosis, Berlin (2017–2022)
- Co-authored ERC-5005 (Zodiac standard) with Auryn Macmillan
- Philosopher, writer, and researcher; the intellectual voice of the Guild's work
- Now at [Inner Library](https://innerlibrary.net) consultancy — advising on organizational design, memory, and strategy
- Contributor to [Other Internet Research Institute](https://otherinter.net)
- Board member of [Regen Foundation](https://regen.foundation)
- Core Researcher, [[Summer of Protocols]] 2023; leads Memory Research Group SIG (ongoing)
- Upcoming book: *Artificial Memory* — on how memory changes with computing and protocols
- Published in: Serpentine Galleries (*All Media is Training Data*, 2024), MIT Press (*Catastrophe Time!*, 2023), Torque Editions (*Radical Friends*, 2022), Anthropocene Curriculum (2018)
- Essays: "A Prehistory of DAOs: Cooperatives, gaming guilds, and the networks to come" (2021), "Inventories, Not Identities: Why multisigs are the future of online accounts" (2021)
- Based: Northeastern United States (mountainside, post-Berlin)
- **Assessment:** ⭐⭐⭐ — see [[Kei Kreutler]] for full note

### Auryn Macmillan — Co-creator / Lead Developer
GitHub: [@auryn-macmillan](https://github.com/auryn-macmillan)
- Co-created Gnosis Guild
- Co-authored ERC-5005 (Zodiac Modular Accounts standard)
- Lead developer across Zodiac ecosystem and Enclave protocol
- Active contributor to Enclave (FHE/MPC protocol)
- **Assessment:** ⭐⭐ — technical co-founder, worth a stub note

### Ryan Yardley (ryardley) — Core Developer
GitHub: [@ryardley](https://github.com/ryardley)
- Primary contributor to Enclave codebase
- **Assessment:** ⭐ — technical contributor

### Other Contributors (Enclave)
Hamza Khalid, Cristóvão, Nathan Ginnever, Giacomo, Cedoor — active on Enclave protocol

## Key Publications & Output

- [Composable Expansion Packs for Decentralized Organizations](https://law.mit.edu/pub/composableexpansionpacks/release/1) — MIT Computational Law Review. The definitive paper articulating Zodiac's philosophy and architecture.
- [ERC-5005: Zodiac Modular Accounts](https://eips.ethereum.org/EIPS/eip-5005) (Macmillan + Kreutler, April 2022) — the Ethereum Improvement Proposal defining the open standard. Currently "Stagnant" status (draft never finalized, but the de facto standard is in use regardless)
- [A Prehistory of DAOs](https://gnosisguild.mirror.xyz/t4F5rItMw4-mlpLZf5JQhElbDfQ2JRVKAzEpanyxW1Q) (Kreutler, 2021) — influential essay on cooperatives, gaming guilds, and the organizational history of DAOs
- [Inventories, Not Identities](https://medium.com/gnosis-pm/inventories-not-identities-7da9a4ec5a3e) (Kreutler, 2021) — essay on multisig wallets as identity infrastructure
- [Gnosis Guild blog](http://gnosisguild.mirror.xyz/) — essays and updates on Mirror

## Key Contributions

### Zodiac Protocol (2021–present)
[zodiac.wiki](https://www.zodiac.wiki) | [GitHub](https://github.com/gnosisguild/zodiac) (479★)

**The architecture:**
- **Avatars** — programmable Ethereum accounts (e.g., Safe/Gnosis Safe) that hold balances and execute transactions
- **Modules** — contracts that implement governance/decision logic; enabled by avatars
- **Modifiers** — contracts that sit between modules and avatars to modify behavior (e.g., enforce delays, scope permissions)
- **Guards** — contracts that check transactions before/after execution

**Zodiac-compliant tools built by Gnosis Guild:**
- **[Roles Modifier](https://github.com/gnosisguild/zodiac-modifier-roles)** (130★) — fine-grained, role-based access control for modules. "Smart account toolkit for role-based access control." v2 is a significant rewrite with expanded permission scoping.
- **[Reality Module](https://github.com/gnosisguild/zodiac-module-reality)** (104★) — on-chain execution based on Reality.eth oracle outcomes (e.g., Snapshot votes). Framework-agnostic.
- **[Exit Module](https://zodiac.wiki/documentation/exit-pattern)** — enables members to redeem tokens for proportional share of treasury (like Moloch's rageQuit)
- **[Delay Modifier](https://zodiac.wiki/documentation/delay-modifier)** — enforces time delays between transaction initiation and execution
- **[Bridge Module](https://zodiac.wiki/documentation/bridge-module)** — cross-chain control: address on one chain controls avatar on another via AMB
- **[Governor Module](https://zodiac.wiki/documentation/governor-module)** — plugs OpenZeppelin Governor into a Safe as a module; seamlessly transitions multisig → token-voting DAO
- **[Siphon Module](https://github.com/gnosisguild/zodiac-module-siphon)** — public interface to trigger avatar to withdraw from liquidity positions to service debt
- **[Scope Guard](https://github.com/gnosisguild/zodiac-guard-scope)** (44★) — limits which functions multisig signers can call

**Ecosystem/third-party tools:**
- Connext Module (cross-chain governance via Connext bridge)
- oSnap (UMA × Snapshot — off-chain votes on-chain)
- Kleros Snapshot Module
- Safe Minion (DAOhaus — Moloch DAO managing Safe assets)
- Badger Access Control / SecretDelay (Kolektivo)
- MetaGuard (Cardstack)

**Scale:** $3B+ in transactions processed through Zodiac tools

**Key adopters:** ENS DAO, Balancer, Kolektivo, Regen Network, many others

### Zodiac Wiki (living resource)
[zodiac.wiki](https://www.zodiac.wiki)

Three key sections:
1. **Documentation** — technical reference for all modules
2. **Patterns** — co-developed pattern language for organizational problems (inspired by Christopher Alexander's *A Pattern Language*)
3. **Library** — collectively curated reading list on decentralized governance:
   - Christopher Alexander et al., *A Pattern Language* (Oxford UP, 1977)
   - Gareth Morgan, *Images of Organization* (Sage, 1986)
   - Ivan Illich, *Tools for Conviviality* (Harper & Row, 1973)
   - Elinor Ostrom & Charlotte Hess (eds.), *Understanding Knowledge as a Commons* (MIT Press, 2007)
   - David Graeber & David Wengrow, *The Dawn of Everything* (Allen Lane, 2021)
   - Jean Lave & Etienne Wenger, *Situated Learning* (Cambridge UP, 1991)
   - Frederic Laloux, *Reinventing Organizations* (Nelson Parker, 2014)
   - David Ehrlichman, *Impact Networks* (Penguin, 2021)
   - Marshall McLuhan, *Understanding Media* (MIT Press, 1964)
4. **Stories** — archive of inactive, failed, deceased crypto projects with lessons extracted; "lessons distilled here may later be shaped into patterns"

### Enclave Protocol (2024–present)
[docs.enclave.gg](https://docs.enclave.gg) | [GitHub](https://github.com/gnosisguild/enclave) (46★)

**What:** Open-source protocol for Collaborative Confidential Compute (Encrypted Execution Environments / E3). Combines:
- **FHE (Fully Homomorphic Encryption)** — compute on encrypted data without decrypting
- **ZKPs (Zero Knowledge Proofs)** — prove computation happened correctly without revealing inputs
- **MPC (Multi-Party Computation)** — distributed key management via Ciphernode Registry

**Why it matters:** Rather than relying on trusted hardware (Intel SGX, etc.) for confidential compute, Enclave achieves privacy and integrity guarantees purely through cryptography and economics. 

**Key component:** CRISP — a reference implementation showing a working application on top of Enclave (see [docs](https://docs.enclave.gg/CRISP/introduction))

**Rust + TypeScript + Noir circuits** codebase. Community: [Telegram group](https://t.me/+raYAZgrwgOw2ODJh)

## Events & Programmes

- **[Discord](https://discord.gnosisguild.org)** — active developer and DAO operator community
- **[Mirror Blog](http://gnosisguild.mirror.xyz/)** — essays and protocol updates
- No formal fellowships or residencies; engagement is through contributing to open-source repos or adopting Zodiac/Enclave in DAO operations

## Intellectual DNA & Lineage

Gnosis Guild's intellectual lineage is unusually rich for a crypto project:
- **Christopher Alexander** → pattern language for governance (directly referenced in Zodiac Wiki; the "patterns" section is explicitly Alexander-inspired)
- **Ivan Illich** (*Tools for Conviviality*) → tools that empower individuals vs. tools that control them; the organizational philosophy of "convivial tools"
- **Elinor Ostrom** → governance of commons; distributed self-governance without state or market
- **David Graeber** (*The Dawn of Everything*) → questioning received narratives about organizational hierarchy; alternative histories of human coordination
- **Etienne Wenger** (*Situated Learning*) → communities of practice; legitimate peripheral participation
- **Marshall McLuhan** → media as extension of man; Kei Kreutler's epigraph on McLuhan anchors the broader worldview

## Connected Communities

- [[Kei Kreutler]] — Co-creator; now at Inner Library + Other Internet + Summer of Protocols
- [[Summer of Protocols]] — Kei Kreutler was SoP23 core researcher; Gnosis Guild connected to protocol studies field
- [[Other Internet Research Institute]] — Kei Kreutler is contributor; overlap on internet-native institutions and governance research
- [[Regen Foundation]] — Kei on board; Regen Network uses Zodiac tools
- [[Commons Stack]] — ecosystem partner; both working on DAO commons infrastructure
- [[BlockScience]] — ecosystem collaborator; complex systems approach to governance design
- [Safe (formerly Gnosis Safe)](https://safe.global/) — primary avatar implementation; Zodiac built around Safe as core infrastructure
- [Economic Space Agency (ECSA)](https://economicspace.agency/) — adjacent work on postcapitalist economic protocol design

## For Amber

**Why interesting for Amber:**

1. **🤝 Cooperation — Pattern language for governance:** The Zodiac pattern language project is directly relevant to Amber's interest in more-than-human design and composable systems. Alexander's pattern language applied to organizational governance is a powerful method — could inspire similar approaches in XR/agent design.

2. **💡 Career inspiration — Technical infrastructure with philosophical grounding:** Gnosis Guild is a model for how to build genuinely used technical infrastructure (billions in transactions) while maintaining a serious intellectual framework (Illich, Ostrom, Graeber). This bridges Amber's technical and philosophical orientations.

3. **🔧 Professional inspiration — Composable design philosophy:** The Avatar/Module/Modifier/Guard architecture is a masterclass in separation of concerns applied to governance. The principle — decouple the "account" from its "authorization logic" — is analogous to principles in agent design (decoupling perception/action/deliberation). Transferable pattern.

4. **🌍 Areas to know — FHE/privacy-preserving computation:** Enclave's pivot to FHE + MPC for encrypted execution environments is directly relevant to Amber's interest in trustworthy agentic systems. Private computation without hardware trust is a frontier that will matter enormously for decentralized AI. Watch Enclave.

5. **🔮 Future involvement — Zodiac Wiki patterns contribution:** The Zodiac Wiki pattern language is explicitly a collective project — contributors can add patterns via PR. Amber could contribute patterns drawn from XR/mixed reality organizational design, or from the more-than-human design perspective.

6. **📚 Learning from their path:** Gnosis Guild built deeply used public goods infrastructure while maintaining intellectual seriousness. They avoided becoming a corporate product while achieving massive adoption. The "public goods" framing (all tools are open-source, framework-agnostic, free) is a deliberate strategic choice with institutional implications worth studying.

7. **Engagement paths:**
   - Follow Enclave development on GitHub; track FHE applications in governance
   - Read [Zodiac Wiki patterns](https://zodiac.wiki/patterns) — the pattern language for organizations is immediately useful
   - Read Kei Kreutler's essays (especially "A Prehistory of DAOs" — connects to Amber's machine behavior / agent society research)
   - Through [[Kei Kreutler]] / [[Summer of Protocols]] Memory Research Group — natural connection point
   - Watch for Kei's forthcoming book *Artificial Memory*

**Who should Amber know:** [[Kei Kreutler]] (already in graph) is the key connection. Auryn Macmillan (technical co-founder) is also worth knowing if Amber goes deeper into decentralized governance infrastructure.

**Who might like Amber's work:** Kei Kreutler's interest in memory, protocols, and AI is directly aligned with Amber's work. The Zodiac community broadly — DAO operators, governance designers — would find Amber's work on agent governance and decentralized AI immediately relevant.

## Why Interesting

Gnosis Guild sits at an unusual intersection: **technically serious infrastructure builders who are also philosophically serious**. Their library (Illich, Ostrom, Alexander, Graeber, McLuhan) is not decoration — it directly shapes the architecture of their tools. The Zodiac "pattern language" for governance, the "conviviality" framing for tool design, the commons orientation — these are coherent and intentional.

The pivot to Enclave (FHE/MPC) signals an important trajectory: from composable governance (who decides?) to private computation (what can be known?). This is the right direction for trustworthy decentralized AI — privacy-preserving computation is table stakes for any serious agentic system that handles sensitive data.

Gnosis Guild connects to Amber's research through:
- **Agentive commoning** — composable governance infrastructure is the technical substrate for agentive commons
- **Decentralized AI / trustworthy agentic web** — Enclave's FHE work directly relevant
- **Protocol studies** — organizational protocols as a design space; connection to [[Summer of Protocols]] network
- **More-than-human design** — governance systems that accommodate non-human agents (what does a DAO membership for an AI look like?)

## 📋 Update Log
| Date | Researcher | Action |
|------|-----------|--------|
| 2026-02-26 | Biber (agent) | Created stub note from Kei Kreutler research. Technical infrastructure with significant real-world adoption. |
| 2026-03-01 | Biber (subagent) | Full deep research. Comprehensive rewrite. Added: Enclave pivot, Zodiac architecture details, full tool list, intellectual lineage (Illich/Ostrom/Alexander/Graeber), Zodiac Wiki library, Auryn Macmillan as key person, connected communities, full For Amber section. |
