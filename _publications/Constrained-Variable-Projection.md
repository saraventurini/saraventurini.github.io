---
title: "Constrained Variable Projection for Structured Problems"
collection: publications
permalink: /publication/Constrained-Variable-Projection
year: 2026
date: 2026-06-01
authors: Emanuele Zangrando, Sara Venturini, Francesco Rinaldi, Francesco Tudsco
venue: 'ArXiv'
abstract: Variable projection is a classical technique for separable nonlinear least-squares problems, in which variables that enter linearly are eliminated exactly, yielding a reduced nonlinear problem. By expressing this framework as a particular instance of a broader class of bilevel optimization problems, we develop a constrained variable-projection framework for data-science models, where the remaining variables are subject to convex constraints and the eliminated variables arise from a lower-level least-squares problem. In particular, by interpreting variable projection as a collapsed bilevel optimization problem, we derive exact reduced-gradient formulas compatible with automatic differentiation and propose a conditional-gradient algorithm for the resulting constrained reduced problem. We establish convergence guarantees under standard smoothness and compactness assumptions, and discuss extensions to structured lower-level variables. Numerical experiments on sparse autoencoding, dictionary learning, blind deconvolution, and few-shot learning suggest that the method can improve wall-clock efficiency and data efficiency relative to natural joint-optimization baselines.
---

Links: [ArXiv](https://arxiv.org/pdf/2606.23939)

<h3>Please cite this paper as:</h3>

``` 
@article{zangrando2026constrained,
  title={Constrained Variable Projection for Structured Problems},
  author={Zangrando, Emanuele and Venturini, Sara and Rinaldi, Francesco and Tudisco, Francesco},
  journal={arXiv preprint arXiv:2606.23939},
  year={2026}
}
```
