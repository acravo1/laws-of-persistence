# Mars Climate Orbiter (1999)

## Overview

The loss of the Mars Climate Orbiter remains one of the most frequently cited examples of a context failure within a complex system.

The mission demonstrates that information can exist, systems can function, and expertise can be available, yet continuity can still fail when contextual consistency is lost.

For the Laws of Persistence, the incident illustrates the consequences of context fragmentation across organizational boundaries.

---

# Summary

The Mars Climate Orbiter was launched by NASA in December 1998.

The mission was intended to study the Martian climate and support future exploration efforts.

On 23 September 1999, communication with the spacecraft was lost during orbital insertion.

Subsequent investigation concluded that a mismatch between measurement units contributed directly to the failure.


---

# Context

The mission involved multiple teams and systems.

One component produced thrust-related data using imperial units.

Another component interpreted the data assuming metric units.

The information itself was not missing.

The problem emerged because different parts of the system attached different meanings to the same data.

The context surrounding the information was not preserved consistently across organizational boundaries.


---

# The Problem

At a technical level, the data being exchanged was valid.

The calculations were executed.

The systems operated.

However, a critical contextual assumption differed between teams.

One system assumed pound-force seconds.

Another assumed newton seconds.

The discrepancy propagated through mission operations until the spacecraft entered an incorrect trajectory.

This ultimately resulted in mission loss.


---

# Interpretation Through the Laws of Persistence

## Law 01 — Elimination of Implicit Knowledge

Critical assumptions regarding measurement interpretation were not sufficiently externalized and enforced.

Knowledge existed.

Shared understanding did not.

---

## Law 02 — Declarative Representation

The systems exchanged values successfully.

The meaning attached to those values was not represented consistently.

Representation existed.

Context did not.

---

## Law 03 — Orphan State Detection

The dependency between data and unit interpretation remained insufficiently visible.

A hidden dependency existed.

---

## Law 05 — Evidence Generation

Evidence existed and enabled post-incident investigation.

Without that evidence, root cause identification would have been significantly more difficult.


---

# The Loss Chain

The incident can be interpreted through the Persistence Model.

Loss of Context
        ↓
Loss of Continuity
        ↓
Loss of Capability

The spacecraft was lost not because information disappeared.

The spacecraft was lost because contextual meaning became inconsistent.

The resulting capability degradation became mission-ending.


---

# Lessons Learned

## Lesson 1

Information without shared context can become dangerous.

---

## Lesson 2

Data validity does not guarantee interpretation validity.

---

## Lesson 3

Dependencies should include semantic assumptions in addition to technical interfaces.

---

## Lesson 4

Organizations must preserve not only information but also the meaning attached to that information.


---

# Relationship With the Continuity Hypothesis

The incident supports one of the central ideas of the Laws of Persistence.

Continuity depends on more than information.

Continuity depends on preserving context.

When context is fragmented, capability can fail despite the continued existence of knowledge and data.

---

# Conclusion

The Mars Climate Orbiter demonstrates that continuity failures frequently originate in contextual failures.

The mission reinforces a fundamental principle of the Persistence Model:

Information may survive.

Knowledge may survive.

Without shared context, capability may not.


---

# Primary Sources

The analysis presented in this case study is based primarily on official NASA investigation material.

## NASA Mission Overview

NASA. Mars Climate Orbiter Mission Summary.

https://science.nasa.gov/mission/mars-climate-orbiter/ 【1-21f27c】

According to NASA, the mission failed due to a navigation error caused by a failure to translate English units into metric units, resulting in trajectory calculation errors that sent the spacecraft too close to Mars. 【1-21f27c】【2-d07281】

---

## NASA Mishap Investigation Board

NASA. Mars Climate Orbiter Mishap Investigation Board Phase I Report (November 10, 1999).

https://llis.nasa.gov/llis_lib/pdf/1009464main1_0641-mr.pdf 【3-c4f350】

The investigation board concluded that the root cause was the failure to use metric units within a ground software component used for trajectory modelling. The resulting mismatch introduced cumulative navigation errors throughout the nine-month journey to Mars. 【4-69645a】【3-c4f350】

---

## NASA Lessons Learned

NASA Lessons Learned Information System (LLIS), Lesson 641.

https://llis.nasa.gov/lesson/641 【4-69645a】

NASA's lessons learned database identifies the root cause as the use of English units instead of metric units in trajectory-related software outputs, resulting in an incorrect estimate of spacecraft position and an approach approximately 170 km lower than planned. 【4-69645a】

---

## NASA Technical Investigation

Report on the Loss of the Mars Climate Orbiter Mission. Jet Propulsion Laboratory Special Review Board.

https://ntrs.nasa.gov/citations/20060043364 【5-8d2b67】

This technical review describes the final mission sequence, loss of signal during Mars Orbit Insertion and the subsequent investigation into the navigation anomaly. 【5-8d2b67】

---

# Relevance to the Laws of Persistence

The Laws of Persistence do not interpret the incident merely as a unit conversion error.

The deeper observation is that information remained available while contextual consistency was lost across organizational and technical boundaries.

The mission demonstrates that preserving data alone is insufficient.

Continuity depends upon preserving context, assumptions and shared understanding.

