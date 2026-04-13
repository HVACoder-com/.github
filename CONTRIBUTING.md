# Contributing to DesignBench

## Purpose

DesignBench is developed using a structured, issue-driven workflow.

The goal is to keep work:

- traceable
- intentional
- explainable over time

This repository is not just code—it is a record of decisions, structure, and evolution.

---

## Workflow

1. **Start with an issue**
   - Every meaningful change should originate from or be linked to an issue.
   - Small fixes (typos, formatting, minor corrections) may be handled directly.

2. **Define scope before implementation**
   - Capture, at a minimum:
     - goal
     - scope boundaries
     - acceptance criteria (when applicable)
     - impacted areas
   - Scope should be reasonably understood before deeper implementation begins.

3. **Implement in focused branches (when appropriate)**
   - Branches help isolate work and maintain clarity.
   - For small changes, direct commits may be acceptable.

4. **Validate before submission**
   - Confirm behavior aligns with intended outcomes.
   - Watch for unintended side effects.

5. **Update documentation**
   - Required when:
     - behavior changes
     - structure changes
     - new patterns or conventions are introduced
   - Documentation is part of the deliverable.

6. **Record architectural decisions**
   - Use `docs/adr/` for:
     - cross-cutting concerns
     - design tradeoffs
     - non-obvious decisions

---

## Pull Requests

Pull requests should:

- reference the related issue when applicable (e.g., `Closes #12`)
- clearly describe:
  - what changed
  - why it changed
- remain focused and reviewable
- include documentation updates where appropriate

Pull requests are the primary mechanism for reviewing and understanding changes, even in a solo workflow.

---

## Documentation

Documentation in this repository is part of the **source of truth**.

Prefer:

- Markdown in version control
- explicit architecture notes
- ADRs for significant decisions
- consistent, domain-aligned terminology

Avoid:

- undocumented behavior
- implicit assumptions
- temporary solutions without explanation

---

## Core Principles

- **Traceability over convenience**
- **Clarity over cleverness**
- **Structure over rigidity**
- **Code and documentation evolve together**

---

## Definition of Done

A change is considered complete when:

- [ ] related issue is addressed (if applicable)
- [ ] implementation aligns with intended scope
- [ ] changes are committed with clear history
- [ ] documentation is updated where needed
- [ ] relevant decisions are recorded when appropriate

---

## Guiding Principle

> If a change cannot be understood later through its issue, code, and documentation, it is not fully complete.
