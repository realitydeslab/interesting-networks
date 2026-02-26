# Venue Graph 🕸️

An Obsidian-compatible knowledge graph of the interestingness network.

## Structure

```
venue-graph/
├── people/          # One note per person
├── communities/     # One note per community/network
├── venues/          # One note per venue/conference
├── cfps/            # One note per active call
├── research-taste.md  # Navigator — what's interesting to Amber
└── README.md        # This file
```

## Conventions

- **Links:** Use `[[Name]]` to connect nodes. Obsidian will build the graph.
- **Tags:** Use tags for cross-cutting themes:
  - `#more-than-human` `#critical-computing` `#machine-behavior` `#speculative-design`
  - `#alife` `#embodied` `#participatory` `#computational-creativity`
  - `#art-science` `#feminist` `#posthuman` `#climate`
- **Ratings:** ⭐⭐⭐ / ⭐⭐ / ⭐ in frontmatter
- **Frontmatter:** YAML for structured data, body for free-form notes
- **Dates:** ISO format (2026-02-26)

## How It Grows

Every node is an entry point. Follow any thread:
- A **person** → links to communities, venues, other people
- A **community** → links to people, venues
- A **venue** → links to people (PC/speakers), communities, CFPs
- A **CFP** → links to venue, relevant people, topics

The daily scout expands the graph. Amber's reactions sharpen it.
