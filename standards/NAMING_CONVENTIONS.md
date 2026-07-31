# Naming Conventions

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

This document defines the official naming conventions used throughout the KingC Software ecosystem.

Consistent naming improves:

- Readability.
- Searchability.
- AI understanding.
- Repository organisation.
- Long-term maintenance.

---

# Naming Principles

KingC Software naming follows:

- Clear names over short names.
- Consistency over personal preference.
- Descriptive names over abbreviations.
- Predictable structures across repositories.

---

# Repository Naming

Repositories use:


PascalCase


Examples:

Correct:


AI_Workstation
OmniForces
BlackBall
AI_Knowledge


Rules:

- Names must describe the purpose.
- Avoid unnecessary abbreviations.
- Existing names should not be changed without documentation.

---

# Folder Naming

Folders should use:


lowercase


or


snake_case


Examples:

Correct:


architecture
repositories
employees
graphify_out


Avoid:


Architecture
RepositoryFiles
My Folder


---

# Documentation Naming

Documentation files use:


UPPER_CASE.md


Examples:

Correct:


SYSTEM_OVERVIEW.md
DEVELOPMENT_LIFECYCLE.md
GIT_STANDARDS.md


Avoid:


SystemOverview.md
system-overview.md
systemoverview.md


---

# Code File Naming

Code files should follow the language standard.

Examples:

Python:


snake_case.py


Example:


user_service.py
database_manager.py


JavaScript:


camelCase.js


Example:


userService.js


---

# Class Naming

Classes use:


PascalCase


Examples:


UserManager
DatabaseConnection
AIResponse


---

# Function Naming

Functions use:


snake_case


Examples:


load_configuration()
create_response()
check_status()


---

# Variable Naming

Variables should be:

- Clear.
- Descriptive.
- Easy to understand.

Examples:

Good:


user_count
repository_name
task_status


Avoid:


x
temp
data1


---

# Branch Naming

Git branches use:


type/name


Examples:


feature/user-login
bugfix/api-error
documentation/update-guide


---

# Commit Naming

Commit messages should describe the action.

Examples:


Add Graphify standards

Update repository documentation

Fix authentication error


---

# AI Employee Naming

AI employees follow:


KC-XXX


Examples:


KC-001 Forge
KC-002 Continue


Future employees should receive:

- Unique identifier.
- Defined role.
- Documented responsibilities.

---

# Naming Review Checklist

Before creating a new item:

- Is the name clear?
- Does it follow the standard?
- Is it consistent with existing names?
- Will humans and AI understand it?

---

# Source of Truth

This document defines the official naming conventions for KingC Software.

Changes to naming rules must be documented here before adoption.

---

# Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 31 July 2026 | Initial naming conventions. |