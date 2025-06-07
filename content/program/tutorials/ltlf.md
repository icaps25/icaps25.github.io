---
title: "LTLf Synthesis and Planning Under Unreliable Input"
date: 2025-04-13T00:00:00+00:00
draft: false
---

# Tutorial on LTLf Synthesis and Planning Under Unreliable Input

ICAPS 2025 Tutorial, Melbourne, Australia, Date: 10-11 November, 2025

## Abstract
We revisit the problem of realizing strategies for Linear Temporal Logics
on Finite traces specification (e.g., LTLf) in nondeterministic environments. In particular, we
consider the case in which certain inputs (responses) from the environment are not fully reliable.
One way to address this unreliability is to disregard the unreliable input completely and not
consider it in choosing the next output. This is related to planning/synthesis under partial
observability. However, this might be too radical and could drastically reduce the agent's ability
to operate, considering that the unreliability we are considering is only occasional. Our objective
instead is to ensure that the system maintains functionality and adheres to critical specifications,
despite uncertain and unreliable inputs. If the uncertainty is quantifiable, we could rely on
probabilities, turning to MDPs or Stochastic Games. Yet, “software does not necessarily conform
neatly to probabilistic distributions, making it difficult to apply statistical models or predictions
commonly used in other scientific disciplines.” Here, we aim at exploring a novel synthesis
method to manage the potential unreliability of input variables obtained without relying on
probabilities. The crux of our approach is not to give up on using input variables that might be
unreliable, but to complement them with the guarantee that even when they behave badly, some
safeguard conditions are maintained. Specifically, we consider two models simultaneously, a
brave model where all input variables are considered reliable (as usual in synthesis/planning),
and a cautious one where unreliable input is projected out and discarded. Using these two
models, we devise a strategy that simultaneously fulfils the task objectives completely if the input
variables behave correctly and maintains certain fallback conditions even if the unreliable input
variables behave wrongly.

The tutorial will revisit synthesis and planning for temporally extended goals under full
observability, partial observability, and unreliable inputs. It will adopt an automata-theoretic
approach and consider several Linear Temporal Logics on Finite traces, including LTLf, PPLTL,
and second-order quantified LTLf (QLTLf).

## Tutorial Website

Accessible [TBD]().

## Authors
[Giuseppe De Giacomo](https://www.cs.ox.ac.uk/people/giuseppe.degiacomo/), University of Oxford, UK

[Shufang Zhu](https://shufang-zhu.github.io/), University of Liverpool, UK

