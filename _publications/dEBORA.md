---
title: "dEBORA: Efficient Bilevel Optimization-based low-Rank Adaptation"
collection: publications
permalink: /publication/dEBORA
year: 2025
date: 2025-01-01
authors: Emanuele Zangrando, Sara Venturini, Francesco Rinaldi, Francesco Tudisco
venue: 'International Conference on Learning Representations (ICLR)'
abstract: Low-rank adaptation methods are a popular approach for parameter-efficient fine-tuning of large-scale neural networks. However, selecting the optimal rank for each layer remains a challenging problem that significantly affects both performance and efficiency. In this paper, we introduce a novel bilevel optimization strategy that simultaneously trains both matrix and tensor low-rank adapters, dynamically selecting the optimal rank for each layer. Our method avoids the use of implicit differentiation in the computation of the hypergradient, and integrates a stochastic away-step variant of the Frank-Wolfe algorithm, eliminating the need for projection and providing identifiability guarantees of the optimal rank structure. This results in a highly efficient and cost-effective training scheme that adaptively allocates the parameter budget across the network layers. On top of a detailed theoretical analysis of the method, we provide different numerical experiments showcasing its effectiveness.
paperurl: 'https://openreview.net/pdf?id=5M0ic2RxQZ'
---

Links: [Paper](https://openreview.net/pdf?id=5M0ic2RxQZ) 

<h3>Please cite this paper as:</h3>

``` 
@inproceedings{
zangrando2025debora,
title={d{EBORA}: Efficient Bilevel Optimization-based low-Rank Adaptation},
author={Emanuele Zangrando and Sara Venturini and Francesco Rinaldi and Francesco Tudisco},
booktitle={The Thirteenth International Conference on Learning Representations},
year={2025},
url={https://openreview.net/forum?id=5M0ic2RxQZ}
}
```
