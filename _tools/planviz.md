---
layout: page
title: PlanViz
description: Web-based visualization of causal graphs, landmark graphs, and domain transition graphs of PDDL tasks.
github: https://github.com/EliaPfl/planviz
img:
importance: 5
category: work
related_publications: false
---

PlanViz is a web-based tool for visualizing the structure of PDDL planning
tasks. After uploading a domain and problem file, it renders interactive graph
representations of the task: the causal graph, including its strongly connected
components, the landmark graph with its different edge types, and the domain
transition graph of individual variables. The frontend is written in Vue.js
using Cytoscape.js for the graph rendering, while the backend builds on a
modified version of Fast Downward to extract the task structure.

PlanViz was developed by Elia Pfletschinger and Paul Nachtigall as part of a
practical course.

The implementation is available on [GitHub](https://github.com/EliaPfl/planviz).
