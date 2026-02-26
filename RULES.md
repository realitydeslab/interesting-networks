# RULES — interesting-networks

All rules for maintaining this repo. Read this first. Follow strictly. No exceptions.

---

## 1. Purpose
Grow the interestingness network: **people** (where interestingness comes from), **communities** (their networks), **venues** (where Amber can participate), **topics** (intellectual threads), **CFPs** (actions Amber can take now).

Every node is an entry point. Follow any thread and the whole graph reveals itself.

## 2. Folder Structure
```
interesting-networks/
├── people/            # One .md per person
├── communities/       # One .md per community/network/institution
├── venues/            # One .md per conference/festival/venue
├── topics/            # One .md per intellectual topic/thread
├── cfps/              # One .md per active call (CFP, residency, fellowship)
├── logs/              # Daily scout logs with reflections
├── RULES.md           # THIS FILE — all rules
├── STYLE-GUIDE.md     # Note templates and formatting rules
├── DEEP-RESEARCH-PROTOCOL.md  # How to deep-research one person
├── finding-strategy.md # Discovery strategies and what works
├── research-taste.md  # Amber's taste profile — the navigator
└── README.md          # Overview
```

## 3. Linking Rules
- Use `[[Name]]` for all internal links between notes
- Use `[text](url)` for all external links — **every book, paper, community, award, fellowship, venue MUST have a clickable URL**
- No naked references. If you mention something, link it.

## 4. Rating Rules
Everything gets rated in frontmatter: `rating: ⭐⭐⭐` / `⭐⭐` / `⭐`

**People:**
- ⭐⭐⭐ = essential node, Amber's direct inspiration, bridges multiple key communities
- ⭐⭐ = very interesting, strong work, worth following actively
- ⭐ = worth watching, might become more central

**Topics:**
- ⭐⭐⭐ = edge of chaos, fast-evolving, core to Amber's taste
- ⭐⭐ = important, more established
- ⭐ = adjacent, worth knowing

**Venues/Communities:**
- ⭐⭐⭐ = must-attend / essential, perfect fit for Amber
- ⭐⭐ = very relevant, strong overlap
- ⭐ = worth tracking

Ratings upgrade when Amber reacts positively. Amber's signals are the strongest input.

## 5. Depth Rules
**One person done properly > 10 people done superficially.**

See `people/Wendi Yan.md` as the gold standard.

### ⭐⭐⭐ people (60-90 min research):
- Full background (education, origin, trajectory, WHY they do what they do)
- ALL key works with descriptions and links
- ALL awards & fellowships with URLs and context
- ALL exhibitions/events/talks with dates, venues, cities
- ALL collaborators identified — for each: brief assessment, interesting enough for own note?
- ALL communities/fellowships researched — create community notes for interesting ones
- Venue circuit analysis — what circuits do they move in? Why those small venues?
- Cohort-mates identified (who else got the same fellowship/award?)
- "Why Interesting" connects to research-taste.md

### ⭐⭐ people (30-45 min):
- Key works, key venues, key relationships
- Important awards/fellowships with URLs
- Don't need every exhibition but cover the important ones

### ⭐ people (15-20 min):
- Domains, why interesting, key connections
- Brief note is fine

