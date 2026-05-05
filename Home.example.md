---
title: Home
kind: template
---

# Grimoire — Home (template)

This file is the public template for `Home.md`. On a fresh fork, copy it:

```bash
cp Home.example.md Home.md
```

`Home.md` is gitignored so your personal landing page (maintained by `inscribe` and `bind`) stays local.

---

# Grimoire

A book of instructions for summoning and directing entities. Two layers, one inbox, six operations.

- **[Scrolls](scrolls/index.md)** — active research wiki (concepts, entities, sources, synthesis)
- **[Shelves](shelves/wiki/index.md)** — library catalog (books, films, music)

Material arrives in `desk/` → `inscribe` routes it → `bind` reconciles periodically. Cross-layer links go both ways: scrolls concepts cite shelves books; shelves clusters give concepts their library footprint.

## What's new this cycle

**Last bind:** _(bind populates — date + one-sentence summary)_

**Last divine:** _(divine populates — date + wikilinked title + brief one-sentence parenthetical)_

**Recently inscribed sources** (last 8, newest first):

_(inscribe populates — newest at top, capped at 8)_

**Concepts and entities updated this cycle:**

_(bind populates — 5–8 concept/entity pages seeing the most recent updates)_

## Cross-layer clusters

Scrolls pages that meet a dense shelves neighborhood.

_(bind populates — pattern: `[[scrolls-page]] ↔ shelves neighborhood (N titles)`)_

## Open synthesis candidates

_(bind populates from the latest bind's synthesis-candidates section)_

## Open work

_(bind populates — re-clips pending, illuminate pending, catalog-triage worksheet, etc.)_

## Operations quick reference

| Operation | Purpose |
|-----------|---------|
| `inscribe` | Route items from `desk/` — creates source pages, updates catalog, promotes assets |
| `bind` | Periodic deep pass — updates concepts/entities, promotes hubs, batched shelves cross-check |
| `consult` | Answer a substantive question against the wiki |
| `divine` | Draft a synthesis essay on a flagged candidate or on request |
| `audit` | Integrity check — contradictions, orphans, stale claims |
| `illuminate` | Localize remote images into `raw/assets/` and rewrite references |

See `docs/operations.md` for the full cheat sheet.
