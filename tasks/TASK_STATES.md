# TASK_STATES.md

---
Version: 1.0
Status: Active
Repository: AI_Knowledge
Owner: KingC Software
Last Updated: 31 July 2026
---

# Task States

## Purpose

This document defines the standard states used within the KingC Software Atomic Task System.

Task states provide a clear understanding of progress from creation through completion.

---

# Task State Flow


Created
↓
Ready
↓
In Progress
↓
Testing
↓
Documentation
↓
Review
↓
Completed


---

# Created

## Meaning

The task has been identified and recorded.

## Requirements

A created task should contain:

- Task name.
- Purpose.
- Expected outcome.
- Owner.

The task is not ready for implementation until it has been understood.

---

# Ready

## Meaning

The task has been reviewed and is ready to begin.

Requirements:

- Objective understood.
- Dependencies identified.
- Approach agreed.

---

# In Progress

## Meaning

Active work is currently being completed.

During this state:

- Development takes place.
- Research may occur.
- Changes are made.
- Progress is recorded.

---

# Testing

## Meaning

The implementation is complete and requires verification.

Testing may include:

- Feature testing.
- Error checking.
- Regression testing.
- Integration testing.

---

# Documentation

## Meaning

The completed work is being recorded.

Documentation should include:

- What changed.
- Why it changed.
- Important decisions.
- Related systems.

---

# Review

## Meaning

The task is being checked before completion.

Review confirms:

- Requirements met.
- Testing complete.
- Documentation complete.
- Repository clean.

---

# Completed

## Meaning

The task has successfully finished.

Completion requires:

- Work saved.
- Git committed.
- Verification complete.
- Documentation updated.
- Graphify updated where required.

---

# Blocked

## Meaning

The task cannot continue due to an issue.

Examples:

- Missing information.
- Technical problem.
- Dependency issue.
- Required decision.

Blocked tasks should record:

- Reason.
- Impact.
- Required action.

---

# Cancelled

## Meaning

The task is no longer required.

Cancelled tasks should record:

- Reason for cancellation.
- Date.
- Decision owner.

---

# AI Employee Usage

AI employees should always know:

- Current task state.
- Next required action.
- Completion requirements.

Tasks should never move directly to completed without verification.

---

# State Change Rules

Tasks should move through states in order unless there is a documented reason.

Example:


Ready → In Progress → Testing → Completed


Skipping states should be avoided.

---

# Source of Truth

The Atomic Task System and task states are maintained within AI_Knowledge.

Changes to task states must be documented before adoption.

---

# Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 31 July 2026 | Initial task states documentation. |