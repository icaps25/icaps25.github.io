---
title: "MiniZinc: Constraint Modelling for Planning and Scheduling"
date: 2025-04-13T00:00:00+00:00
draft: false
---

# Tutorial: MiniZinc - Constraint Modelling for Planning and Scheduling

[MiniZinc](https://www.minizinc.org) is a high-level, solver-independent modelling language for constraint programming. It allows users to express complex combinatorial problems declaratively and succinctly. MiniZinc models can be solved using a wide range of backends, including constraint programming, mixed integer programming, and SAT-based solvers, making it an ideal tool for both research and practical applications.

This tutorial will introduce participants to the fundamentals of constraint modelling with MiniZinc. We will begin with the basics of writing and solving MiniZinc models, using simple hands-on examples that participants can follow directly in the web-based [MiniZinc Playground](https://play.minizinc.dev). We will then demonstrate how to represent simple planning problems, showing how formulations in PDDL can be mapped into MiniZinc models. While MiniZinc (and its underlying solvers) may not be the most efficient choice for such problems, we will explore how extending these examples with richer side constraints and optimization objectives can make constraint-based approaches highly effective. Finally, we will look at modelling and solving scheduling problems, including scenarios involving optional tasks and resource constraints.

## Presenters

**Guido Tack** is an Associate Professor in the Department of Data Science and AI at Monash University and one of the core developers of the MiniZinc modelling language and toolchain. His research focuses on modelling languages, constraint solving technology, and combinatorial optimization. He has extensive experience teaching constraint modelling and optimization to both academic and industrial audiences.

**Peter J. Stuckey** is a Professor in the Department of Data Science and AI at Monash University and a pioneer in constraint programming, the science of modelling and solving complex combinatorial problems. His research interests include discrete optimization; programming languages, in particular declarative programming languages;  constraint solving algorithms; bioinformatics; and constraint-based graphics.
