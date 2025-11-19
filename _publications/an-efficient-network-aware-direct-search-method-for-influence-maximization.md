---
title: "An efficient network-aware direct search method for influence maximization"
collection: publications
permalink: /publication/an-efficient-network-aware-direct-search-method-for-influence-maximization.
year: 2025
date: 2025-11-13
authors: Matteo Bergamaschi, Sara Venturini, Francesco Rinaldi, Francesco Tudisco
venue: 'Journal of Complex Networks'
abstract: Influence Maximization (IM) is a pivotal concept in social network analysis, involving the identification of influential nodes within a network to maximize the number of influenced nodes, and has a wide variety of applications that range from viral marketing and information dissemination to public health campaigns. IM can be modeled as a combinatorial optimization problem with a black-box objective function, where the goal is to select \$ B \$ seed nodes that maximize the expected influence spread. Direct search methods, which do not require gradient information, are well-suited for such problems. Unlike gradient-based approaches, direct search algorithms, in fact, only evaluate the objective function at a suitably chosen set of trial points around the current solution to guide the search process. However, these methods often suffer from scalability issues due to the high cost of function evaluations, especially when applied to combinatorial problems like IM. This work, therefore, proposes the Network-aware Direct Search (NaDS) method, an innovative direct search approach that integrates the network structure into its neighborhood formulation and is used to tackle a mixed-integer programming formulation of the IM problem, the so-called General Information Propagation model. We tested our method on large-scale networks, comparing it to existing state-of-the-art approaches for the IM problem, including direct search methods and various greedy techniques and heuristics. The results of the experiments empirically confirm the assumptions underlying NaDS, demonstrating that exploiting the graph structure of the IM problem in the algorithmic framework can significantly improve its computational efficiency in the considered context.
paperurl: 'https://academic.oup.com/comnet/article/13/6/cnaf042/8322444'
---

Links: [Paper]( https://academic.oup.com/comnet/article/13/6/cnaf042/8322444) [ArXiv](https://arxiv.org/abs/2508.12164) [Code]( https://github.com/Berga53/Network-aware-Direct-Search)

<h3>Please cite this paper as:</h3>

``` 
@article{10.1093/comnet/cnaf042,
    author = {Bergamaschi, Matteo and Venturini, Sara and Tudisco, Francesco and Rinaldi, Francesco},
    title = {An efficient network-aware direct search method for influence maximization},
    journal = {Journal of Complex Networks},
    volume = {13},
    number = {6},
    pages = {cnaf042},
    year = {2025},
    month = {11},
    abstract = {Influence Maximization (IM) is a pivotal concept in social network analysis, involving the identification of influential nodes within a network to maximize the number of influenced nodes, and has a wide variety of applications that range from viral marketing and information dissemination to public health campaigns. IM can be modeled as a combinatorial optimization problem with a black-box objective function, where the goal is to select \$ B \$ seed nodes that maximize the expected influence spread. Direct search methods, which do not require gradient information, are well-suited for such problems. Unlike gradient-based approaches, direct search algorithms, in fact, only evaluate the objective function at a suitably chosen set of trial points around the current solution to guide the search process. However, these methods often suffer from scalability issues due to the high cost of function evaluations, especially when applied to combinatorial problems like IM. This work, therefore, proposes the Network-aware Direct Search (NaDS) method, an innovative direct search approach that integrates the network structure into its neighborhood formulation and is used to tackle a mixed-integer programming formulation of the IM problem, the so-called General Information Propagation model. We tested our method on large-scale networks, comparing it to existing state-of-the-art approaches for the IM problem, including direct search methods and various greedy techniques and heuristics. The results of the experiments empirically confirm the assumptions underlying NaDS, demonstrating that exploiting the graph structure of the IM problem in the algorithmic framework can significantly improve its computational efficiency in the considered context.},
    issn = {2051-1329},
    doi = {10.1093/comnet/cnaf042},
    url = {https://doi.org/10.1093/comnet/cnaf042},
    eprint = {https://academic.oup.com/comnet/article-pdf/13/6/cnaf042/65284922/cnaf042.pdf},
}
```

