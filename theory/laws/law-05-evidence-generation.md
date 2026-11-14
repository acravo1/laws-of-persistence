# Law 05 — Evidence Generation

## Statement

Every significant change shall generate verifiable evidence.

---

# Rationale

Knowledge of the current state of a system is insufficient to understand how that state was reached.

Without evidence, history becomes dependent on memory.

When memory degrades, causality becomes impossible to reconstruct.

Evidence transforms events into persistent knowledge.

---

# Definition

Evidence is any persistent representation capable of demonstrating that an event, action, decision or change occurred.

Examples include:

- commits;
- logs;
- changelogs;
- decision records;
- audit records;
- tickets;
- events;
- approvals;
- reviews;
- version history.

Evidence must be:

- attributable;
- timestamped;
- durable;
- verifiable.

---

# Problem

Many systems preserve current state while failing to preserve the sequence of events that produced that state.

As a result:

- decisions lose rationale;
- failures lose traceability;
- learning becomes impossible;
- accountability becomes ambiguous.

The organization remembers outcomes but forgets causes.

---

# Observable Symptoms

Indicators of insufficient evidence include:

- undocumented decisions;
- unknown change history;
- unexplained configurations;
- inability to identify who approved a change;
- inability to reconstruct incidents;
- repeated operational mistakes.

---

# Historical Perspective

History is the accumulation of evidence.

Organizations evolve through decisions.

Without evidence, organizations lose their ability to understand themselves.

A system without evidence possesses state but lacks history.

---

# Examples

## Software Development

Source code exists.

No commit history exists.

Future developers understand what was built but not why it was built.

---

## Infrastructure

Configuration exists.

Change records do not.

Failures become difficult to investigate.

---

## Organizational Decision Making

A strategic decision was made.

The justification was never recorded.

Future stakeholders inherit consequences without understanding rationale.

---

# Relationship With Persistence

Persistence is not merely the preservation of state.

Persistence is the preservation of state transitions.

Evidence preserves transitions.

Without evidence, continuity becomes dependent on institutional memory.

---

# Relationship With Existing Literature

This law aligns with concepts from:

- Auditability;
- Traceability;
- Configuration Management;
- Information Governance;
- Knowledge Management.

The Law of Persistence treats evidence generation as a prerequisite for continuity rather than merely a compliance mechanism.

---

# Git as a Persistence Mechanism

Git provides one of the most successful examples of systematic evidence generation.

Every commit records:

- author;
- timestamp;
- change;
- context;
- history.

Git does not merely preserve code.

Git preserves the evolution of code.

The distinction is fundamental.

---

# Consequences

Without evidence:

- accountability decreases;
- recoverability decreases;
- learning decreases;
- governance weakens;
- continuity becomes fragile.

---

# Operational Guidance

Whenever a significant action occurs, evidence should be generated.

Examples:

- changes produce commits;
- decisions produce records;
- incidents produce reports;
- approvals produce audit trails;
- events produce logs.

Evidence should be created automatically whenever technically possible.

---

# Corollaries

Related Corollaries:

- Corollary 3 — A Backup Is Only a Hypothesis Until Recovery Is Validated.
- Corollary 7 — Versioning Is Organizational Memory.
- Corollary 8 — Continuity Degrades Silently.

---

# Foundational Principle

Knowledge explains the present.

Evidence explains how the present came to exist.

