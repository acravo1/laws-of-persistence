# Law 06 — Validated Recovery

## Statement

Nothing is truly protected until recovery has been successfully demonstrated.

---

# Rationale

Organizations frequently measure protection through the existence of safeguards.

Backups exist.

Documentation exists.

Inventories exist.

Repositories exist.

However, the existence of a protection mechanism does not guarantee the ability to restore capability.

Continuity depends on recoverability.

Recoverability depends on demonstrated recovery.

---

# Definition

Validated Recovery is the proven ability to restore:

- information;
- knowledge;
- configuration;
- capability;
- operational state;

within acceptable constraints of time, completeness and reliability.

Validation requires evidence.

Assumptions are insufficient.

---

# Problem

Many organizations mistake possession for recoverability.

Examples include:

- backups never restored;
- disaster recovery plans never executed;
- documentation never tested;
- procedures never rehearsed.

The resulting systems appear protected while remaining unproven.

---

# Observable Symptoms

Indicators of unvalidated recovery include:

- backup jobs reported as successful;
- absence of restoration tests;
- undocumented recovery procedures;
- recovery times based on assumptions;
- uncertainty regarding dependencies;
- lack of recovery evidence.

---

# Historical Example

The distinction between backup and recoverability became highly visible during the 2017 GitLab incident.

Backups existed.

Recovery capability proved significantly more complex than expected.

The lesson is universal:

Protection mechanisms only provide value when recovery is demonstrably possible.

---

# Examples

## Infrastructure

Backups of virtual machines exist.

No restoration test has ever been performed.

Recoverability remains unknown.

---

## Documentation

Critical operational procedures are documented.

No individual has attempted to execute them independently.

Practical recoverability remains unverified.

---

## Knowledge

Knowledge repositories exist.

No process exists for reconstructing capability using only those repositories.

Continuity remains uncertain.

---

# Relationship With Persistence

Persistence without recovery is incomplete.

Storage preserves assets.

Recovery preserves capability.

The distinction is fundamental.

---

# Relationship With Existing Literature

This law aligns with concepts from:

- Disaster Recovery;
- Business Continuity;
- Resilience Engineering;
- Operational Readiness.

The Law of Persistence extends these ideas beyond technology by applying recoverability to:

- knowledge;
- context;
- documentation;
- organizational capability.

---

# Recovery Levels

Validated recovery may exist at multiple levels:

## Data Recovery

Recovery of information.

## System Recovery

Recovery of functionality.

## Knowledge Recovery

Recovery of understanding.

## Capability Recovery

Recovery of operational effectiveness.

## Continuity Recovery

Recovery of sustainable operation.

---

# Consequences

Failure to validate recovery creates:

- false confidence;
- hidden fragility;
- underestimated risk;
- continuity failures.

The absence of testing converts protection into assumption.

---

# Operational Guidance

Recovery should be tested periodically.

Tests should measure:

- completeness;
- repeatability;
- duration;
- dependency requirements;
- operational readiness.

Recovery validation should produce evidence.

---

# Corollaries

Related Corollaries:

- Corollary 3 — A Backup Is Only a Hypothesis Until Recovery Is Validated.
- Corollary 6 — Critical Capability Must Be Auditable.
- Corollary 9 — The Cost of Persistence Is Lower Than the Cost of Reconstruction.

---

# Foundational Principle

A backup proves that data was stored.

A recovery proves that continuity can survive.

