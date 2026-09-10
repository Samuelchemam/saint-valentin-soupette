# Graph Report - valentine-question  (2026-09-10)

## Corpus Check
- Corpus is ~1,217 words - fits in a single context window. You may not need a graph.

## Summary
- 15 nodes · 16 edges · 5 communities (4 shown, 1 thin omitted)
- Extraction: 94% EXTRACTED · 6% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.85)
- Token cost: 0 input · 60,669 output

## Community Hubs (Navigation)
- Setup & Mode Toggle
- Anti-Spoiler URL Encoding
- NO Button Dodge Game
- Link Generation & Sharing
- YES Celebration Animation

## God Nodes (most connected - your core abstractions)
1. `Valentine Question Page App` - 5 edges
2. `encode()` - 3 edges
3. `Anti-spoiler URL encoding scheme` - 3 edges
4. `NO button dodge game (nuclear mode)` - 3 edges
5. `Shareable link generation & copy flow` - 3 edges
6. `decode()` - 2 edges
7. `gen() - generate shareable link` - 2 edges
8. `mv() - evade the NO button` - 2 edges
9. `clp() - close 'technical problem' popup` - 2 edges
10. `Valentine mode vs Custom mode toggle` - 2 edges

## Surprising Connections (you probably didn't know these)
- `saint-valentin-soupette (project)` --conceptually_related_to--> `Valentine Question Page App`  [INFERRED]
  README.md → index.html

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Link generation & decoding flow (q/r params)** — index_gen, index_encode, index_decode, index_valentine_question_app [EXTRACTED 1.00]
- **NO-button evasion game mechanic** — index_mv, index_clp, index_win, index_no_button_dodge_game [EXTRACTED 1.00]
- **Setup screen mode toggle feeding generation** — index_sw, index_valentine_mode_vs_custom_mode, index_gen [INFERRED 0.85]

## Communities (5 total, 1 thin omitted)

### Community 0 - "Setup & Mode Toggle"
Cohesion: 0.50
Nodes (4): sw() - switch setup mode, Valentine mode vs Custom mode toggle, Valentine Question Page App, saint-valentin-soupette (project)

### Community 1 - "Anti-Spoiler URL Encoding"
Cohesion: 1.00
Nodes (3): Anti-spoiler URL encoding scheme, decode(), encode()

### Community 2 - "NO Button Dodge Game"
Cohesion: 1.00
Nodes (3): clp() - close 'technical problem' popup, mv() - evade the NO button, NO button dodge game (nuclear mode)

### Community 3 - "Link Generation & Sharing"
Cohesion: 0.67
Nodes (3): cp() - copy link to clipboard, gen() - generate shareable link, Shareable link generation & copy flow

## Knowledge Gaps
- **5 isolated node(s):** `saint-valentin-soupette (project)`, `sw() - switch setup mode`, `cp() - copy link to clipboard`, `win() - handle YES click`, `herts() - spawn floating hearts animation`
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 5 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Valentine Question Page App` connect `Setup & Mode Toggle` to `Anti-Spoiler URL Encoding`, `NO Button Dodge Game`, `Link Generation & Sharing`?**
  _High betweenness centrality (0.549) - this node is a cross-community bridge._
- **Why does `NO button dodge game (nuclear mode)` connect `NO Button Dodge Game` to `Setup & Mode Toggle`?**
  _High betweenness centrality (0.220) - this node is a cross-community bridge._
- **Why does `Shareable link generation & copy flow` connect `Link Generation & Sharing` to `Setup & Mode Toggle`?**
  _High betweenness centrality (0.198) - this node is a cross-community bridge._
- **What connects `saint-valentin-soupette (project)`, `sw() - switch setup mode`, `cp() - copy link to clipboard` to the rest of the system?**
  _5 weakly-connected nodes found - possible documentation gaps or missing edges._