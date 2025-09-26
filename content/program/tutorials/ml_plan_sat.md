---
title: "NN-enriched Planning with SMT"
date: 2025-04-13T00:00:00+00:00
draft: false
---


# NN-enriched Planning with SMT
Planning as satisfiability allows for quickly solving even complex planning problems from classical to numerical domains. 
Though it is an efficient and powerful tool, a major bottleneck remains in modelling the planning domain.
While domain models usually are presumed to exist, this typically does not account for real-world planning problems, posing a major limitation in their real-world application.
Although data-driven approaches, such as action model learning, have been proposed to alleviate the modeling overhead, their adoption remains limited and largely confined to research settings.

This tutorial explores how data-driven techniques can be integrated into Satisfiability Modulo Theories (SMT) solvers for automated planning. 
It extends beyond action model learning and builds upon our previous work presented at last year's ECAI [A Lazy Approach to Neural Numerical Planning with Control Parameters](https://ebooks.iospress.nl/doi/10.3233/FAIA241000).
This part will be hands-on. You can find the materials [here](https://github.com/imb-hsu/icaps25-tutorial-nn-enriched-planning-with-smt).


## Outline
The tutorial is organized into four blocks. 
**The first two blocks about SAT solving and planning as Satisfiability are in a joint session with the** [Planning as SAT: What's new?](https://icaps25.icaps-conference.org/program/tutorials/plan_sat/) **tutorial**.
After, the tutorials are split, and we will proceed with the topic "Neural Network-enriched Plannning with SMT" in a separate session.
This session will cover two blocks about fundamentals of Machine Learning for learning state transition models of planning domains and their subsequent integration into a SMT-based approach for planning. 

1. **Gregor Behnke** will present a general introduction to SAT solving (problem, format, tools) and then some encoding methods for classical planning. This will include: encoding of the basic causality of planning, Encodings of Parallelism (Forall, Exists, relaxed Exists, relaxed-relaxed Exists, reinforced), transition-based encoding, and CEGAR-style encoding. Time permitting, Gregor will briefly talk about lifted planning with SAT and QBF.

2. **Matteo Cardellini** will introduce Satisfiability Modulo Theory (SMT) and present recent SMT encodings for numeric planning and his recent work on the Symbolic Pattern Planning Encoding which outperforms all search-based planners for numeric planning. 

---

3. **Jonas Ehrhardt** will introduce fundamentals of ML with a special focus on learning models of state transitions and implications that arise in the context of their application in planning scenarios, e.g., inverse solving or finding and enforcing boundaries. 

4. **René Heesch** will present methods for integrating ML models into SMT-based planning approaches. He will discuss potentials, challenges, and limitations that arise when integrating ML models into satisfiability problems in general and in the context of planning in particular.


## Presenters
- [**Gregor Behnke**](https://staff.science.uva.nl/g.behnke/) is an Assistant Professor for Symbolic AI at the University of Amsterdam, The Netherlands, working on theoretical and practical aspects of planning, which include symbolic reasoning methods (SAT and symbolic search) for both classical and hierarchical planning. 
- [**Matteo Cardellini**](https://matteocardellini.it/) is a Researcher at the University of Genova, Italy. His recent work has focused on planning techniques based on a new SAT-based  paradigm for planning, called Symbolic Pattern Planning, for Classical Planning with Conditional Effects, Numeric and Temporal Planning.
- [**Jonas Ehrhardt**](https://www.researchgate.net/profile/Jonas-Ehrhardt) is a research associate at Helmut Schmidt University. His recent work features Reinforcement Learning and optimization for solving planning problems, with a special focus on offline Reinforcement Learning.
- [**René Heesch**](https://www.researchgate.net/profile/Rene-Heesch) is a research associate at Helmut Schmidt University. His recent work features AI and Formal Methods, with special focus on SMT‐based planning and NN integration.
