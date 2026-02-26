# RULES — interesting-networks

**The professional editorial manual for this knowledge graph.**
Any agent (human or AI) editing this repo MUST read and follow these rules.

---

## 0. Philosophy
This is a **living knowledge graph** mapping the interestingness network around Amber's research interests. It is maintained like a professional wiki: structured, sourced, timestamped, and collaborative.

**Core principles:**
- **Depth over breadth** — one note done properly > 10 done superficially
- **Edge of chaos** — prioritize fast-evolving, fast-shaping areas
- **Everything linked** — every reference clickable, every connection explicit
- **Everything timestamped** — every note tracks when it was researched and when to revisit
- **Amber-centered** — every note explains why it matters to Amber specifically

---

## 1. Folder Structure
```
interesting-networks/
├── people/            # One .md per person
├── communities/       # One .md per community/network/institution
├── venues/            # One .md per conference/festival/venue
├── topics/            # One .md per intellectual topic/thread
├── cfps/              # One .md per active call
├── logs/              # Daily scout logs with reflections
├── RULES.md           # THIS FILE — editorial manual
├── STYLE-GUIDE.md     # Note templates and formatting
├── DEEP-RESEARCH-PROTOCOL.md  # How to deep-research one person
├── finding-strategy.md # Discovery strategies
├── research-taste.md  # Amber's taste profile — the navigator
└── README.md          # Overview
```

---

## 2. Universal Frontmatter (ALL notes)
Every note MUST have these fields:
```yaml
---
rating: ⭐⭐⭐        # ⭐⭐⭐ / ⭐⭐ / ⭐
added: 2026-02-26      # date first created
last_researched: 2026-02-26  # date of last deep research
revisit_weeks: 4       # suggested weeks until next research
next_research: 2026-03-26    # computed from above
tags: [tag1, tag2]     # from tag vocabulary
---
```

### Revisit Period Guide
| Type | Condition | Revisit |
|------|-----------|---------|
| Topic | `edge_of_chaos: true` | 2-4 weeks |
| Topic | Established | 8-12 weeks |
| Person | ⭐⭐⭐ | 4 weeks |
| Person | ⭐⭐ | 8 weeks |
| Person | ⭐ | 12 weeks |
| Community | Active, fast-moving | 4 weeks |
| Community | Stable | 8-12 weeks |
| Venue | During CFP season | 2 weeks |
| Venue | Off-season | 12 weeks |
| CFP | Active | weekly until deadline |

---

## 3. Universal Note Structure
Every note MUST have these sections in this order:

### Front Matter (YAML)
### Title (H1)
### ⚡ Recent Updates (H2) — ALWAYS AT THE TOP
What's new since last research. Bullet list, most recent first, dated.
```markdown
## ⚡ Recent Updates
- **2026-02-26:** Initial deep research. Created note with full profile.
- **2026-03-15:** Added new exhibition at X. Updated venues.
```
If first research, write: `- **2026-02-26:** Initial deep research.`

### [Main content sections — varies by note type, see below]

### 📋 Update Log (H2) — ALWAYS AT THE BOTTOM
Full research history. Who researched, when, what changed.
```markdown
## 📋 Update Log
| Date | Researcher | Action |
|------|-----------|--------|
| 2026-02-26 | Biber (agent) | Initial deep research. Created note. |
| 2026-03-15 | Scout (cron) | Added 2 new exhibitions, updated venues. |
```

---

## 4. People Notes
Required sections in order:
```
---
[frontmatter with rating, added, last_researched, revisit_weeks, next_research, tags]
affiliation:
website:
social:
  x: "@handle"
  linkedin:
born:        # optional
education:   # optional
based:       # optional
---

# Name

## ⚡ Recent Updates

[One-line description]

## Background
Education, origin, trajectory. The WHY behind their work.

## Domains
What they work on.

## Key Works
[*Title*](url) (year) — description. ALL with clickable links.

## Awards & Fellowships
ALL of them with URLs. Small ones matter.

## Exhibitions / Events / Talks
ALL of them. Date, venue, city.

## Key Communities
[[links]] with URLs. Role in each.

## Key Relationships & Collaborators
[[links]]. For each: relationship type, interesting enough for own note?

## Venue Circuit Analysis (⭐⭐⭐ only)
What circuits do they move in? Why those venues?

## Research Taste Analysis (⭐⭐⭐ only)
Analyze HOW this person builds their research, not just WHAT they research.
This section should let Amber quickly understand the meta-strategy she can learn from.

Required sub-sections:
### The Formula
Identify the repeating pattern. Examples:
- **Seed paper strategy**: write conceptual framework → spend years filling empirical slots
- **Research franchise model**: each paper creates demand for the next
- **Framework multiplication**: take two established ideas from different fields → multiply into new concept
- **Field declaration**: zoom out from specific results → declare an entire field exists

### Key Moves (chronological)
List the 3-5 career-defining moves with dates:
1. What they did
2. WHY it worked (timing, framing, positioning)
3. What it enabled next

### What Amber Can Learn
Not "collaboration potential" — what STRATEGY or PATTERN can Amber extract and adapt?
Be specific: "Write a 'seed paper' that defines agent ethology's conceptual territory before doing empirical work"

## For Amber
- **Why interesting:** connection to Amber's taste
- **Collaboration potential:** what could they work on together?
- **Engagement paths:** specific ways to connect (events, people, submissions)

## Why Interesting
Connect to research-taste.md.

## 📋 Update Log
```