## 6. Research Protocol
Follow `DEEP-RESEARCH-PROTOCOL.md` for every person. Seven phases:
1. Full website scrape
2. Collaborator search (DON'T SKIP — this is where most research fails)
3. Community/fellowship deep-dive
4. Venue circuit analysis
5. Awards & recognition
6. Writing & ideas
7. Assembly & connection

**Common mistakes to avoid:**
- Skipping collaborators (every project has them — FIND THEM)
- Not clicking through communities (don't just write "Eyebeam residency" — research Eyebeam, get URL, create community note)
- Missing small venues (Trust Berlin, Artifice NYC — these are the strongest signal)
- Ignoring funders (who funds them reveals their network)
- Not searching cohort-mates (every fellowship has a cohort — find them)

## 7. GitHub Issue Rules
### Every ⭐⭐⭐ person MUST have a completeness issue:
- Title: `Deep Research: [Name] — completeness check`
- Labels: `deep-research` + `review`
- Body: checklist from DEEP-RESEARCH-PROTOCOL.md
- Close only when Amber approves

### Every new interesting person discovered goes into the queue:
- Title: `Deep Research Queue: [Name] ⭐⭐`
- Label: `queue`
- Body: who discovered them, why interesting, what research is needed

### Labels:
- `deep-research` — active deep research task
- `queue` — people/communities waiting for research
- `review` — needs Amber's review

## 8. Daily Scout Rules
- Runs daily at 10:00 UTC via cron
- Deep-dive **1-2 people maximum** per session (depth > breadth)
- Pick from the `queue` issues on GitHub
- Follow DEEP-RESEARCH-PROTOCOL.md
- Create GitHub issues for new discoveries
- Check for new CFPs, flag urgent deadlines (⚠️ if < 2 weeks)
- Write reflective log in `logs/YYYY-MM-DD.md`
- Git add, commit, push after every batch
- Post summary in #venue Discord channel

## 9. Topic Note Rules
Every topic note must include (when known):
- **Domain summary** — what it is, scope, history, key theories/results, key challenges
- **Edge of chaos analysis** — is it fast-evolving? Will it be hot in 1-3 years? Why?
- **Sub-topics & trends** (last 3-5 years) — what's active, what's churning
- **Key people** — with [[links]], for each: who, what, why interesting to Amber
- **Key texts** — must-read books and papers (with clickable URLs!)
- **Key venues** — where to present/attend
- **Key communities** — labs, discords, forums, institutions (with URLs!)
- **Fellowships & programmes** — what Amber can APPLY for (URLs required)
- **How can Amber engage?** — CFPs, residencies, online communities, fun events
- **Recent important updates** (timeline, last 3-5 years)
- **For Amber specifically:**
  - Who should Amber know?
  - Who might like Amber's work?
  - Who can Amber collaborate with?
  - What publications should Amber target?
- Adjacent topics (with [[links]])
- Open questions
- Why interesting (connect to research-taste.md)
- `edge_of_chaos: true/false` in frontmatter
- **`last_researched:` date in frontmatter**
- **`research_period:` in frontmatter** (e.g., "monthly", "quarterly") — how often to re-research
- **`next_research:` date in frontmatter** — when to check again

### Topic Depth Levels
- ⭐⭐⭐ topics: comprehensive deep dive (like Wendi Yan for people). 60-90 min research. Gold standard.
- ⭐⭐ topics: solid coverage. 30-45 min.
- ⭐ topics: brief overview. 15-20 min.

### Community Note Rules (for institutions)
Same depth as topics, plus:
- **Every person in the community** assessed for Amber's interests
- **Why interesting to Amber** (collaboration, future work, visit)
- **How can Amber engage** (visiting, guest lectures, research, positions)
- **Openings** (jobs, fellowships, residencies, visiting positions)
- **Key people for Amber:** who to know, who might like Amber, who to learn from, who to collaborate with, who inspires

## 10. CFP Note Rules
- One note per active call in `cfps/`
- Must include: deadline, URL, what it's for, why relevant
- ⚠️ flag if deadline < 2 weeks
- Move to archive section when expired
- Connect to relevant [[topics]], [[venues]], [[people]]

## 11. Log Rules
- One log per day in `logs/YYYY-MM-DD.md`
- Must include: what was found, WHY it's interesting, which strategy led to it
- Reflections on patterns in Amber's taste
- Links to new notes created: `[[Person]]`, `[[Community]]`
- Strategy notes: what worked, what to try differently

## 12. Interestingness Principles
From research-taste.md — the navigator:

### Edge of Chaos
The most interesting areas are:
- **Fast-evolving** — the field is actively reshaping itself
- **Fast-shaping** — new ideas crystallizing, new communities forming
- **Unstable in a productive way** — churning with possibility
Stop researching a thread when it becomes predictable. Double down when it's alive.

### Quality Signals
- Amber explicitly said it's interesting (strongest signal)
- Sits at intersection of 2+ topics
- Weird + rigorous (not just strange, not just academic)
- Creative practice asking philosophical questions
- Bridges non-Western and Western perspectives
- People we already track are involved
- Institutional outsiders doing insider things

### Anti-patterns
- Pure engineering with no critical lens
- "AI for X" without questioning whether X should be AI'd
- Industry showcase disguised as research
- Mega-conferences that are too diffuse
- Predictable — you can guess what they'll say

## 13. Git Rules
- Commit after every meaningful batch of changes
- Push immediately after commit
- Commit messages should describe what was added/changed
- The daily scout must always push before finishing

## 14. Privacy Rules
- Repo is PRIVATE
- Don't include personal contact info (private emails, phone numbers)
- Public professional info is fine (institutional email, public social handles)
- Don't include Amber's personal information

## 15. Re-Research Schedule
Topics and communities go stale. Each note must track when it was last researched and when to check again.

**Frontmatter fields:**
```yaml
last_researched: 2026-02-26
research_period: monthly
next_research: 2026-03-26
```

**Suggested periods:**
- `edge_of_chaos: true` topics → **monthly** (fast-evolving)
- Established topics → **quarterly**
- Active communities → **monthly**
- Stable communities → **quarterly**
- People notes → **update when new work appears** (scout checks social media daily)

The daily scout should check `next_research` dates and flag topics/communities due for refresh.

## 16. Updating Rules
- When Amber says something is interesting → update research-taste.md + upgrade ratings
- When Amber says something is boring → note in research-taste.md anti-patterns
- When a strategy works well → document in finding-strategy.md
- When you make a mistake → document in DEEP-RESEARCH-PROTOCOL.md common mistakes
- **When you add a new rule → add it to this file**

---

*This file is the single source of truth. If it's not written here, it's not a rule.*
*Last updated: 2026-02-26*
