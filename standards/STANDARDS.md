# KingC Software Standards

## Purpose

This document defines the shared standards used across KingC Software.

These standards are the source of truth for:

- Engineering practices
- Documentation expectations
- Development quality
- AI-assisted workflows

Current standards are maintained in:

AI_Knowledge/standards/STANDARDS.md

---

# Core Principles

## Understand Before Building

Before creating solutions:

- Understand the problem
- Understand existing systems
- Understand requirements
- Understand constraints

Do not build solutions based on assumptions.

---

## Explain Before Implementing

Important changes should include:

- What is changing
- Why it is changing
- How it will work
- Potential risks

Clear communication improves decision quality.

---

## Simplicity Over Complexity

Prefer:

- Simple solutions
- Clear code
- Maintainable architecture
- Practical designs

Avoid unnecessary complexity.

---

## Quality Over Speed

Software should be built to last.

Prioritise:

- Reliability
- Maintainability
- Testing
- Clear design

---

## Protect Working Software

Existing working systems should be treated carefully.

Before major changes:

- Create checkpoints
- Understand impact
- Test thoroughly

---

# Software Development Standards

All development follows this process:

1. Read documentation
2. Understand the assignment
3. Create a plan
4. Build the solution
5. Test thoroughly
6. Update affected documentation
7. Commit working code
8. Verify a clean repository

---

# Coding Standards

Code should be:

- Readable
- Maintainable
- Simple
- Consistent

Developers should:

- Avoid unnecessary complexity
- Prefer clear solutions
- Explain important decisions
- Protect existing functionality

---

# Testing Standards

Before completing work:

- Test changes
- Verify expected behaviour
- Check for regressions
- Confirm the system remains stable

Untested changes should not be considered complete.

---

# Documentation Standards

Documentation should:

- Have one clear purpose
- Maintain one source of truth
- Record important decisions
- Support future understanding

Avoid:

- Duplicate documentation
- Conflicting information
- Unnecessary documents

---

# Repository Standards

Repositories should maintain:

- Clear structure
- Logical commits
- Meaningful history
- Clean working state

Before finishing work:

```text
git status