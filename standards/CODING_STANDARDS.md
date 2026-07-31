# Coding Standards

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

This document defines the official coding standards used throughout the KingC Software ecosystem.

The purpose is to ensure software is:

- Reliable.
- Maintainable.
- Understandable.
- Testable.
- Professional.

Code quality is prioritised over speed of implementation.

---

# Coding Principles

KingC Software follows:

- Understand before building.
- Explain before implementing.
- Simplicity over complexity.
- Quality over speed.
- Test before committing.
- Protect working software.
- Continuously improve.

---

# Code Quality Rules

All code should:

- Be readable.
- Have clear responsibilities.
- Avoid unnecessary complexity.
- Follow existing project patterns.
- Be maintainable by another developer.

Code should be written for long-term ownership, not just immediate completion.

---

# Planning Before Coding

Before implementation:

- Understand the requirement.
- Review existing code.
- Check documentation.
- Identify affected systems.
- Create a clear approach.

Do not start coding without understanding the problem.

---

# Simplicity Standard

Prefer:

- Simple solutions.
- Clear designs.
- Small focused functions.
- Easy-to-understand architecture.

Avoid:

- Over-engineering.
- Unnecessary abstraction.
- Complex solutions without benefit.

---

# File Creation Rules

New files must be created carefully.

Correct:


VS Code
↓
Right-click folder
↓
New File
↓
Enter filename


Example:


app
└── models.py


Avoid creating accidental nested structures:


app
└── app
└── models.py


---

# Code Organisation

Code should follow:

- One responsibility per file where practical.
- Clear folder structures.
- Logical naming.
- Consistent formatting.

---

# Testing Standards

Before committing:

- Test changes.
- Check expected behaviour.
- Confirm no existing functionality is broken.

Testing may include:

- Unit testing.
- Integration testing.
- Manual verification.

---

# Error Handling

Software should:

- Handle expected errors.
- Provide useful messages.
- Avoid silent failures.
- Protect user data.

---

# Documentation in Code

Comments should explain:

- Why something exists.
- Important decisions.
- Complex logic.

Avoid comments that simply repeat obvious code.

---

# AI Employee Coding Rules

AI employees must:

- Read documentation first.
- Explain important decisions.
- Keep changes focused.
- Test before committing.
- Update documentation when required.

---

# Code Review Checklist

Before completion:

- Requirement understood?
- Solution simple?
- Code readable?
- Tests completed?
- Documentation updated?
- Git clean?

---

# Source of Truth

This document defines the official coding standards for KingC Software.

Changes to coding practices must be documented here before adoption.

---

# Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 31 July 2026 | Initial coding standards. |