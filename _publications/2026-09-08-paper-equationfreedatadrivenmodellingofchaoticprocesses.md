---
title: "Equation free data-driven modelling of chaotic processes"
collection: publications
category: preprints
permalink: /publication/2026-09-08-paper-equationfreedatadrivenmodellingchaoticprocesses
excerpt: 'This paper propose a method for constructing predictive models of non cyclis physical processes.'
date: 2026-09-08
#venue: 
# slidesurl: 'http://aurorapoggi.github.io/files/slides2.pdf'
paperurl: 'http://aurorapoggi.github.io/files/equationfree.pdf'
citation: 'A. Poggi, M. Martens, H. Brismar, O. Öktem, L. Palmisano (2026). Equation free data-driven modelling of chaotic processes.'
---


The paper introduces a method for constructing predictive models of non-cyclic physical processes directly from time-series data, without assuming an underlying differential equation. Recovering governing equations of a physical system from a single observed noisy time series is a highly ill-posed inverse problem as many possible equations “fit the data” and a small perturbation to the data is likely to result in a very different set of equations.
Rather than recovering the equations, the approach we take in our paper focuses on recovering a surrogate model of the physical system, which is a Markov chain that models its dynamics and thus represents an emergent property.
Renormalization provides a systematic way to construct candidate Markov models at different scales and we also derive criterion for identifying the scale at which the resulting model appropriately represents the underlying dynamics.
The entire framework is stable with respect to perturbations to data, so one can view this as a “regularization” in where renormalization is used to rephrase the initial inverse problem, and then the hyperbolicity criteria are used to single out the appropriate scale where the associated Markov chain constitutes the emergent property of the system that one can stably infer from data.