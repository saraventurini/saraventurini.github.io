---
title: "Relax and penalize: a new bilevel approach to mixed-binary hyperparameter optimization"
collection: publications
permalink: /publication/Relax-and-penalize
year: 2025
date: 2025-01-01
authors: Sara Venturini, Marianna De Santis, Jordan Frecon-Deloir, Martin Schmidt, Francesco Rinaldi*, Saverio Salzo* 
venue: 'Transactions on Machine Learning Research'
abstract: In recent years, bilevel approaches have become very popular to efficiently estimate high-dimensional hyperparameters of machine learning models. However, to date, binary parameters are handled by continuous relaxation and rounding strategies, which could lead to inconsistent solutions. In this context, we tackle the challenging optimization of mixed-binary hyperparameters by resorting to an equivalent continuous bilevel reformulation based on an appropriate penalty term. We propose an algorithmic framework that, under suitable assumptions, is guaranteed to provide mixed-binary solutions. Moreover, the generality of the method allows to safely use existing continuous bilevel solvers within the proposed framework. We evaluate the performance of our approach for two specific machine learning problems, i.e., the estimation of the group-sparsity structure in regression problems and the data distillation problem. The reported results show that our method is competitive with state-of-the-art approaches based on relaxation and rounding.
paperurl: 'https://openreview.net/pdf?id=A1R1cQ93Cb'
---

Links: [Paper](https://openreview.net/pdf?id=A1R1cQ93Cb) [ArXiv](https://arxiv.org/abs/2308.10711) [Code](https://github.com/saraventurini/Relax-and-penalize) 

<h3>Please cite this paper as:</h3>

``` 
@article{
venturini2025relax,
title={Relax and penalize: a new bilevel approach to mixed-binary hyperparameter optimization},
author={Sara Venturini and Marianna De Santis and Jordan Patracone and Martin Schmidt and Francesco Rinaldi and Saverio Salzo},
journal={Transactions on Machine Learning Research},
issn={2835-8856},
year={2025},
url={https://openreview.net/forum?id=A1R1cQ93Cb},
note={}
}
```
