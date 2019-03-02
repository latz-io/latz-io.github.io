---
title: "Fast Sampling of parameterised Gaussian random fields"
collection: publications
permalink: _publications/2019-02-15-paper-title-number-3
excerpt: ' Gaussian random fields are popular models for spatially varying uncertainties, arising for instance in geotechnical engineering, hydrology or image processing. A Gaussian random field is fully characterised by'
date: 2019-02-15
venue: 'Comput. Methods in Appl. Mech. Engrg.'
paperurl: 'https://doi.org/10.1016/j.cma.2019.02.003'
citation: 'Jonas Latz, Marvin Eisenberger, Elisabeth Ullmann. (2019). &quot;Fast Sampling of parameterised Gaussian random fields.&quot; <i>Comput. Methods in Appl. Mech. Engrg.</i>. 348, p. 978-1012.'
---

_Abstract:_  Gaussian random fields are popular models for spatially varying uncertainties, arising for instance in geotechnical engineering, hydrology or image processing. A Gaussian random field is fully characterised by its mean function and covariance operator. In more complex models these can also be partially unknown. In this case we need to handle a family of Gaussian random fields indexed with hyperparameters. Sampling for a fixed configuration of hyperparameters is already very expensive due to the nonlocal nature of many classical covariance operators. Sampling from multiple configurations increases the total computational cost severely. In this report we employ parameterised Karhunen-Loève expansions for sampling. To reduce the cost we construct a reduced basis surrogate built from snapshots of Karhunen-Loève eigenvectors. In particular, we consider Matérn-type covariance operators with unknown correlation length and standard deviation. We suggest a linearisation of the covariance function and describe the associated online-offline decomposition. In numerical experiments we investigate the approximation error of the reduced eigenpairs. As an application we consider forward uncertainty propagation and Bayesian inversion with an elliptic partial differential equation where the logarithm of the diffusion coefficient is a parameterised Gaussian random field. In the Bayesian inverse problem we employ Markov chain Monte Carlo on the reduced space to generate samples from the posterior measure. All numerical experiments are conducted in 2D physical space, with non-separable covariance operators, and finite element grids with ~1E4 degrees of freedom. 