### Depth by Rating
- **⭐⭐⭐** (60-90 min): ALL sections filled. Every exhibition, award, collaborator. Note should REPLACE their website.
- **⭐⭐** (30-45 min): Key sections filled. Major works, venues, relationships.
- **⭐** (15-20 min): Brief. Domains, why interesting, key connections.

---

## 5. Topic Notes
Required sections in order:
```
---
[frontmatter]
edge_of_chaos: true/false
---

# Topic Name

## ⚡ Recent Updates

[One-paragraph description]

## Domain Summary
What it is, scope, history, key theories, key results.

## Edge of Chaos Analysis
Is it fast-evolving? Will it be hot in 1-3 years? What's driving it?

## Sub-topics & Trends (last 3-5 years)
What's active, what's churning.

## Key People
[[links]], for each: who, what, why interesting.

## Must-Read List
### Books
- [*Title*](url) (Author, year) — why essential
### Papers
- [Title](arxiv/doi) (Author, year) — why essential
### Journals
Where to publish.

## Key Venues
Where to present.

## Key Communities & Institutions
Labs, discords, forums. ALL with URLs.

## Fellowships & Programmes
What Amber can APPLY for. URLs required.

## How Can Amber Engage?
CFPs, residencies, online communities, events.

## For Amber
- **Who should Amber know?**
- **Who might like Amber's work?**
- **Who can Amber collaborate with?**
- **What publications should Amber target?**

## Recent Important Updates (Timeline)
Chronological, last 3-5 years. Key events, papers, shifts.

## Adjacent Topics
[[links]]

## Open Questions

## Why Interesting

## 📋 Update Log
```

---

## 6. Community / Institution Notes
Required sections in order:
```
---
[frontmatter]
url:
---

# Community Name

## ⚡ Recent Updates

[Vibe description]

## Mission & Objectives
What they do, why they exist.

## Key People
EVERY interesting person. Brief summary each. [[links]] for ⭐⭐+.

## Key Publications & Output
What they produce.

## Key Contributions
What they've given the world.

## Events & Programmes
Regular events, residencies, fellowships. With URLs.

## For Amber
- **Why interesting:** collaboration, future work, visit?
- **How can Amber engage:** visiting, guest lectures, research, positions?
- **Opening opportunities:** jobs, fellowships, residencies, visiting positions
- **Who should Amber know?**
- **Who might like Amber?**
- **Who can Amber learn from?**
- **Who can Amber collaborate with?**
- **Who can inspire Amber?**
- **Key publications to be part of**

## Recent Events That Matter
Events relevant to Amber's interests.

## Connected Institutions
[[links]]

## Why Interesting

## 📋 Update Log
```

---

## 7. Venue Notes
```
---
[frontmatter]
url:
frequency: annual/biennial/one-off
---

# Venue Name

## ⚡ Recent Updates

[Vibe description]

## Key People
Organizers, keynotes, PC.

## Topics

## Next Edition
Date, location, deadlines.

## Recent Editions (keynotes, themes)
Last 2-3 years.

## Fellowships & Programmes

## For Amber
How relevant, what to submit, who to meet.

## Why Interesting

## 📋 Update Log
```

---

## 8. CFP Notes
```
---
[frontmatter]
venue: "[[Venue Name]]"
deadline: 2026-06-01
url:
status: open/closed/expired
urgent: true/false
---

# CFP: Name

## ⚡ Recent Updates

## What
## Deadline
## Why Relevant
## Related

## 📋 Update Log
```

---

## 9. Linking Rules
- `[[Name]]` for all internal links
- `[text](url)` for all external links
- **EVERY book, paper, community, award, fellowship, venue MUST have a clickable URL**
- No naked references. If you mention it, link it.
- Prefer: arXiv > DOI > publisher page > Amazon

---

## 10. Rating Rules
**People:**
- ⭐⭐⭐ = essential node, Amber's inspiration, bridges key communities
- ⭐⭐ = very interesting, worth following actively
- ⭐ = worth watching

**Topics:**
- ⭐⭐⭐ = edge of chaos, core to Amber's taste
- ⭐⭐ = important, more established
- ⭐ = adjacent, worth knowing

**Venues/Communities:**
- ⭐⭐⭐ = must-attend / essential, perfect fit
- ⭐⭐ = very relevant
- ⭐ = worth tracking

Ratings upgrade when Amber reacts positively.

---

