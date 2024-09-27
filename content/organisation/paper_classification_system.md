# ICAPS 2025 Paper Classification System

Inspired by the [ACM 2012 Computing Classification System](https://www.acm.org/publications/class-2012-intro) we have
developed a paper classification system to better index research papers on planning and scheduling. 
Indexing submissions in a careful manner helps authors be found by the most relevant reviewers and to track how the
research interests and efforts of the community evolve over time.

ICAPS 2025 uses the following definition for the term _planning, that is independent of formalisms and algorithms. 
_Planning_ is a **synthesis task** that involves the
formulation of a course of action to achieve some desired objective or objectives. Such a course of actions is rigorously
defined as a structure in which objects called _actions_ are bound together by some mathematical relation
and arranged in specific patterns often represented as graphs. Actions 
represent activities or processes that change in some way the properties of or existing relations amongst a given set of 
objects or entities other than actions.
Objectives in planning problems encompass a diverse set of concepts, such as achieving a set of 
_goals_, instantiating or performing an abstract task, or optimising some given objective function. ICAPS assumes the task 
of seeking such courses of action is solved
in an autonomous or semi-autonomous fashion by suitably defined algorithms implemented on some computing device or network
of such devices.

ICAPS 2025 welcomes submissions of research on any type of planning problems, including but not limited to specialised ones such as 
motion and path planning, production and route planning, and scheduling. We invite authors to carefully consider what
of the tags below best describe the nature and form of their contributions to ensure that expert reviewers are matched
to their papers.

Our system is flat and allows to attach three categories of terms (tags) to submissions: types, topics and subjects.

## Type Tags

Submissions can be tagged with one of the following terms that describe the nature of the contributions that readers will
find in the paper. We note that the authors of papers where contributions match multiple of the terms below will
**need to choose one**, that describes best the most crucial contribution in the paper. If the authors research spans
more than one type of contribution, we encourage authors to consider submitting additional, shorter papers to the 
conference or its satellite workshops. 

- **Theoretical**  
  - The paper reports contributions that broaden the set of analytical tools to study problems and algorithms. 
  - Examples of contributions in this category would be, but are not limited to: complexity results, 
    expressiveness/compilations, new frameworks
- **Algorithmic** 
  - The paper reports contributions that add new methodologies and algorithms to solve planning problems.
  - Examples of contributions in this category would be, but are not limited to: optimisations/specialisations of 
    existing algorithms, propagators, decompositions into sub-problems, etc.
- **Models** 
  - The paper describe new representations of planning problems and their solutions. 
  - Examples of contributions in this category would be, but are not limited to: new mathematical frameworks for 
    existing problems or original descriptions of new problems, refinements in existing frameworks for knowledge 
    representation of actions, goals, states, or other rigorously defined concept that describes solutions
    planning and scheduling problems.
- **Position Paper**
  - The paper contributes a thoughtful critique or bold new perspectives of the field.
  - Examples of contributions in this category would be: meta-analysis of research trends, descriptions of new challenge 
    problems suitable for planning and scheduling, historical perspectives and analysis of the field and technical 
    discussions of various implementation techniques.
- **Tools**
  - The paper discusses a tool of interest to the community or a new version of a tool built using novel algorithmic
    and engineering techniques. 
  - Examples of contributions in this category would be, but are not limited to, planners (i.e. solvers integrating 
    representations and methods), model checkers and synthesis tools, general libraries to construct, manage and 
    transform representations of planning and scheduling problems, applications for visualising, benchmarking and comparing
    planners or other types of tools, etc.


Specific guidelines and submission instructions are provided for [Tools](/calls/tools_papers_call) submissions.


## Topic Tags

Topics are terms that describe the context that motivates the research questions and accompanying assumptions that are 
addressed in the paper. ICAPS 2025 invites papers addressing the following topics:

- **Abstract Models** _of Planning and Scheduling_
  - Planning and scheduling problems are described rigorously in terms of a suitably defined axiomatic theory. The axioms
  of this theory provide the building blocks to establish the existence (or non-existence) of solutions. This topic 
  encompasses research formulated on frameworks such as, but not exclusively, PDDL, RDDL, Markov Decision Processes, Transition 
  Systems and Automata, Graph Theory, etc. and methodologies as diverse as Heuristic Search and Dynamic Programming, Boolean 
  Satisfiability, Discrete and Continuous Optimisation, etc.
- **Machine Learning** _in Planning and Scheduling_
  - Applications of the theory and algorithms of Machine Learning to the representation and solution of planning and 
  scheduling problems. This is a wide-ranging topic that covers Reinforcement Learning, Representation Learning, integrations
  of or with Large Language Model technology, etc. We expect submissions to this topic to formulate their assumptions in a 
  rigorous fashion, connected to existing mathematical formulations of planning and scheduling problems. Novel formulations
  are welcome, and in that case, it will be expected that the submission contains an articulate and compelling argument
  based on capabilities that are either absent or limited in existing methodologies and formulations.
- _Planning and Scheduling in_ **Robotics and Control Theory** in _Planning and Scheduling_ 
  - This topic addresses approaches to planning and scheduling where the theory used to represent problems and
  reason about the existence of solutions is an "intuitive" one, that models with some degree of fidelity the constraints
  that agent(s) physical form and actions are subject to in the real world. Methodologies specific to this topic are
  (nonlinear) mathematical programming, unconstrained optimisation, model predictive control methods, geometric reasoning, 
  amongst many others. 
- **Human-aware** _Planning and Scheduling_
  - Submissions made to this topic discuss frameworks and algorithms that address applications of planning and scheduling 
  in which a human is in or on the loop. This requires to adopt and reason about assumptions that take into account quantitative
  or qualitative aspects of human cognition, psychology, user interface design, and other multi-disciplinary topics.
  We expect submissions to ICAPS to present these assumptions in a rigorous and mathematical fashion, connected
  with existing work on abstract models of planning problems, robotics and control theory.
- **Applications** _of Planning and Scheduling_ (Special Topic) 
  - Applications of planning and scheduling technologies in Engineering, Management in enterprise environments. Submissions to 
    this topic are processed via a slightly different workflow that acknowledges the gaps
    between academic research and applied engineering in a commercial enterprise.
- **Knowledge Engineering** _in Planning and Scheduling_ (Community Topic)
  - Knowledge Engineering for Planning and Scheduling is the collection of processes involving (i) the acquisition, 
  validation, verification, and maintenance of models of planning problems, (ii) the selection and optimisation of appropriate 
  planning and scheduling technology, and (iii) the integration of (i) and (ii) to deliver automated planning and 
  scheduling applications. Submissions to this topic are expected to be of a diverse nature, as befits the wide range
  of representations of planning and scheduling problems that are known in the literature. It is desirable that submissions
  establish where applicable a crisp differentiation between persistent knowledge (e.g. domain models) and the 
  specification of particular scenarios.


## Subject Tags

We use the _subject_ as a shorthand of _subject matter_, that is the thing that is being written about, discussed,
or shown. Subject tags are thus the descriptors that spell out the background and specific mathematical and algorithmic
frameworks that are addressed in a submission. We have borrowed the structure of the ontology used by IJCAI 2024, adding 
to it some terms we found on AAAI 2024 classification that were not used by IJCAI, as well as a few subjects we felt were 
missing or could be made more precise.
We also include a number of topics outside the "Planning and Scheduling" IJCAI category which we think are very closely
related and may help authors to better describe the subjects covered by their submission.

Please let us know if you would like to add a new category by writing [to our mailing list](mailto:icaps25pc@googlegroups.com).
We **look forward to expand** on this list up until the ICAPS 2025 submission site
is open for submissions.

We want to stress that submissions which **do not** refer to **one or more** of the subject tags under the "Planning and
Scheduling" category will be flagged automatically for **desk rejection**.

### Humans and AI
 -  HAI: Human-aware planning and behaviour prediction
 -  HAI: Planning and decision support for human-machine teams
### Knowledge Representation and Reasoning
 -  KRR: Reasoning about actions
 -  KRR: Reasoning about knowledge and belief
### Machine Learning
 -  ML: Reinforcement learning
 -  ML: Representation learning
### Planning and Scheduling
 -  PS: Activity and plan recognition
 -  PS: Applications
 -  PS: Learning for planning and scheduling
 -  PS: Mixed discrete/continuous planning
 -  PS: Model-based reasoning
 -  PS: Optimisation of spatio-temporal systems
 -  PS: Plan execution and monitoring
 -  PS: Planning under uncertainty
 -  PS: Planning with large language models
 -  PS: Planning with Markov decision process models (MDPs, POMDPs)
 -  PS: Re-planning and plan repair
 -  PS: Routing
 -  PS: Scheduling
 -  PS: Scheduling under uncertainty
 -  PS: Temporal planning
 -  PS: Distributed and multi-agent planning
 -  PS: Planning with Hierarchical Task Networks (HTN)
 -  PS: Classical (fully-observable, deterministic) planning
 -  PS: Fully observable non-deterministic planning
 -  PS: Partially observable planning
 -  PS: Planning with incomplete models
 -  PS: Real-time planning
 -  PS: Theoretical foundations of planning
 -  PS: Multi-agent path-finding
 -  PS: Generalised planning
 -  PS: Search in planning and scheduling
 -  PS: SAT, SMT and CP
 -  PS: Local search and evolutionary programming
 -  PS: Sub-modular and gradient-free optimisation
 -  PS: Mathematical programming
 -  PS: Infinite-horizon optimal control problems
 -  PS: Model checking for trust, safety and robustness
### Robotics
 -  ROB: Motion and path planning
### Uncertainty in AI
 -  UAI: Sequential decision making
 -  UAI: Uncertainty representations