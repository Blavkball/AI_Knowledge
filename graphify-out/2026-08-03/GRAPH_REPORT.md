# Graph Report - E:\AI_Knowledge  (2026-08-03)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 64 nodes · 41 edges · 28 communities (9 shown, 19 thin omitted)
- Extraction: 59% EXTRACTED · 39% INFERRED · 0% AMBIGUOUS · INFERRED: 16 edges (avg confidence: 1.0)
- Token cost: 519 input · 262 output

## Graph Freshness
- Built from commit: `5c1ac9eb`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Standards
- Session Handover
- Development Lifecycle
- AI Knowledge
- Agent Management
- AI Rules
- Human Readable Name
- Coding Standards
- Versioning
- Employees README
- Repository
- Workstation
- Git & Docs
- Employee Definitions
- AI Knowledge
- Repository
- Task Methodology
- BlackBall Repo
- BlackBall
- Engineering Standards
- Future Repositories
- Global Architecture
- Graphify Knowledge Graph
- OmniForces Repository
- AI Knowledge README
- Repo Relationships
- Shared Docs
- Human Readable Name

## God Nodes (most connected - your core abstractions)
1. `KingC Software Standards` - 7 edges
2. `Session Handover 2026-08-01` - 4 edges
3. `Session Handover 2026-08-02` - 4 edges
4. `AgentManager` - 4 edges
5. `AI Knowledge` - 3 edges
6. `Development Lifecycle` - 3 edges
7. `OmniForces` - 2 edges
8. `BlackBall` - 2 edges
9. `AI Workstation` - 2 edges
10. `Human Readable Name` - 2 edges

## Surprising Connections (you probably didn't know these)
- `Session Handover 2026-08-01` ----> `Context Builder`  [INFERRED]
  SESSION_HANDOVER_2026-08-01.md → app/context/context_builder.py
- `Session Handover 2026-08-01` ----> `Graphify Context Integration`  [INFERRED]
  SESSION_HANDOVER_2026-08-01.md → app/context/graphify_context.py
- `Session Handover 2026-08-01` ----> `Knowledge Provider`  [INFERRED]
  SESSION_HANDOVER_2026-08-01.md → app/context/knowledge_provider.py
- `Session Handover 2026-08-01` ----> `Repository Context`  [INFERRED]
  SESSION_HANDOVER_2026-08-01.md → app/context/repository_context.py
- `Session Handover 2026-08-02` ----> `Context Builder`  [INFERRED]
  SESSION_HANDOVER_2026-08-02.md → app/context/context_builder.py

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Human Readable Label** — src_auth_session, employees_ai_supervisor [EXTRACTED 0.75]
- **Engineering Ecosystem** — repositories_ai_knowledge, repositories_ai_workstation, repositories_omniforces, repositories_blackball [INFERRED 0.75]
- **** — src_auth_session [EXTRACTED]

## Communities (28 total, 19 thin omitted)

### Community 0 - "Standards"
Cohesion: 0.25
Nodes (8): Coding Standards, Documentation Standards, Git Standards, Graphify Standards, Standards README, KingC Software Standards, Versioning Standards, Naming Conventions

### Community 1 - "Session Handover"
Cohesion: 0.53
Nodes (6): Context Builder, Graphify Context Integration, Knowledge Provider, Repository Context, Session Handover 2026-08-01, Session Handover 2026-08-02

### Community 2 - "Development Lifecycle"
Cohesion: 0.40
Nodes (5): KC-001 — Forge, KC-002 — Continue, Development Lifecycle, AI Employees, OmniForces – Session Handover

### Community 3 - "AI Knowledge"
Cohesion: 0.50
Nodes (5): AI Knowledge, AI Workstation, BlackBall, OmniForces, Human Readable Name

### Community 4 - "Agent Management"
Cohesion: 0.40
Nodes (5): AgentManager, Graphify, KnowledgeProvider, MemoryManager, ObsidianContext

### Community 5 - "AI Rules"
Cohesion: 0.67
Nodes (3): AI Knowledge - AI_Workstation History, AI Knowledge - AI Employee Rules, AI Employee Rules

### Community 6 - "Human Readable Name"
Cohesion: 0.67
Nodes (3): Human Readable Name, Human Readable Name, Human Readable Name

### Community 7 - "Coding Standards"
Cohesion: 0.67
Nodes (3): Repositories README, AI Workflow Standards, Coding Standards

### Community 8 - "Versioning"
Cohesion: 1.00
Nodes (3): Versioning Standards, Atomic Task System, Tasks README

## Knowledge Gaps
- **41 isolated node(s):** `Human Readable Name`, `AI Knowledge`, `Future Repositories`, `Human Readable Name`, `Human Readable Name` (+36 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **19 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Are the 4 inferred relationships involving `Session Handover 2026-08-01` (e.g. with `Context Builder` and `Graphify Context Integration`) actually correct?**
  _`Session Handover 2026-08-01` has 4 INFERRED edges - model-reasoned connections that need verification._
- **Are the 4 inferred relationships involving `Session Handover 2026-08-02` (e.g. with `Context Builder` and `Graphify Context Integration`) actually correct?**
  _`Session Handover 2026-08-02` has 4 INFERRED edges - model-reasoned connections that need verification._
- **Are the 4 inferred relationships involving `AgentManager` (e.g. with `Graphify` and `KnowledgeProvider`) actually correct?**
  _`AgentManager` has 4 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Human Readable Name`, `AI Knowledge`, `Future Repositories` to the rest of the system?**
  _41 weakly-connected nodes found - possible documentation gaps or missing edges._