## 11. Research Protocol
Follow `DEEP-RESEARCH-PROTOCOL.md`. Seven phases:
1. Full website scrape
2. **Collaborator search** (DON'T SKIP — most common failure)
3. Community/fellowship deep-dive
4. Venue circuit analysis
5. Awards & recognition
6. Writing & ideas
7. Assembly & connection

**Time:** ⭐⭐⭐ = 60-90 min, ⭐⭐ = 30-45 min, ⭐ = 15-20 min

---

## 12. GitHub Issue Rules
### Every ⭐⭐⭐ note MUST have a completeness issue:
- Title: `Deep Research: [Name] — completeness check`
- Labels: `deep-research` + `review`
- Body: checklist
- Close only when Amber approves

### Every new discovery → queue issue:
- Title: `Deep Research Queue: [Name] ⭐⭐`
- Label: `queue`

### Labels:
- `deep-research` — active research task
- `queue` — waiting for research
- `review` — needs Amber's approval

---

## 13. Scout Cron Job (Daily, Lightweight)
Runs daily at 10:00 UTC. The cron does NOT do deep research. It maintains the queue:
1. Scan all notes for `deep_researched: false` → create queue issues if not already queued
2. Scan all notes where `next_research` date has passed → flag for re-research
3. Check for new CFPs, flag urgent deadlines (⚠️ if < 2 weeks)
4. Post queue status summary to #venue

## 13b. Deep Research Execution
- **No daily limit.** Do as much research as tokens allow.
- Monitor token usage. If tokens remain, keep working the queue.
- Priority: ⭐⭐⭐ first → ⭐⭐ → ⭐. Within same rating: Amber's key people → topics → communities → venues.
- Spawn sub-agents for parallel deep research when possible.
- Follow DEEP-RESEARCH-PROTOCOL.md for each note.
- Git add, commit, push after each completed note.
- Write log in `logs/YYYY-MM-DD.md`.

---

## 14. Interestingness Principles
From research-taste.md:

### Edge of Chaos
- **Fast-evolving** — field reshaping itself
- **Fast-shaping** — new ideas crystallizing
- **Unstable productively** — churning with possibility
Stop when predictable. Double down when alive.

### Quality Signals
- Amber said it's interesting (strongest)
- Intersection of 2+ topics
- Weird + rigorous
- Creative practice asking philosophical questions
- Non-Western + Western perspectives bridged
- Institutional outsiders doing insider things

### Anti-patterns
- Pure engineering, no critical lens
- "AI for X" without questioning X
- Industry showcase as research
- Mega-conferences too diffuse
- Predictable

---

## 15. Git Rules
- Commit after every meaningful batch
- Push immediately
- Descriptive commit messages
- Scout must push before finishing

---

## 16. Privacy Rules
- Repo is PRIVATE
- No personal contact info (private emails, phones)
- Public professional info is fine
- No Amber personal info

---

## 17. Tag Vocabulary
Use consistently:
`#more-than-human` `#critical-computing` `#machine-behavior` `#speculative-design` `#alife` `#embodied` `#participatory` `#computational-creativity` `#art-science` `#feminist` `#posthuman` `#climate` `#social-simulation` `#accelerationism` `#cosmotechnics` `#sinofuturism` `#open-endedness` `#active-inference`

---

## 18. Multi-Agent Collaboration Rules
This repo may be edited by multiple agents (main agent, scout cron, research sub-agents). Rules for collaboration:

### Editing Etiquette
- **Read before writing.** Always check existing notes before creating new ones.
- **Don't overwrite.** If a note exists, UPDATE it — don't replace unless doing a full rewrite.
- **Sign your work.** Every change goes in the 📋 Update Log with date and agent name.
- **Incremental commits.** Push after every batch, not at the end. Other agents may be working.
- **Conflict resolution:** If two agents edit the same file, the more comprehensive version wins. Merge, don't discard.

### Communication
- New discoveries → create GitHub queue issue (other agents can pick it up)
- Completed research → update GitHub completeness issue
- Reflections → write in logs/ (other agents can learn from your strategy)

### Quality Standards
- Every note must pass the checklist in DEEP-RESEARCH-PROTOCOL.md before marking complete
- All URLs must be tested (no broken links)
- All [[links]] must point to existing notes (or create the note)
- No orphan notes — everything must link to at least one other node

### Onboarding a New Agent
A new agent joining this project should:
1. Read RULES.md (this file) — the entire editorial manual
2. Read research-taste.md — understand what's interesting to Amber
3. Read DEEP-RESEARCH-PROTOCOL.md — understand research methodology
4. Read finding-strategy.md — understand discovery strategies
5. Read STYLE-GUIDE.md — understand formatting
6. Read `people/Wendi Yan.md` — the gold standard for people notes
7. Check GitHub issues for `queue` items to pick up
8. Start with a ⭐⭐ person to practice before attempting ⭐⭐⭐

---

## 19. Updating This File
- **When you add a new rule → add it here**
- **When a rule doesn't work → update it here with explanation**
- **When Amber gives feedback → encode it as a rule here**
- This file is the single source of truth. If it's not here, it's not a rule.

---

*Last updated: 2026-02-26*
*This is a living document. Update it as the project evolves.*
