---
layout: page
title: Count Downward
description: Numeric planning with abstraction heuristics, participant of the International Planning Competition 2026.
github: https://github.com/dgnad/numeric-fast-downward
img:
importance: 7
category: work
related_publications: true
---

Count Downward is a numeric planner that extends Numeric Fast Downward with two
families of numeric abstraction heuristics: pattern databases
{% cite gnad-et-al-aaai2025 fritzsche-et-al-aaai2026b %} and domain abstractions
{% cite fritzsche-et-al-socs2026b %}. Several planners built on this codebase
participated in the International Planning Competition 2026, in the optimal,
satisficing, and agile tracks. The sequential portfolios that combine these
configurations and adds the numeric landmark-cut heuristic are called Count 
Downward Together.

The implementation is available on
[GitHub](https://github.com/dgnad/numeric-fast-downward). The repository
receives only rudimentary maintenance; we recommend switching to
[PlanForge](/tools/planforge/), a reimplementation in Rust.
