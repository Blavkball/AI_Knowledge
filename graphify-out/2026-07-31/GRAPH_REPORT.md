# Graph Report - .  (2026-07-31)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 10 nodes · 9 edges · 3 communities (2 shown, 1 thin omitted)
- Extraction: 0% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `87469a35`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Human Readable Name
- Human Readable Name
- Human Readable Name

## God Nodes (most connected - your core abstractions)
1. `Human Readable Name` - 5 edges
2. `Human Readable Name` - 2 edges
3. `Human Readable Name` - 1 edges
4. `Human Readable Name` - 1 edges
5. `Human Readable Name` - 1 edges
6. `Human Readable Name` - 1 edges
7. `Human Readable Name` - 1 edges
8. `Human Readable Name` - 1 edges
9. `Human Readable Name` - 1 edges

## Surprising Connections (you probably didn't know these)
- `Human Readable Name` --implements|references|cites|conceptually_related_to|shares_data_with|semantically_similar_to--> `Human Readable Name`  [EXTRACTED|INFERRED|AMBIGUOUS]
  src/auth/session.py → omniforces.py
- `Human Readable Name` --implements|references|cites|conceptually_related_to|shares_data_with|semantically_similar_to--> `Human Readable Name`  [EXTRACTED|INFERRED|AMBIGUOUS]
  src/auth/employee.py → omniforces.py
- `Human Readable Name` --implements|references|cites|conceptually_related_to|shares_data_with|semantically_similar_to--> `Human Readable Name`  [EXTRACTED|INFERRED|AMBIGUOUS]
  src/auth/task.py → omniforces.py
- `Human Readable Name` --implements|references|cites|conceptually_related_to|shares_data_with|semantically_similar_to--> `Human Readable Name`  [EXTRACTED|INFERRED|AMBIGUOUS]
  src/architecture.py → omniforces.py
- `Human Readable Name` --references|cites|conceptually_related_to|shares_data_with|semantically_similar_to--> `Human Readable Name`  [EXTRACTED|INFERRED|AMBIGUOUS]
  GLOBAL_KNOWLEDGE.md → STANDARDS.md

## Import Cycles
- None detected.

## Communities (3 total, 1 thin omitted)

### Community 0 - "Human Readable Name"
Cohesion: 0.40
Nodes (5): Human Readable Name, Human Readable Name, Human Readable Name, Human Readable Name, Human Readable Name

### Community 1 - "Human Readable Name"
Cohesion: 0.67
Nodes (3): Human Readable Name, Human Readable Name, Human Readable Name

## Knowledge Gaps
- **7 isolated node(s):** `Human Readable Name`, `Human Readable Name`, `Human Readable Name`, `Human Readable Name`, `Human Readable Name` (+2 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Human Readable Name` connect `Human Readable Name` to `Human Readable Name`?**
  _High betweenness centrality (0.722) - this node is a cross-community bridge._
- **Why does `Human Readable Name` connect `Human Readable Name` to `Human Readable Name`?**
  _High betweenness centrality (0.222) - this node is a cross-community bridge._
- **What connects `Human Readable Name`, `Human Readable Name`, `Human Readable Name` to the rest of the system?**
  _7 weakly-connected nodes found - possible documentation gaps or missing edges._