# Deep Research Protocol

## Model Strategy (Cost Efficiency)
- **Sonnet** for data scraping: CV crawling, paper collection, link gathering, factual sections, institutional details
- **Opus** for judgment: interestingness ratings, Amber-relevance analysis, engagement strategy, editorial voice, connection mapping
- In practice: spawn scraping subagents with Sonnet, then do a final Opus pass for ratings + analysis — How to Research One Person

Researching one person properly is a **multi-hour, multi-agent task**. This document defines the steps.

## The Rule
**One person done at Wendi Yan depth > 10 people done superficially.**
See `people/Wendi Yan.md` as the gold standard (11KB, 6 community nodes generated).

---

## Phase 1: Full Website Scrape (~15 min)
- Fetch their homepage, CV/about page, exhibitions page, writing page
- Extract EVERYTHING: every exhibition, talk, publication, award, residency, fellowship
- If the site is JS-heavy, use browser or Exa search to get cached content
- Note: dates, venues, cities, roles (speaker/exhibitor/panelist)

## Phase 2: Collaborator Search (~15 min)
This is where most research fails. **Every project has collaborators. Find them.**
- For each major artwork/project: who are the co-creators?
- Search "[person name] collaboration" / "[project name] team"
- Check exhibition descriptions — group shows list all artists
- Check talk descriptions — panels list all speakers
- Check paper co-authors on Google Scholar
- **For each collaborator: brief assessment — interesting enough for their own note?**

## Phase 3: Community/Fellowship Deep-Dive (~15 min)
For every fellowship, residency, award, programme the person was part of:
- Search for the programme itself: what is it? Who runs it? Who else is in the cohort?
- Get the URL
- If interesting enough → create a community note in `communities/`
- Check: does this community have open calls? → note in `cfps/`

## Phase 4: Venue Circuit Analysis (~10 min)
- Map ALL venues where they've shown/spoken
- Group by geography and type (Asian art-tech / European media art / NYC art-tech / etc.)
- Analyze the pattern: what circuits do they move in?
- Which small/niche venues did they choose? WHY? (small venues are the strongest signal)

## Phase 5: Awards & Recognition (~5 min)
- List ALL awards with links
- Note who else received the same award (other years) — potential interesting people

## Phase 6: Writing & Ideas (~10 min)
- What do they write about? Published where?
- Key ideas/concepts they're developing
- How does their intellectual trajectory connect to our research taste?

## Phase 7: Assembly & Connection (~10 min)
- Write the note following STYLE-GUIDE.md template
- Add [[links]] to all connected nodes (people, communities, venues, topics)
- Create new community/venue notes for anything interesting discovered
- Add new people to a "to research" queue if interesting enough

---

## Checklist (must all be ✅ before committing)
- [ ] Full background (education, origin, trajectory)
- [ ] All key works with descriptions
- [ ] ALL awards & fellowships with URLs
- [ ] ALL exhibitions/events/talks with dates and venues
- [ ] ALL collaborators identified and assessed
- [ ] ALL communities/fellowships researched and linked
- [ ] Venue circuit analysis written
- [ ] "Why Interesting" connects to research-taste.md
- [ ] Every URL is clickable
- [ ] New community notes created for interesting programmes
- [ ] Collaborators flagged for future deep research
- [ ] Log entry written with reflections

---

## Common Mistakes
1. **Skipping collaborators** — Darren Zhu (Wendi Yan's Biotopy co-creator) is a Yale synthetic biologist + Thiel Fellow + Berggruen + Ethereum Foundation. That's a ⭐⭐ at minimum. DON'T MISS THESE.
2. **Not clicking through** — "Eyebeam residency" is not enough. WHAT is Eyebeam? URL? Who else is there?
3. **Missing small venues** — Trust Berlin, Artifice NYC, Last Projects LA. These are the signal. List them all.
4. **Ignoring funders** — Cosmos Ventures, Ethereum Foundation, Steve Jobs Archive — who funds them reveals their network.
5. **Not searching cohort-mates** — SJA Fellowship has a cohort. VH Award has finalists. FIND THEM.

---

## Time Estimate
- ⭐⭐⭐ person: 60-90 minutes
- ⭐⭐ person: 30-45 minutes  
- ⭐ person: 15-20 minutes

---

## GitHub Issue Rules

### When completing a deep research:
1. Create a GitHub issue with the checklist above: `Deep Research: [Name] — completeness check`
2. Label it `deep-research` + `review` (for Amber to check)
3. Check off items as you complete them
4. Close the issue only when Amber approves

### When discovering someone worth researching later:
1. Create a GitHub issue: `Deep Research Queue: [Name] ⭐⭐`
2. Label it `queue`
3. Include: who discovered them, why they're interesting, what research is needed
4. The daily scout picks from the queue

### Labels
- `deep-research` — active deep research task
- `queue` — people/communities waiting for deep research
- `review` — needs Amber's review before closing

### Rule: Every ⭐⭐⭐ person MUST have an issue tracking completeness.
### Rule: Every new interesting person discovered goes into the queue as an issue.
