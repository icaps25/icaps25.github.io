---
title: "Tutorial on Domain-Independent Dynamic Programming"
date: 2025-04-13T00:00:00+00:00
draft: false
---

# Modeling and Solving Combinatorial Optimization Problems with Heuristic Search through Domain-Independent Dynamic Programming

## Abstract

Domain-independent dynamic programming (DIDP) is a recently proposed technology for solving combinatorial optimization problems, such as routing and scheduling problems studied in operations research.
In DIDP, a problem is formulated as a declarative dynamic programming model and then solved by a general-purpose solver.
DIDP is inspired by domain-independent AI planning: its modeling language is based on a state-based problem representation, and its currently developed solvers are based on heuristic search algorithms such as A*.
Recent research has demonstrated that DIDP has state-of-the-art performance in multiple combinatorial optimization problem classes, outperforming commercial constraint programming and mixed integer programming solvers.
We aim to introduce DIDP to the ICAPS community, encouraging researchers to apply AI planning and heuristic search technologies to combinatorial optimization through DIDP.
This tutorial introduces the basics of DIDP and does a hands-on session using DIDPPy, the Python interface of our DIDP software framework.

## Presenters

**Ryo Kuroiwa** is an Assistant Professor at the National Institute of Informatics in Japan. His main interest is in heuristic search and its application to combinatorial optimization and AI planning. He received a Ph.D. from the University of Toronto, supervised by Prof. J. Christopher Beck. During his Ph.D., he developed domain-independent dynamic programming with his supervisor, publishing papers at ICAPS, CPAIOR, the AAAI Conference on Artificial Intelligence (AAAI), and the International Conference on Principles and Practices of Constraint Programming (CP).

**J Christopher Beck** is a Professor in the Department of Mechanical & Industrial Engineering at the University of Toronto. He is the author of over 170 peer reviewed conference and journal publications in AI and Operations Research in areas such as planning, scheduling, constraint programming, and combinatorial optimization. Chris was the President of the Executive Committee for ICAPS and the President of the Association for Constraint Programming and is Editor-in-Chief of the Journal of Artificial Intelligence Research. He recently developed domain-independent dynamic programming with his student, Ryo Kuroiwa.
