# Contributing to DesignBench

## Purpose

DesignBench is developed using a structured, issue-driven, documentation-first workflow.

The goal is to keep work:

- traceable
- intentional
- explainable over time

This repository is not just code—it is a record of decisions, structure, and evolution.

## DesignBench Context

DesignBench is a decision-centered engineering system.

Work in this repository should contribute to:

- defining engineering decisions
- capturing design intent
- structuring domain concepts such as equipment, systems, and context
- maintaining traceability between decisions, guidance, and outcomes

Changes that do not support or clarify these areas should be reconsidered.

---

## Workflow

1. **Start with an issue**
   - Every meaningful change should originate from or be linked to an issue.
   - Issues should reflect a clear intent related to:
     - a decision
     - a domain concept
     - a structural or architectural improvement
   - Small fixes (typos, formatting, minor corrections) may be handled directly.

2. **Clarify intent before implementation**
   - Capture, at a minimum:
     - goal
     - scope boundaries
     - acceptance criteria (when applicable)
     - impacted areas
   - Clarify how the change affects:
     - decisions
     - domain structure
     - system behavior
   - When a change affects system behavior, architecture, terminology, or workflow, the intended change should be reflected in documentation before or alongside implementation.

3. **Implement in focused branches (when appropriate)**
   - Branches help isolate work and maintain clarity.
   - For small changes, direct commits may be acceptable.

4. **Validate before submission**
   - Confirm behavior aligns with intended outcomes.
   - Watch for unintended side effects.

5. **Keep documentation ahead of or aligned with code**
   - Documentation should not lag behind implementation.
   - Update documentation when:
     - behavior changes
     - structure changes
     - new patterns or conventions are introduced
     - decisions need to be made explicit
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

It should make engineering intent and system behavior understandable without relying on implicit knowledge.

DesignBench is documentation-first:

- issues define intent
- documentation clarifies structure and behavior
- ADRs capture important decisions
- implementation should follow documented understanding, not replace it

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

- **Documentation before ambiguity**
- **Traceability over convenience**
- **Clarity over cleverness**
- **Structure over rigidity**
- **Code and documentation evolve together**

---

## Definition of Done

A change is considered complete when:

- [ ] related issue is addressed (if applicable)
- [ ] implementation aligns with intended scope
- [ ] impact on decisions, domain structure, or system behavior is clear
- [ ] changes are committed with clear history
- [ ] documentation is updated where needed
- [ ] relevant decisions are recorded when appropriate

---

## Guiding Principle

> If a change cannot be understood later through its issue, documentation, and code, it is not fully complete.
