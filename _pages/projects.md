---
layout: archive
title: ""
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

In Recent years, the rapid development of high-throughput technologies as well as robust methodologies has significantly boosted the translation of data into knowledge and touched the advancement of almost every scientific field.  So far, there are quite a few methodologies put forward from a diverse range of perspectives; while machine learning view takes advantage of big data, compressed sensing attempts to extract the information from a limited set of observations by exploiting the sparse nature of data. What thoroughly fascinates me about these exciting fields is their common theoretical foundations of multivariate analysis, statistics, optimization, and information theory. In my view, such theoretical foundations are crucial to bridge the gap mentioned above between data and knowledge. Thus, I am keen to solve the real world problems raised in signal and image processing, inverse problems, high dimensional data analysis, machine learning, and computational biology through the utilization and the development of tools empowered by rigorous theoretical substructures.

In the rest of this page you can read about some of the research projects that I have conducted during my undergraduate studies. 

Quantized Matrix Completion
======
Matrix Completion (MC) is of interest in many applications and practical settings. In recent years, theoretical advancements and achievements were reached by many authors in MC and has been utilized in a wide range of application. In this project, I joined two of my colleagues in  Advanced Communications Research Institute at Sharif University of Technology and under supervision of [Prof. Farokh Marvasti](http://acri.sharif.ir/resume/marvasti) to introduce an algorithm for the recovery of a matrix of quantized data with missing information (Quantized MC), i.e., some entries of a given matrix are not assigned (NA), and the rest take quantized values rather than continuous values. We proposed a regularized non-convex cost function composed of a log-likelihood term and a Trace norm term. The Bi-factorization approach and the Augmented Lagrangian Method (ALM) are applied to find the global minimizer of the cost function in order to recover the genuine data.

- Publication : Esmaeili, S., Kayhan, B., Al-E-Mohammad, S., & Marvasti, F. (2018). Recovering Quantized Data with Missing Information Using Bilinear Factorization and Augmented Lagrangian Method. [arXiv:1810.03222](https://arxiv.org/abs/1810.03222) - Submitted to the ACM Transactions on Intelligent Systems and Technology

Multi-Spectral Analysis of Paintings 
======
The recent advances in the image data acquisition technology has helped us to digitalizes the cultural heritages. This vast storages of images have gained the attention of the scholars in the image processing to use computational methods to analyze the artworks. In that event, IEEE signal processing magazine has published 3 special issue regarding this problem so far. I am currently working under supervision of [Prof. Arash Amini](http://sharif.ir/~aamini/) at Sharif University of Technology on an interesting problem in the multi-spectral analysis of paintings as my B.Sc. thesis. We have been provided with the multi-spectral and high-resolution images of Claude Monet’s paintings by the [Lumiere Technology](http://www.lumiere-technology.com/index.htm) . Followed by our analysis on the methods Monet has used in his paintings as an impressionist artist, we have the goal of finding the colors Monet has used in his paintings, that is known to be limited, by sparse non-negative matrix factorization of the spectrum of the image pixels. 

Here is a vidoe of Monet painting "Irises By The Pond" at his garden in 1915! (click on the image)

[![](http://img.youtube.com/vi/BJE4QUNgaeg/0.jpg)](http://www.youtube.com/watch?v=BJE4QUNgaeg"")

One-Bit Compressed Sensing
======
Originally proposed by [Boufounos and Baraniuk](https://ieeexplore.ieee.org/abstract/document/4558487), one-bit compressed sensing focused on finding sparse solution from the signed linear measurements. Up to now, many algorithms has been proposed for an efficient signal recovery. Most of these methods use $\ell_1$ norm as regularization penalty for sparsity constraint that demand higher sample complexity than the original problem, that is using $\ell_0$, but unfortunately minimizing $\ell_0$ is NP-hard. In this project, I proposed a one-bit compressed sensing recovery algorithm using a smooth measure of the $\ell_0$ norm ($S\ell_0$) that yielded to better results than the previous methods, and I am currently working on its convergence analysis under supervision of [Prof. Arash Amini](http://sharif.ir/~aamini/).

![Algorithm performance for the 3 dimensions signal on the unit sphere](https://github.com/SinaAlemohammad/sinaalemohammad.github.io/raw/master/images/sl0.jpg)

Manifold Clustering for Blind Source Separation
======

Blind Source Separation (BSS) is the problem of separating signals which are mixed through an unknown function from a number of observations, without any information about the mixing model. Although it has been mathematically proven that the separation can be done when the mixture is linear by assuming that sources are independent, there is not any general proof for the separability of nonlinearly mixed signals. However, by assuming that the sources are also spatially sparse, we would be able to separate the sources in the nonlinear mixtures. When the mixture is non-linear, the sources are mapped on non-linear intersecting manifolds, and by clustering each manifold, the source separation is done. I proposed a novel robust unsupervised algorithm for clustering the manifolds as a part of my projects in the Digital Signal Processing Laboratory under supervision of [Prof. Massoud Babaie-Zadeh](http://sharif.edu/~mbzadeh/).

![bss](https://github.com/SinaAlemohammad/sinaalemohammad.github.io/raw/master/images/bss.jpg)

System Level Analysis of Glioblastoma Cancer
======
Glioblastoma (GBM), is the most aggressive type of brain tumor with an average life expectancy of less than 15 months. It is a heterogeneous disease with wide alteration in the somatic mutational profiles of different samples. Considering these variations, a large fraction of genes and proteins are being identified as key tumor dependencies but they are proved to be ineffective in stratifying more general properties of disease properties such as reoccurrence and drug resistance and the main cause of mortality in patients diagnosed glioblastoma cancer is the reoccurrence of tumor after treatment of the initial tumor. [Recent studies](https://www.ncbi.nlm.nih.gov/pubmed/27977008) has revealed a recurrent regulatory architecture which genomic alterations lies upstream of some functional master regulators (called tumor checkpoints) of differentially expressed. The tumor checkpoint is not necessarily muted or differentially expressed but their activity is necessary for maintaining the tumor stability and drug resistance of the disease state of the network. Reverse engineering of transcriptional networks using gene expression and analysis based on that enable us to find the so called tumor checkpoints. In this study we have provided a framework to find some candidate tumor checkpoints for the recurrence type of glioblastoma under supervision of [Prof. Babak Khalaj](http://sharif.edu/~khalaj/) and in collaboration with [Prof.Jiguang Wang lab](http://wang-lab.ust.hk/) at Hong Kong University of Science and Technology.

Radiogenomics
======   

Radiogemics is an emerging field in cancer research that focuses on the relationship between the radiomics and genomics data. Until now, the developed models that relate molecular phenotypes or imaging phenotypes to the outcome of cancer are highly inaccurate. The fundamental question is that in order to use a better therapeutic strategy, are we able to find a synergy between the imaging data and genomic data that might lead us the find better models to characterized cancer outcome? I conduced a literature review on the researchers conducted in this field last summer as a junior research assistance in the Laboratory for Bioinformatics and Computational Biology at Hong Kong University of Science and Technology under supervision of [Prof. Weichuan Yu](http://www.ece.ust.hk/~eeyu/)



