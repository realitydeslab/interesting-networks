# Venue Graph 🕸️

An Obsidian-compatible knowledge graph of the interestingness network.

## Structure

```
interesting-networks/
├── people/            # One note per person
├── communities/       # One note per community/network
├── venues/            # One note per venue/conference
├── topics/            # One note per intellectual topic/thread
├── cfps/              # One note per active call
├── logs/              # Daily scout logs with reflections
├── research-taste.md  # Navigator — what's interesting to Amber
├── finding-strategy.md # How we discover things + what works
└── README.md          # This file
```

## Conventions

- **Links:** Use `[[Name]]` to connect nodes. Obsidian will build the graph.
- **Tags:** Use tags for cross-cutting themes:
  - `#more-than-human` `#critical-computing` `#machine-behavior` `#speculative-design`
  - `#alife` `#embodied` `#participatory` `#computational-creativity`
  - `#art-science` `#feminist` `#posthuman` `#climate`
- **Ratings:** ⭐⭐⭐ / ⭐⭐ / ⭐ in frontmatter — rate EVERYTHING (people, topics, venues, communities)
- **Frontmatter:** YAML for structured data, body for free-form notes
- **Dates:** ISO format (2026-02-26)

## Rating Guide
Everything gets rated in frontmatter (`rating: ⭐⭐⭐`):

**People:**
- ⭐⭐⭐ = essential node, Amber's direct inspiration, or bridges multiple key communities
- ⭐⭐ = very interesting, strong work, worth following actively
- ⭐ = worth watching, might become more central

**Topics:**
- ⭐⭐⭐ = edge of chaos, fast-evolving, core to Amber's taste
- ⭐⭐ = important and relevant, but more established
- ⭐ = adjacent, worth knowing about

**Venues/Communities:**
- ⭐⭐⭐ = must-attend / essential community, perfect fit for Amber
- ⭐⭐ = very relevant, strong overlap with interests
- ⭐ = worth tracking, occasionally interesting

Ratings can change over time. Amber's reactions are the strongest signal for upgrades.

## People Note Template
Every person note should include (when known):
- **Domains** — what they work on
- **Key Books/Papers** — their essential works, linked
- **Key Communities** — labs, networks, institutions they belong to
- **Key Venues** — where they present/publish
- **Key Relationships** — co-authors, advisors, students, collaborators (use [[links]])
- **Why Interesting** — what makes them worth following

## Topic Note Template
Every topic note should include (when known):
- **Key People** — who's driving this area
- **Key Venues** — where to present/attend
- **Key Communities** — networks, labs, institutions
- **Fellowships & Programmes** — what Amber can APPLY for (residencies, fellowships, grants, programmes)
- **Key Texts** — essential reading
- **Open Questions** — what's unresolved
- **Adjacent Topics** — links to related areas

## How It Grows

Every node is an entry point. Follow any thread:
- A **person** → links to communities, venues, other people
- A **community** → links to people, venues
- A **venue** → links to people (PC/speakers), communities, CFPs
- A **CFP** → links to venue, relevant people, topics

The daily scout expands the graph. Amber's reactions sharpen it.
