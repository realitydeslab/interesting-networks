# Style Guide — interesting-networks

Rules for writing notes in this repo. Follow strictly.

---

## General Rules
- Every note gets a **rating** in frontmatter: `rating: ⭐⭐⭐` / `⭐⭐` / `⭐`
- Use `[[Name]]` for internal links between notes
- Use `#tags` in frontmatter YAML array: `tags: [alife, art-science]`
- Dates in ISO format: `2026-02-26`
- Every note has a `added:` date in frontmatter

## Links — Always Clickable
- **Books:** Link to publisher page, Amazon, or Open Library
  - Example: `[*Things We Could Design*](https://mitpress.mit.edu/books/things-we-could-design)`
- **Papers:** Link to arXiv, DOI, or publisher
  - Example: `[Generative Agents](https://arxiv.org/abs/2304.03442)`
  - Prefer arXiv > DOI > publisher paywall
- **Websites:** Always include URL
  - Example: `<https://machinebehavior.science/>`
- **Fellowships/Programmes:** Always include application URL
- **Venues:** Always include main website URL
- **People websites:** Include in frontmatter as `website:`

## People Notes
Required sections (when known):
```markdown
---
rating: ⭐⭐⭐
affiliation: Institution
website: https://...
social:
  x: "@handle"
  linkedin: name
added: 2026-02-26
tags: [tag1, tag2]
---

# Name

One-line description.

## Domains
What they work on.

## Key Books & Papers
- [*Book Title*](https://link) (year) — brief note
- [Paper Title](https://arxiv.org/abs/...) (year) — brief note

## Key Communities
- [[Community Name]] — their role (member, founder, etc.)

## Key Venues
- [[Venue Name]] — how they're involved (speaker, PC, regular)

## Key Relationships
- [[Person]] — relationship (co-author, advisor, student, collaborator)
- [[Person]] — relationship

## Why Interesting
What makes them worth following. Connect to Amber's taste.
```

## Topic Notes
Required sections (when known):
```markdown
---
rating: ⭐⭐⭐
added: 2026-02-26
tags: [tag1, tag2]
edge_of_chaos: true/false
---

# Topic Name

One-paragraph description.

## Key People
- [[Person]] — their contribution

## Key Texts
- [*Book Title*](https://link) (Author, year) — brief note
- [Paper Title](https://doi.org/...) (Author, year) — brief note

## Key Venues
- [[Venue]] — relevance

## Key Communities
- [[Community]] — relevance

## Fellowships & Programmes
- **Name** — brief description. <https://application-link>

## Adjacent Topics
- [[Topic]] — how they connect

## Open Questions
Active/unresolved questions in this area.

## Why Interesting
How this connects to Amber's research taste.
```

## Venue Notes
Required sections:
```markdown
---
url: https://...
rating: ⭐⭐
frequency: annual/biennial/one-off
added: 2026-02-26
tags: [tag1, tag2]
---

# Venue Name

Vibe description.

## Key People
- [[Person]] — role (organizer, keynote, PC)

## Topics
What's covered.

## Next Edition
Date, location, deadlines.

## Fellowships & Programmes
Associated grants, travel awards, etc.

## Why Interesting
Fit with Amber's taste.
```

## Community Notes
Required sections:
```markdown
---
url: https://...
rating: ⭐⭐
added: 2026-02-26
tags: [tag1, tag2]
---

# Community Name

Vibe description.

## Key People
- [[Person]] — role

## Topics
What they work on.

## Events & Programmes
Regular events, fellowships, residencies.

## Why Interesting
```

## CFP Notes
```markdown
---
venue: "[[Venue Name]]"
deadline: 2026-06-01
url: https://...
status: open/closed/expired
urgent: true/false
added: 2026-02-26
tags: [tag1, tag2]
---

# CFP: Name of Call

## What
What they're looking for.

## Deadline
Date (flag ⚠️ if < 2 weeks)

## Why Relevant
How it connects to Amber's interests.

## Related
- [[Topic]], [[Person]], [[Venue]]
```

## Log Notes
```markdown
---
date: 2026-02-26
---

# Scout Log — YYYY-MM-DD

## Discoveries
What was found, with [[links]] to new notes.

## Reflections
Why things are interesting. Patterns noticed.

## Strategy Notes
What worked, what to try next.
```

## Tag Vocabulary
Use these consistently:
- `#more-than-human` `#critical-computing` `#machine-behavior`
- `#speculative-design` `#alife` `#embodied` `#participatory`
- `#computational-creativity` `#art-science` `#feminist`
- `#posthuman` `#climate` `#social-simulation`
- `#accelerationism` `#cosmotechnics`

## Rating Guide
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
