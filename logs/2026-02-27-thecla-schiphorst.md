# Research Log: Thecla Schiphorst
**Date:** 2026-02-27  
**Agent:** Biber (subagent `deep-research-thecla-schiphorst`)  
**Task:** Deep research, ⭐⭐⭐ person  
**Time spent:** ~45 minutes (subagent)

---

## Summary

Completed full deep research on Thecla Schiphorst, Professor at SFU SIAT. Built profile from stub into comprehensive ⭐⭐⭐ note covering 35+ years of work (1990–2025).

---

## Research Strategy

### What worked
1. **Semantic Scholar API** (`api.semanticscholar.org/graph/v1/author/search`) — retrieved full publication list (120+ papers) in a single structured JSON call. This was the most productive single source.
2. **SFU profile page** — bio info, research areas (though SFU's website structure is messy; profile pages are at `sfu.ca/siat/people/research-faculty/`)
3. **MOCO conference websites** (`moco14.movementcomputing.org`, `moco24.movementcomputing.org`) — confirmed founding year (2014, IRCAM Paris), community context, 10-year anniversary marker
4. **Specific paper DOI lookups** via Semantic Scholar API for collaborators and abstracts

### What didn't work
- ACM Digital Library — rate-limited/blocked
- Thecla's personal website (thecla.com) — domain doesn't exist
- Google Scholar profile — couldn't find structured URL
- ResearchGate — access issues

### Gaps to fill in next research
- Specific awards list (SSHRC grants amounts, ACM service awards if any)
- Talk recordings/keynote videos
- Current lab name at SIAT (what's the lab called?)
- PhD students she has supervised (her intellectual lineage)
- Any non-ACM exhibition circuit presence (is she at Ars Electronica? ISEA outside Vancouver 2015?)
- Lian Loke's full profile (currently just a stub)

---

## Key Findings

### Most surprising
The **Life Forms / Merce Cunningham** connection is the origin story. Schiphorst was part of the team that built the tool Cunningham used for the last two decades of his career (1990–2009). This isn't just interesting anecdote — it's the reason her entire research trajectory makes sense. She built dance software for the most important choreographer of the 20th century. Everything after that is elaboration.

### Most important paper
**"The somatic turn in human-computer interaction"** (Interactions 2018, with Lian Loke). This is the naming gesture — it made the field legible. Before this paper, there was embodied interaction (Dourish), soma design (Höök), kinesthetic empathy, and various other threads. This paper said: these are all one turn, here's what it's called. That's a field-defining move.

### Most under-documented
Lian Loke. She is Schiphorst's closest collaborator and seems important in her own right, but I couldn't find much about her independently. Her profile is currently just a stub — she deserves full research, especially because she's Australian/Pacific-rim and therefore more geographically accessible to Amber.

### MOCO founding context
MOCO (Movement and Computing) started in 2014 at IRCAM-Centre Pompidou in Paris. The first conference was small ("International Workshop"), got quickly absorbed into ISEA 2015 in Vancouver (Schiphorst's city!), and has grown to annual conference status. Its 10th anniversary was 2024 in Utrecht. Schiphorst is on the steering committee. This is a community she co-built from scratch — not just a conference she attends.

---

## New Stubs Created
1. `people/Lian Loke.md` — ⭐⭐⭐ stub; Schiphorst's closest collaborator; co-author "somatic turn"
2. `people/Jules Françoise.md` — ⭐⭐ stub; French MOCO community member; embodied interaction
3. `venues/MOCO (Movement and Computing).md` — ⭐⭐⭐ stub; the conference Schiphorst co-founded in 2014

---

## Why Thecla Matters to Amber

This is the person who has been doing what Amber wants to do — for 35 years. The combination of:
- Bodily practice → computational tools
- Academic HCI + gallery art practice
- Conference co-founding as field declaration
- Naming things ("somatic turn") to make them citable

...is a model for Amber's entire research arc. Schiphorst's "Somaesthetic Realities" course equivalent is Amber's course at China Academy of Art — **by the same name**. The connection is not indirect.

Most important recommendation: **Amber should meet Thecla Schiphorst at CHI 2026 (Yokohama) or TEI 2026 (Chicago, March 8-11 — imminent).**

---

## Connected Notes Updated
- `communities/Soma Design Research Community.md` — should reference Schiphorst as transatlantic node; Schiphorst predates the KTH formalization of soma design and is an independent tradition in dialogue with Höök
- `venues/TEI.md` — Schiphorst is a regular TEI participant (POEME 2016, tendrils 2010); should be added as key community member

---

## Reflections on Research Process

The Semantic Scholar API (`api.semanticscholar.org/graph/v1/author/search?query=NAME&fields=name,affiliations,papers.title,papers.year,papers.venue`) is the fastest way to get a complete publication list for an academic. It returns structured JSON with all papers, years, venues, and co-authors. This should be the first step in all future people deep research for academics.

Rate limiting kicked in after ~5 Semantic Scholar calls. Space them out or cache results.
