# Law 02 — Declarative Representation

## Statement

Everything that exists should be capable of being described outside itself.

---

# Rationale

A system cannot be reliably understood, governed, recovered or evolved if its structure exists only in its implementation.

Whenever understanding depends upon direct access to the system itself, continuity becomes fragile.

Representation enables persistence.

What cannot be represented cannot be preserved.

---

# Definition

Declarative Representation is the explicit description of a system independent of its execution.

A declarative representation describes:

- what exists;
- how it is related;
- why it exists;
- how it should behave.

without requiring direct inspection of the implementation.

---

# Problem

Many systems contain information that exists only in operational form.

Examples include:

- infrastructure known only by live inspection;
- undocumented configurations;
- applications without architectural descriptions;
- business processes known only through observation.

In such environments, understanding becomes dependent on access and interpretation.

This dependency increases continuity risk.

---

# Observable Symptoms

Indicators of poor representation include:

- undocumented assets;
- architecture diagrams that no longer reflect reality;
- manual discovery processes;
- configuration drift;
- inability to reconstruct system topology;
- dependence on expert interpretation.

---

# Examples

## Software

Source code exists.

Architecture does not.

Understanding requires reading implementation details.

Representation is insufficient.

---

## Infrastructure

Servers exist.

Networks exist.

Configurations exist.

No inventory exists.

The operational state becomes the only source of truth.

---

## Organizations

Processes exist.

Roles exist.

Dependencies exist.

No formal model exists.

Continuity depends on institutional memory.

---

# Relationship With Persistence

Declarative representation transforms hidden structures into persistent structures.

It enables:

- documentation;
- automation;
- governance;
- recovery;
- transfer of knowledge.

Representation is therefore a prerequisite for persistence.

---

# Relationship With PAPE

The PAPE architecture is fundamentally based on declarative representation.

Its objective is to represent:

- systems;
- components;
- relationships;
- services;
- events;
- configurations;
- capabilities;

through persistent metadata.

This allows operational reality to be reconstructed independently of individual memory.

---

# Relationship With Existing Literature

This law aligns with concepts from:

- Model Driven Engineering;
- Enterprise Architecture;
- Configuration Management;
- Knowledge Representation;
- Organizational Memory.

The Law of Persistence extends these ideas by treating representation as a continuity requirement rather than merely an architectural practice.

---

# Consequences

Without declarative representation:

- recovery becomes more difficult;
- governance becomes weaker;
- onboarding becomes slower;
- continuity becomes dependent upon experts.

---

# Operational Guidance

Whenever possible, systems should possess explicit representations of:

- assets;
- relationships;
- dependencies;
- ownership;
- configurations;
- operational procedures.

The representation should remain understandable independently of the implementation.

---

# Corollaries

Related Corollaries:

- Corollary 1 — Information Without Context Is Functionally Equivalent to Lost Information.
- Corollary 6 — Critical Capability Must Be Auditable.
- Corollary 7 — Versioning Is Organizational Memory.

---

# Foundational Principle

If a system can only be understood by observing it directly, the system is insufficiently represented.

