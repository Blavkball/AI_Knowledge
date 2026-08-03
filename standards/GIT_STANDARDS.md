# Git Standards

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

This document defines the official Git standards used throughout the KingC Software ecosystem.

Git is treated as a safety system that protects working software, records progress and provides a reliable history of decisions.

---

# Git Principles

KingC Software follows these Git principles:

- Commit working software.
- Keep commits logical.
- Use meaningful commit messages.
- Protect stable versions.
- Keep repositories clean.
- Verify before finishing work.

---

# Standard Workflow

All changes follow:


Change Required
↓
Understand
↓
Plan
↓
Implement
↓
Test
↓
Commit
↓
Push
↓
Verify


---

# Repository Status Check

Before starting work:

```powershell
git status

Expected:

nothing to commit, working tree clean

A clean repository confirms the starting point is known.

Branch Standards
Main Branch

The main branch represents the stable version of the repository.

Rules:

Working software only.
No unfinished changes.
No experimental code.
Branch Naming

When branches are required, use:

feature/<name>
bugfix/<name>
documentation/<name>
experiment/<name>

Examples:

feature/user-authentication
documentation/update-readme
bugfix/login-error
Commit Standards

Commits should:

Represent one logical change.
Explain what changed.
Be easy to understand later.
Commit Message Format

Use:

<action> <description>

Examples:

Add documentation standards

Fix authentication validation

Update repository overview

Create AI supervisor documentation
Commit Rules

Before committing:

Code tested.
Documentation updated.
Files reviewed.
No unnecessary changes included.
Push Standards

After committing:

git push

The remote repository should always contain the latest approved work.

Repository Cleanliness

Before finishing:

Run:

git status

Expected:

nothing to commit, working tree clean

A clean repository indicates completed work.

AI Employee Git Rules

AI employees must:

Check Git status before changes.
Commit completed work.
Use meaningful commit messages.
Never leave unfinished changes silently.
Report blockers.
Documentation Changes

Documentation updates follow the same Git process as code.

Documentation is part of the software system and must be version controlled.

Git Verification Checklist

This checklist follows the Definition of Done in STANDARDS.md: Saved? Git? Graphify? Documentation?

Before completing a task, confirm all four:

Saved?

- Work is written to disk.

Git?

- git status checked
- Changes staged
- Commit created
- Push completed
- Repository clean

Graphify?

- Graphify run per GRAPHIFY_STANDARDS.md
- Extraction confirmed successful

Documentation?

- Affected documentation updated per DOCUMENTATION_STANDARDS.md

Work is not complete until all four are yes.
Source of Truth

This document defines the official Git standards for KingC Software.

Changes to Git workflow must be documented here before adoption.

Revision History
Version	Date	Description
1.0	31 July 2026	Initial Git standards.