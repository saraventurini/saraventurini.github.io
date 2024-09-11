---
title: "Learning the Right Layers: a Data-Driven Layer-Aggregation Strategy for Semi-Supervised Learning on Multilayer Graphs"
collection: publications
permalink: /publication/Learning-the-Right-Layers-for-Multilayer-Graph-Classification
year: 2023
date: 2023-07-23
authors: Sara Venturini, Andrea Cristofari, Francesco Rinaldi, Francesco Tudisco
venue: International Conference on Machine Learning (ICML)
abstract: Clustering  (or community detection) on multilayer graphs poses several additional complications with respect to standard graphs as different layers may be characterized by different structures and types of information. One of the major challenges is to establish the extent to which each layer contributes to the cluster assignment in order to effectively take advantage of the multilayer structure and improve upon the classification obtained using the individual layers or their union. However, making an informed a-priori assessment about the clustering information content of the layers can be very complicated. In this work, we assume a semi-supervised learning setting, where the class of a small percentage of nodes is initially provided,  and we propose a parameter-free Laplacian-regularized model that learns an optimal nonlinear combination of the different layers from the available input labels. The learning algorithm is based on a Frank-Wolfe optimization scheme with inexact gradient, combined with a modified Label Propagation iteration. We provide a detailed convergence analysis of the algorithm and extensive experiments on synthetic and real-world datasets, showing that the proposed method  compares favourably with a variety of baselines and  outperforms each individual layer when used in isolation.
paperurl: 'https://arxiv.org/abs/2306.00152'
---

Links: [Paper](https://proceedings.mlr.press/v202/venturini23a/venturini23a.pdf) [ArXiv](https://arxiv.org/abs/2306.00152) [Code](https://github.com/saraventurini/Learning-the-right-layers-on-multilayer-graphs) [Slides](https://saraventurini.github.io/files/ICML23_slides.pdf) [Poster](https://saraventurini.github.io/files/ICML23_poster.pdf)

<h3>Please cite this paper as:</h3>

```

@InProceedings{venturini2023learning,
  title = 	 {Learning the Right Layers a Data-Driven Layer-Aggregation Strategy for Semi-Supervised Learning on Multilayer Graphs},
  author =       {Venturini, Sara and Cristofari, Andrea and Rinaldi, Francesco and Tudisco, Francesco},
  booktitle = 	 {Proceedings of the 40th International Conference on Machine Learning},
  pages = 	 {35006--35023},
  year = 	 {2023},
  editor = 	 {Krause, Andreas and Brunskill, Emma and Cho, Kyunghyun and Engelhardt, Barbara and Sabato, Sivan and Scarlett, Jonathan},
  volume = 	 {202},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {23--29 Jul},
  publisher =    {PMLR},
  pdf = 	 {https://proceedings.mlr.press/v202/venturini23a/venturini23a.pdf},
  url = 	 {https://proceedings.mlr.press/v202/venturini23a.html},
  abstract = 	 {Clustering (or community detection) on multilayer graphs poses several additional complications with respect to standard graphs as different layers may be characterized by different structures and types of information. One of the major challenges is to establish the extent to which each layer contributes to the cluster assignment in order to effectively take advantage of the multilayer structure and improve upon the classification obtained using the individual layers or their union. However, making an informed a-priori assessment about the clustering information content of the layers can be very complicated. In this work, we assume a semi-supervised learning setting, where the class of a small percentage of nodes is initially provided, and we propose a parameter-free Laplacian-regularized model that learns an optimal nonlinear combination of the different layers from the available input labels. The learning algorithm is based on a Frank-Wolfe optimization scheme with inexact gradient, combined with a modified Label Propagation iteration. We provide a detailed convergence analysis of the algorithm and extensive experiments on synthetic and real-world datasets, showing that the proposed method compares favourably with a variety of baselines and outperforms each individual layer when used in isolation.}
}
```

