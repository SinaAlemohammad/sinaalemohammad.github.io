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

One-Bit Compressed Sensing
======

Originally proposed by [Boufounos and Baraniuk](https://ieeexplore.ieee.org/abstract/document/4558487), One-Bit Compressed Sensing focus on the sparse solution of the underdetermined 
