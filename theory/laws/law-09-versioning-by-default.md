# Law 09 — Versioning by Default

## Statement

Whenever technically and operationally feasible, history shall be preserved.

The absence of version history should be treated as a design defect.

---

# Rationale

Without history, state becomes disconnected from its evolution.

Without evolution, understanding becomes dependent on memory.

Without memory, continuity becomes impossible.

Versioning preserves the relationship between:

- past;
- present;
- future.

It transforms change from an event into a traceable process.

---

# Definition

Versioning is the systematic preservation of historical states and state transitions.

Versioning enables:

- reconstruction;
- auditability;
- rollback;
- learning;
- accountability.

A version history records not only what exists.

It records how it came to exist.

---

# Problem

Many systems preserve only the current state.

Examples include:

- overwritten files;
- updated configurations;
- modified procedures;
- replaced documentation.

The previous state disappears.

The reasons disappear.

The lessons disappear.

Continuity becomes dependent upon recollection.

---

# Observable Symptoms

Indicators of insufficient versioning include:

- files named "final_v2_final_really_final.docx";
- missing change history;
- inability to identify modifications;
- unknown authorship;
- uncertainty regarding previous states;
- reliance on oral explanations.

---

# Versioning Scope

Versioning should apply not only to software.

It should apply wherever continuity depends upon historical understanding.

Examples include:

- source code;
- configuration;
- documentation;
- architecture;
- procedures;
- inventories;
- decisions;
- policies;
- metadata.

---

# Examples

## Software

Git preserves:

- history;
- authorship;
- timestamps;
- rationale.

Recovery becomes possible.

Learning becomes possible.

---

## Infrastructure

Infrastructure as Code allows:

- rollback;
- comparison;
- reconstruction.

The infrastructure becomes historically observable.

---

## Documentation

Every modification is versioned.

Historical context remains available.

Evolution can be reconstructed.

---

## Organizations

Decision records preserve rationale.

Future stakeholders understand not only the decision but the reasoning behind it.

---

# Relationship With Persistence

Persistence requires more than preservation of current state.

Persistence requires preservation of historical context.

Versioning acts as organizational memory.

It allows capability to survive personnel changes and technological evolution.

---

# Relationship With Existing Literature

This law aligns with concepts from:

- Configuration Management;
- Knowledge Management;
- Records Management;
- Software Engineering;
- Organizational Memory.

The Law of Persistence extends these ideas by treating version history as a continuity mechanism.

---

# Relationship With Git

Git represents one of the most mature implementations of persistence principles.

Git preserves:

- evidence;
- ownership;
- chronology;
- recoverability;
- accountability.

Its importance lies not only in storing files, but in preserving evolution.

---

# Relationship With PAPE

Within PAPE, entities should be version-aware.

Changes to:

- metadata;
- configurations;
- relationships;
- capabilities;
- scripts;
- templates;

should preserve historical lineage.

The objective is not only state storage.

The objective is state evolution preservation.

---

# Consequences

Failure to preserve history results in:

- loss of rationale;
- reduced auditability;
- slower recovery;
- repeated mistakes;
- dependence on memory.

The organization loses the ability to learn from itself.

---

# Operational Guidance

Versioning should be enabled by default.

Deletion should be exceptional.

Replacement should preserve history.

Whenever possible:

- changes should be attributable;
- changes should be timestamped;
- changes should be recoverable.

---

# Corollaries

Related Corollaries:

- Corollary 2 — Undocumented Knowledge Is Persistence Debt.
- Corollary 7 — Versioning Is Organizational Memory.
- Corollary 10 — Organizations Do Not Lose Knowledge; They Lose Capability.

---

# Foundational Principle

Current state explains where a system is.

Version history explains how it got there.

