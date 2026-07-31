# REPOSITORIES.md

---
Version: 1.0
Status: Active
Repository: AI_Knowledge
Owner: KingC Software
Last Updated: 31 July 2026
---

# Repository Overview

## Purpose

This document defines every repository within the KingC Software ecosystem, its purpose, responsibilities and relationships.

Each repository has a single responsibility while working together as part of one engineering ecosystem.

---

# Repository Structure

```
KingC Software
│
├── AI_Knowledge
├── AI_Workstation
├── OmniForces
└── BlackBall
```

---

# AI_Knowledge

## Purpose

The central documentation repository.

## Responsibilities

- Engineering standards
- Architecture documentation
- Repository documentation
- AI employee definitions
- Development workflows
- Company knowledge
- Atomic task system
- Long-term documentation

## Contains

- Markdown documentation
- Engineering standards
- Architecture
- Knowledge base

## Does Not Contain

- Application code
- APIs
- Production software

---

# AI_Workstation

## Purpose

The engineering workspace used during software development.

## Responsibilities

- Development workflow
- AI onboarding
- Session continuity
- Engineering guidance
- Documentation management
- Daily engineering operations

## Depends On

- AI_Knowledge

---

# OmniForces

## Purpose

The AI engineering platform.

## Responsibilities

- AI orchestration
- Memory systems
- Agent communication
- AI services
- Automation
- Future AI workforce management

## Depends On

- AI_Knowledge

---

# BlackBall

## Purpose

Commercial pool league management platform.

## Responsibilities

- League management
- Fixtures
- Results
- Player management
- Statistics
- Competition administration

## Depends On

- AI_Knowledge
- OmniForces (future AI integration)

---

# Repository Relationships

```
                AI_Knowledge
                      │
      ┌───────────────┼───────────────┐
      │               │               │
      ▼               ▼               ▼
AI_Workstation   OmniForces     BlackBall
```

AI_Knowledge provides standards.

AI_Workstation manages engineering.

OmniForces provides AI capability.

BlackBall delivers the commercial application.

---

# Engineering Rules

Each repository should:

- Have one primary responsibility.
- Avoid duplicate documentation.
- Follow AI_Knowledge standards.
- Maintain independent version control.
- Be fully documented.
- Remain professionally maintained.

---

# Documentation Ownership

| Repository | Primary Responsibility |
|------------|------------------------|
| AI_Knowledge | Documentation & Standards |
| AI_Workstation | Engineering Workspace |
| OmniForces | AI Platform |
| BlackBall | Commercial Software |

---

# Repository Lifecycle

Every repository follows the same process:

1. Plan
2. Build
3. Test
4. Document
5. Commit
6. Verify
7. Release

---

# Future Repositories

Any future repository must:

- Have a clearly defined purpose.
- Follow AI_Knowledge standards.
- Maintain independent responsibility.
- Avoid overlapping responsibilities.
- Integrate into the engineering ecosystem.

---

# Source of Truth

Repository architecture is maintained within AI_Knowledge.

Changes to repository responsibilities must be documented here before implementation.

---

# Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 31 July 2026 | Initial repository documentation. |