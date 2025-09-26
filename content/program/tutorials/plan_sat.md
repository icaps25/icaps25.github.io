---
title: "Planning as SAT: What's new?"
date: 2025-06-24T00:00:00+00:00
draft: false
---

# Planning as SAT: What's new?

Despite the growing prevalence of heuristic search and learning-based approaches in automated planning, Satisfiability-based Planning (SAT-based planning) continues to represent a robust and promising paradigm. Indeed, SAT approaches have a long-standing tradition of strong theoretical foundations [1] and demonstrated success across various domains. This tutorial aims to re-establish the relevance of SAT-based planning by highlighting recent progress, examining emerging applications, and identifying pathways for future research and integration.

### Outline
The talk will be split in four sections, one for each presenter. The first two sections are joint with the workshop [NN-enriched Planning with SMT](https://icaps25.icaps-conference.org/program/tutorials/ml_plan_sat/).

 1. **Gregor Behnke** will present a general introduction to SAT solving (problem, format, tools) and then some encoding methods for classical planning. This will include: encoding of the basic causality of planning [2], Encodings of Parallelism (Forall, Exists [11], relaxed Exists [14], relaxed-relaxed Exists [12], reinforced [15]), transition-based encoding [16], and CEGAR-style encoding [17]. Time permitting, Gregor will briefly talk about lifted planning with SAT [13] and QBF [18].

2. **Matteo Cardellini**  will introduce Satisfiability Modulo Theory (SMT) and present recent SMT encodings for numeric planning [3,4] and his recent work on the Symbolic Pattern Planning Encoding [5] which outperforms all search-based planners for numeric planning. 

3. **Andrea Micheli** will introduce the audience to the basics of Optimization Modulo Theory (OMT) [6] and present a series of encodings for *optimally* solving numeric [7] and temporal [8] planning.

4. **Nicola Gigante** will discuss about the related topic of *compilability* between planning problems, starting from the seminal work by Nebel [9] and including more recent results [10].

### Presenters
 - [**Gregor Behnke**](https://staff.science.uva.nl/g.behnke/) is an Assistant Professor for Symbolic AI at the University of Amsterdam, The Netherlands, working on theoretical and practical aspects of planning, which include symbolic reasoning methods (SAT and symbolic search) for both classical and hierarchical planning. 
- [**Matteo Cardellini**](https://matteocardellini.it/) is a Researcher at the University of Genova, Italy. His recent work has focused on planning techniques based on a new SAT-based  paradigm for planning, called Symbolic Pattern Planning, for Classical Planning with Conditional Effects, Numeric and Temporal Planning.
- [**Nicola Gigante**](https://www.inf.unibz.it/~gigante/) is a Researcher at the Free University of Bozen-Bolzano, Italy, focusing on foundations of temporal reasoning in a broad sense, from (temporal) planning to temporal logic. 
- [**Andrea Micheli**](https://andrea.micheli.website/) is Head of the Planning, Scheduling and Optimization unit at Fondazione Bruno Kessler in Trento, Italy. His research focuses on the development and technology transfer of temporal planning technologies using both symbolic and search-based methods. He is also PI of an ERC project focused on combining automated temporal planning and reinforcement learning.

#### References

[1]  Kautz, H. A. and Selman, B. (1992). Planning as satisfia-
bility. In Neumann, B., editor, 10th European Conference on Artificial Intelligence,
ECAI 92, Vienna, Austria, August 3-7, 1992. Proceedings, pages 359–363. John Wiley
and Sons.

[2] Kautz, H., McAllester, D., and Selman, B. (1996). Encoding Plans
in Propositional Logic.

[3] Scala, E., Ram´ırez, M., Haslum, P., and Thi´ebaux, S. (2016). Nu-
meric planning with disjunctive global constraints via SMT. In Proceedings of
the Twenty-Sixth International Conference on Automated Planning and Scheduling,
ICAPS 2016, London, UK, June 12-17, 2016, pages 276–284. AAAI Press.

[4] Bofill, M., Espasa, J., and Villaret, M. (2017). Relaxed Exists-Step
Plans in Planning as SMT. In Proceedings of the Twenty-Sixth International Joint
Conference on Artificial Intelligence, pages 563–570, Melbourne, Australia. Interna-
tional Joint Conferences on Artificial Intelligence Organization.

[5] Cardellini, M., Giunchiglia, E., and Maratea, M. (2024). Sym-
bolic numeric planning with patterns. In Thirty-Eighth AAAI Conference on Artificial
Intelligence, AAAI 2024, Thirty-Sixth Conference on Innovative Applications of Ar-
tificial Intelligence, IAAI 2024, Fourteenth Symposium on Educational Advances in
Artificial Intelligence, EAAI 2014, February 20-27, 2024, Vancouver, Canada, pages
20070–20077. AAAI Press.

[6] Sebastiani, R. and Tomasi, S. (2015). Optimization mod-
ulo theories with linear rational costs. ACM Trans. Comput. Log., 16(2):12:1–12:43.

[7] Leofante, F., Giunchiglia, E., ´Abrah´am, E., and Tacchella, A.
(2020). Optimal planning modulo theories. In Bessiere, C., editor, Proceedings of the
Twenty-Ninth International Joint Conference on Artificial Intelligence, IJCAI 2020,
pages 4128–4134. ijcai.org.

[8]  Panjkovic, S. and Micheli, A. (2024). Abstract action
scheduling for optimal temporal planning via OMT. In Thirty-Eighth AAAI Con-
ference on Artificial Intelligence, AAAI 2024, Thirty-Sixth Conference on Innovative
Applications of Artificial Intelligence, IAAI 2024, Fourteenth Symposium on Educa-
tional Advances in Artificial Intelligence, EAAI 2014, February 20-27, 2024, Vancou-
ver, Canada, pages 20222–20229. AAAI Press.

[9] Nebel, B. (2000). On the compilability and expressive power of proposi-
tional planning formalisms. J. Artif. Intell. Res., 12:271–315.

[10]  Gigante, N. and Scala, E. (2023). On the compilability of
bounded numeric planning. In Proceedings of the Thirty-Second International Joint
Conference on Artificial Intelligence, IJCAI 2023, 19th-25th August 2023, Macao,
SAR, China, pages 5341–5349. ijcai.org.

[11] Rintanen, J., Heljanko, K., & Niemelä, I. (2004). Parallel encodings of classical planning as satisfiability. In European Workshop on Logics in Artificial Intelligence (pp. 307-319).

[12] Balyo, T. (2013). Relaxing the relaxed exist-step parallel planning semantics. In 2013 IEEE 25th International Conference on Tools with Artificial Intelligence (pp. 865-871). IEEE.

[13] Höller, D., & Behnke, G. (2022). Encoding lifted classical planning in propositional logic. In Proceedings of the International Conference on Automated Planning and Scheduling (Vol. 32, pp. 134-144).

[14] Wehrle, M., & Rintanen, J. (2007). Planning as satisfiability with relaxed-step plans. In Australasian Joint Conference on Artificial Intelligence (pp. 244-253).

[15] Balyo, T., Barták, R., & Trunda, O. (2015). Reinforced encoding for planning as sat. Acta Polytechnica CTU Proceedings, 2(2), 1-7.

[16] Huang, R., Chen, Y., & Zhang, W. (2012). SAS+ planning as satisfiability. Journal of Artificial Intelligence Research, 43, 293-328.

[17] Froleyks, N., Balyo, T., & Schreiber, D. (2019). PASAR—Planning as Satisfiability with Abstraction Refinement. In Proceedings of the International Symposium on Combinatorial Search (pp. 70-78).

[18] Shaik, I., & van de Pol, J. (2022). Classical planning as QBF without grounding. In Proceedings of the International Conference on Automated Planning and Scheduling (pp. 329-337).
