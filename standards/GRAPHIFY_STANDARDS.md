# Graphify Standards

---
Version: 1.0
Status: Active
Repository: AI_Knowledge
Owner: KingC Software
Last Updated: 31 July 2026
Source of Truth: AI_Knowledge
Applies To:
- AI_Knowledge
- AI_Workstation
- OmniForces
- BlackBall
- All future KingC Software repositories
---

# Purpose

This document defines the official Graphify standards used throughout the KingC Software ecosystem.

Graphify provides knowledge graph extraction and relationship mapping between documentation, repositories and engineering knowledge.

The purpose is to maintain an up-to-date understanding of the KingC Software ecosystem.

---

# Graphify Principles

Graphify usage follows:

- Documentation is the source material.
- Knowledge relationships must remain current.
- Generated knowledge should be verified.
- Graph updates follow documentation changes.
- The knowledge graph supports engineering decisions.

---

# When To Run Graphify

Graphify should be run when:

- New documentation is created.
- Major documentation changes occur.
- Architecture changes.
- Repository structures change.
- New AI employees are introduced.
- Knowledge relationships require updating.

---

# Standard Extraction Command

The standard extraction process uses:

```powershell
graphify extract . `
    --backend ollama `
    --model llama3.2:latest `
    --global `
    --as AI_Knowledge `
    --token-budget 12000 `
    --max-concurrency 1
Graphify Workflow

The process is:

Create Documentation
        ↓
Save Changes
        ↓
Commit Changes
        ↓
Run Graphify
        ↓
Review Output
        ↓
Verify Knowledge Graph
Repository Graph Rules

Each repository should maintain clear relationships.

The knowledge graph should understand:

AI_Knowledge
        │
        ├── Architecture
        │
        ├── Standards
        │
        ├── Employees
        │
        ├── Tasks
        │
        └── Repositories
Verification Checklist

After running Graphify:

Confirm:

Extraction completed successfully.
No processing errors occurred.
New documents are visible.
Relationships are created correctly.
Knowledge graph reflects current documentation.
Git Rules For Graphify

After Graphify execution:

Check:

git status

Review generated changes.

Decide whether generated files should be:

Committed.
Ignored.
Managed separately.

Generated output should not hide unfinished work.

AI Employee Graphify Rules

AI employees must:

Run Graphify when required.
Confirm successful extraction.
Report problems.
Keep knowledge relationships accurate.
Knowledge Graph Purpose

The Graphify knowledge graph supports:

AI context.
Repository awareness.
Documentation discovery.
Engineering decisions.
Future automation.
Source of Truth

This document defines the official Graphify standards for KingC Software.

Changes to Graphify usage must be documented here before adoption.

Revision History
Version	Date	Description
1.0	31 July 2026	Initial Graphify standards.