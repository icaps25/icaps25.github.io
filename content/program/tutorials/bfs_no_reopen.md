---
title: "Best-First Search without Node Re-openings"
date: 2025-06-26T13:27:57+02:00
draft: false
---

## The Theory and Practice of suboptimal Best-First Search without Node Re-openings
### ICAPS 2025 Tutorial

Suboptimal heuristic search has a long history dating to work by Pohl in the early 1970s. At the time, suboptimal search was not well-understood, but over time, this understanding has gradually been filled in, including work on understanding whether Weighted A* needs node-expansions, and the suboptimality bounds that result from using Weighted A*. This has also included work on focal-list algorithms, which generally require node re-expansions. One aspect of this work culminated in a 2021 paper by Chen and Sturtevant, which described the necessary and sufficient conditions for avoiding reopenings in best-first search. These conditions lead to new priority functions for best-first search which can significantly improve performance over Weighted A*, with only an approximately 1-line change to the source code. The goal of this tutorial is to provide attendees with a deep understanding of this work to foster further work on the topic.

This half-day tutorial will use videos and interactive demos (from the [MovingAI Web site](https://www.movingai.com/SAS/)) to work through the theory of avoiding node re-expansions in best-first search. The tutorial will culminate with the example of Dynamic Suboptimality Weighted A*, an algorithm that can decide at runtime where to be more or less suboptimal, while avoiding re-expansions and maintaining a global suboptimality bound. After attending the tutorial, attendees will understand the requirements for avoiding re-expansions and be able to apply them in building new priority functions that can achieve this in different settings.

This tutorial only assumes a knowledge of best-first search, so in some ways it is an introductory tutorial. But, it will go deep quickly (eg we will cover some proofs in detail), so familiarity with inductive proof techniques for best-first search algorithms would be helpful to get the most out of the tutorial.

**Estimated Outline:**
- General overview on suboptimal search [with demos]
- The impact of re-expansions in best-first search [with demos]
- Proofs: WA* bounded suboptimality with and without re-expansions
- Necessary and sufficient conditions for avoiding re-expansions [with demos]
- Deriving new priority functions
- Dynamic Suboptimality Weighted A* [with demo]
- Open directions and problems

Further details (slides, videos, links) will be posted to the [MovingAI web site](https://www.movingai.com/icaps25.html)