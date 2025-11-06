---
title: "KRPlan"
date: 2025-04-25T00:00:00+00:00
draft: false
---

# KRPlan: Knowledge Representation Meets Automated Planning

Joint workshop at [KR 2025](https://kr.org/KR2025) and [ICAPS 2025](https://icaps25.icaps-conference.org/)\
Melbourne, Australia\
November 11, 2025

Registration is possible through either ICAPS or KR (full or workshop registration).


<div style="background-color: #f5821f; padding: 15px; margin: 20px 0; border-radius: 8px;">
<h2 style="margin: 0; font-size: 1.3em;">KRPlan takes place in the Lyle Theatre (Room 101) of the <a href="https://kr.org/KR2025/info_venue.html">Redmond Barry Building (Building 115)</a> of the University of Melbourne (17 Spencer Road), located a 5-minute walk from Melbourne Connect.
The breaks are aligned with the other KR workshops, but we start slightly earlier.</h2>
</div>

## Description

Traditionally, the areas of Knowledge Representation and Reasoning
(KR) and Automated Planning are related via common connections to
logical theories of acting and sensing, robotics, and temporal
logics.  However, the two research areas have developed in distinct
directions, with the focus of KR research being more on theoretical
results, such as the complexity of logical reasoning, while Automated
Planning research has produced powerful heuristic search approaches
that work on large problems from industry. There is substantial
research interest in the connection between the two fields, with
approaches ranging from temporal reasoning about actions and goals,
answer set planning, ontology-based planning specifications,
epistemic planning, to planning under open-world semantics.

Knowledge Representation Meets Automated Planning (KRPlan) aims at
bringing together researchers from the fields of Knowledge
Representation and Reasoning and Automated Planning to discuss and
develop ideas for applying state-of-the-art techniques from KR and
Planning for modeling and solving complex planning and reasoning
problems. We invite both theoretical and practical contributions
from these areas, including but not limited to:

 * Expressive planning domain models
 * Background knowledge for planning tasks
 * Improved preprocessing and search
 * Heuristic search techniques for reasoning
 * Explanations of dynamic systems
 * Standard formats like PDDL and OWL
 * Tailored search heuristics
 * Theories of actions and processes
 * Situation calculus
 * Temporal logic reasoning
 * Answer set planning
 * Knowledge engineering

## Schedule
|8:50|Session 1|
|:---|:---|
|8:50|Opening|
|9:00|**Invited Talk**<br>Sasha Rubin<br>*Best-effort Planning*|
|10:00|Mikhail Soutchanski (Remote)<br>*Bounded Proper Planning* ([PDF](../krplan-papers/soutchanski-krplan25.pdf))|
|**10:30**|**Tea/Coffee Break**|
|**11:00**|**Session 2**|
|11:00|Guang Hu, Tim Miller and Nir Lipovetzky<br>*Where Common Knowledge Cannot Be Formed, Common Belief Can – Planning with Multi-Agent Belief Using Group Justified Perspectives* ([PDF](../krplan-papers/hu-et-al-krplan25.pdf))|
|11:30|Guang Hu, Weijia Li and Yangmengfei Xu<br>*Beyond Static Assumptions: the Predictive Justified Perspective Model for Epistemic Planning* ([PDF](../krplan-papers/hu-et-al-krplan25a.pdf))|
|12:00|Shenghui Chen, Shufang Zhu, Giuseppe De Giacomo and Ufuk Topcu<br>*Learning to Coordinate without Communication under Incomplete Information* ([PDF](../krplan-papers/chen-et-al-krplan25.pdf))|
|**12:30**|**Lunch Break**|
|**14:00**|**Session 3**|
|14:00|Stefan Borgwardt, Duy Nhu and Gabriele Röger<br>*Automated Planning with Ontologies under Coherence Update Semantics (Extended Abstract)* ([PDF](../krplan-papers/borgwardt-et-al-krplan25.pdf))|
|14:30|Claudia Grundke and Gabriele Röger<br>*Eliminating Negative Occurrences of Derived Predicates from PDDL Axioms* ([PDF](../krplan-papers/grundke-roeger-krplan25.pdf))|
|15:00|Siqi Cheng and Patrik Haslum<br>*From Words to Action: Creating a General Narrative Planning Domain from VerbNet* ([PDF](../krplan-papers/cheng-haslum-krplan25.pdf))|
|**15:30**|**Tea/Coffee Break**|
|**16:00**|**Session 4**|
|16:00|David Wang and Mohammad Abdulaziz<br>*Verified Certification of Unsolvability of Temporal Planning Problems* ([PDF](../krplan-papers/wang-abdulaziz-krplan25.pdf))
|16:30|**Panel Discussion**<br>Giuseppe De Giacomo, Patrik Haslum, Guang Hu, Shufang Zhu<br>*Challenges in Combining Knowledge Representation and Automated Planning*|
|17:20|Closing|

<p></p>

## Invited Speaker

### Sasha Rubin

<img style="float:left; padding-right:1em; padding-bottom:1em" src="https://www.sydney.edu.au/AcademicProfiles/profile/resource?urlid=sasha.rubin">

Dr Sasha Rubin holds an undergraduate degree in mathematics and computer science from the University of Cape Town, and a PhD in mathematics and computer science from the University of Auckland. Before joining the University of Sydney in 2019 as a Senior Lecturer in Computer Science, he worked at the University of Naples Federico II. His research interests are Mathematical Logic, Foundations of Synthesis and Planning, Formal Methods, and Finite and Algorithmic Model Theory.

### Best-effort Planning

Automation is no longer just about reproducing laborious tasks; it involves programs/agents making decisions. For example, a robot interacting with a human in a manufacturing environment, or an underwater autonomous vehicle. Although agents excel at making decisions under risk (when probabilities can be calculated or sampled) they have trouble making decisions under ignorance (when the available information is too scarce to be aggregated by probabilities). Many critical environments display such unmeasurable uncertainty, e.g., due to unpredictable human behaviour or unfamiliar terrain.

Planning has traditionally handled such unmeasurable uncertainty by framing it as Nondeterministic Planning. Here, the standard solution concepts are *strong policies* (this assumes Murphy’s law, i.e., that anything that can go wrong will go wrong), and *strong-cyclic policies* (this assumes that the environment is governed by an unknown probability distribution). However, even when such policies are appropriate, they may not exist.

In this talk, I will describe an approach for doing Planning under Ignorance (in case that standard solution concepts do not exist or are not appropriate). It is based on the dominance principle from Decision Theory, and results in what we call *best-effort policies*.

## Important Dates

* ~~Abstract submission: July 23, 2025~~
* ~~Paper submission: ~~July 23, 2025~~ July 29, 2025~~
* ~~Notification: August 27, 2025~~
* Workshop: November 11, 2025

All deadlines are AoE (UTC-12).

## Submission

We invite extended abstracts of 2-5 pages on topics related to both
KR and Automated Planning. The papers should be formatted in Springer
LNCS Style and submitted via [EasyChair](https://easychair.org/conferences?conf=krplan2025).

The workshop will only have informal proceedings and the main
purpose is to encourage discussions. We welcome not only papers
covering unpublished results, but also abstracts of previous
publications that fall within the scope of the workshop.

## Workshop Committee

### Organizing Committee

- [Stefan Borgwardt](https://lat.inf.tu-dresden.de/~stefborg/), TU Dresden, Germany
- [Giuseppe De Giacomo](https://www.cs.ox.ac.uk/people/giuseppe.degiacomo/), University of Oxford, UK
- [Patrick Koopmann](https://research.vu.nl/en/persons/patrick-koopmann), Vrije Universiteit Amsterdam, The Netherlands
- [Gabriele Röger](https://ai.dmi.unibas.ch/people/roeger/), University of Basel, Switzerland

Contact: [krplan2025@easychair.org](mailto:krplan2025@easychair.org)

### Program Committee

- Gregor Behnke, University of Amsterdam, The Netherlands
- Sara Bernardini,	University of Oxford, UK
- Lukáš Chrpa, Czech Technical University in Prague, Czech Republic
- Birte Glimm, Universität Ulm, Germany
- Alisa Kovtunova, TU Dresden, Germany
- Gerhard Lakemeyer, RWTH Aachen University, Germany
- Leonardo Lamanna, Fondazione Bruno Kessler, Italy
- Christian Muise, Queen's University, Canada
- Bernhard Nebel, Freiburg University, Germany
- Fabio Patrizi, Sapienza University of Rome, Italy
- Jussi Rintanen, Aalto University, Finland
- Sasha Rubin, The University of Sydney, Australia
- Mikhail Soutchanski, Toronto Metropolitan (formerly Ryerson) University, Canada
- Marcel Steinmetz, LAAS-CNRS, France
