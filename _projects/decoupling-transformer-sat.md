---
layout: page
title: Decoupling Transformer SAT
description: SAT-based planning with axioms, built on the Decoupling Transformer.
github: https://github.com/galvusdamor/decoupling-transformer-sat
img:
importance: 4
category: work
related_publications: true
---

Decoupling Transformer SAT extends the Decoupling Transformer with SAT-based
planning. It implements the AxSAT approach, solving classical planning tasks via
satisfiability while supporting conditional effects and axioms, using a
sequential exists-step encoding and the Kissat SAT solver. The approach is
described in our JELIA 2025 paper {% cite behnke-et-al-jelia2025 %}.

The implementation is available on
[GitHub](https://github.com/galvusdamor/decoupling-transformer-sat).

It is built on top of the [Decoupling Transformer](/projects/decoupling-transformer/)
project.
