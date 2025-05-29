---
title: "Data-driven multi-agent modelling of calcium interactions in cell culture: PINN vs Regularized Least-squares"
collection: publications
# category: conferences
category: books
permalink: /publication/2025-05-26-paper-LSM_PINN
excerpt: 'This paper is a methodology for characterization and performance analysis of calcium delivery in a family of cells.'
date: 2025-05-26
#venue: 
# slidesurl: 'http://aurorapoggi.github.io/files/slides2.pdf'
paperurl: 'http://aurorapoggi.github.io/files/arxiv_LSM_PINN.pdf'
citation: 'Aurora Poggi and Giuseppe Alessio D'Inverno and Hjalmar Brismar and Ozan Öktem and Matthieu Barreau and Kateryna Morozovska (2025). Data-driven multi-agent modelling of calcium interactions in cell culture: PINN vs Regularized Least-squares.'
---

Data-driven discovery of dynamics in biological systems allows for better observation and characterization of processes, such as calcium signaling in cell culture. Recent advancements in techniques allow the exploration of previously unattainable insights of dynamical systems, such as the Sparse Identification of Non-Linear Dynamics (SINDy), overcoming the limitations of more classic methodologies. The latter requires some prior knowledge of an effective library of candidate terms, which is not realistic for a real case study. Using inspiration from fields like traffic density estimation and control theory, we propose a methodology for characterization and performance analysis of calcium delivery in a family of cells. In this work, we compare the performance of the Constrained Regularized Least-Squares Method (CRLSM) and Physics-Informed Neural Networks (PINN) for system identification and parameter discovery for governing ordinary differential equations (ODEs). The CRLSM achieves a fairly good parameter estimate and a good data fit when using the learned parameters in the Consensus problem. On the other hand, despite the initial hypothesis, PINNs fail to match the CRLSM performance and, under the current configuration, do not provide fair parameter estimation. However, we have only studied a limited number of PINN architectures, and it is expected that additional hyperparameter tuning, as well as uncertainty quantification, could significantly improve the performance in future works.