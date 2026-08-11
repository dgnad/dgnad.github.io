---
layout: page
title: PlanForge
description: A numeric planner written in Rust that natively supports numeric variables.
github: https://github.com/mrlab-ai/PlanForge
img:
importance: 6
category: work
related_publications: false
---

PlanForge is a planning system for numeric PDDL tasks. It grounds a task into a
numeric SAS+ representation and searches for a sequential plan, keeping numeric
fluents in the task so that search algorithms and heuristics can reason about
numbers directly. It ships with a range of search algorithms and several heuristics. 
Both a planner (`planforge`) and a standalone translator (`planforge-translator`) are
provided.

The system is written in Rust and requires no dependencies beyond the Rust
toolchain. It started as a port of Numeric Fast Downward, itself a fork of Fast
Downward, and is developed at the Machine Reasoning Lab at Linköping University.

Documentation is available at [mrlab.ai/PlanForge](https://mrlab.ai/PlanForge/index.html),
the implementation on [GitHub](https://github.com/mrlab-ai/PlanForge).

PlanForge is the recommended successor of [Count Downward](/tools/count-downward/).
