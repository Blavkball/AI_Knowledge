# Documentation Standards

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

This document defines the official documentation standards used throughout the KingC Software ecosystem.

The purpose is to ensure all documentation is:

- Consistent.
- Understandable.
- Maintainable.
- Searchable.
- Useful for both humans and AI employees.

Documentation is considered part of the software system and must be maintained with the same care as code.

---

# Documentation Principles

KingC Software documentation follows:

- One document = one responsibility.
- One source of truth for each topic.
- Explain before implementing.
- Document important decisions.
- Keep information current.
- Remove unnecessary duplication.
- Prefer clarity over complexity.

---

# Required Document Header

Every official document must begin with:

```markdown
# Document Title

---
Version: 1.0
Status: Active
Repository: Repository Name
Owner: KingC Software
Last Updated: DD Month YYYY
Source of Truth: Repository Name
Applies To:
- Repository
---
Document Naming

Documentation files must use:

UPPER_CASE.md

Examples:

Correct:

SYSTEM_OVERVIEW.md
DEVELOPMENT_LIFECYCLE.md
GIT_STANDARDS.md

Incorrect:

systemOverview.md
system-overview.md
SystemOverview.md
Document Structure

Standard documents should contain:

Purpose

Explain why the document exists.

Main Content

Explain the responsibility of the document.

Use:

Clear headings.
Short sections.
Lists where appropriate.
Examples when useful.
Relationships

Explain connections to:

Other documents.
Repositories.
AI employees.
Development processes.
Source of Truth

Every document must clearly state what information it owns.

Example:

This document is the source of truth for Git workflow standards.
Revision History

Every document must finish with:

# Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | DD Month YYYY | Initial document |
Document Status Values

Approved status values:

Draft

Document is being created.

Review

Document is being checked.

Active

Document is approved and operational.

Archived

Document is no longer active but retained for history.

Updating Documentation

Documentation must be updated when:

Architecture changes.
Development processes change.
New standards are introduced.
Important decisions are made.

Documentation should be updated before major changes are considered complete.

AI Employee Documentation Rules

AI employees must:

Read relevant documentation before work.
Update documentation after important changes.
Avoid creating duplicate information.
Reference existing sources of truth.
Markdown Standards

Use:

Clear headings.
Consistent formatting.
Code blocks for commands.
Tables for structured information.
Lists for multiple items.

Avoid:

Large unbroken paragraphs.
Duplicate explanations.
Temporary notes in permanent documents.
Documentation Review Checklist

Before completing a document:

Purpose defined?
Owner defined?
Source of truth defined?
Version included?
Last updated date included?
Related documents identified?
Revision history included?
Source of Truth

This document defines the official documentation standards for KingC Software.

All future documentation should follow these rules.

Revision History
Version	Date	Description
1.0	31 July 2026	Initial documentation standards.