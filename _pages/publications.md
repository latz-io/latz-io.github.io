---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Preprints

[5] Jonas Latz (2019)  
On the well-posedness of Bayesian inverse problems  
Under review. ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/La19.bib), [arXiv](https://arxiv.org/abs/1902.10257))  
<details>
<summary>Abstract</summary>

The subject of this article is the introduction of a weaker concept of well-posedness of Bayesian inverse problems. The conventional concept of ("Lipschitz") well-posedness in [Stuart 2010, Acta Numerica 19, pp. 451-559] is difficult to verify in practice, especially when considering blackbox models, and probably too strong in many contexts. Our concept replaces the Lipschitz continuity of the posterior measure in the Hellinger distance by just continuity. This weakening is tolerable, since the continuity is in general only used as a stability criterion. The main result of this article is a proof of well-posedness for a large class of Bayesian inverse problems, where very little or no information about the underlying model is available. It includes any Bayesian inverse problem arising when observing finite-dimensional data perturbed by additive, non-degenerate Gaussian noise. Moreover, well-posedness with respect to other probability metrics is investigated, including weak convergence, total variation, Wasserstein, and also the Kullback-Leibler divergence.
</details>

___
### Refereed journal articles

[4] Christian Kahle, Kei Fong Lam, Jonas Latz, Elisabeth Ullmann (2019)  
**Bayesian parameter identification in Cahn-Hilliard models for biological growth**  
SIAM/ASA J. Uncertain. Quantif. 7(2), p. 526-552, [DOI](https://doi.org/10.1137/18M1210034). ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/KLLU19.bib), [arXiv](https://arxiv.org/abs/1805.03304))  
<details>
<summary>Abstract</summary>

We consider the inverse problem of parameter estimation in a diffuse interface model for tumor growth. The model consists of a fourth-order Cahn-Hilliard system and contains three phenomenological parameters: the tumor proliferation rate, the nutrient consumption rate, and the chemotactic sensitivity. We study the inverse problem within the Bayesian framework and construct the likelihood and noise for two typical observation settings. One setting involves an infinite-dimensional data space where we observe the full tumor. In the second setting we observe only the tumor volume; hence the data space is finite-dimensional. We show the well-posedness of the posterior measure for both settings, building upon and improving the analytical results in [C. Kahle and K. F. Lam, Appl. Math. Optim., (2018)]. A numerical example involving synthetic data is presented in which the posterior measure is numerically approximated by the sequential Monte Carlo approach with tempering.
</details>

[3] Jonas Latz, Marvin Eisenberger, Elisabeth Ullmann (2019)  
**Fast Sampling of parameterised Gaussian random fields**  
Comput. Methods in Appl. Mech. Engrg. 348, p. 978-1012, [DOI](https://doi.org/10.1016/j.cma.2019.02.003). ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/LEU19.bib), [arXiv](https://arxiv.org/abs/1804.11157))  
<details>
<summary>Abstract</summary>

Gaussian random fields are popular models for spatially varying uncertainties, arising for instance in geotechnical engineering, hydrology or image processing. A Gaussian random field is fully characterised by its mean function and covariance operator. In more complex models these can also be partially unknown. In this case we need to handle a family of Gaussian random fields indexed with hyperparameters. Sampling for a fixed configuration of hyperparameters is already very expensive due to the nonlocal nature of many classical covariance operators. Sampling from multiple configurations increases the total computational cost severely. In this report we employ parameterised Karhunen-Loève expansions for sampling. To reduce the cost we construct a reduced basis surrogate built from snapshots of Karhunen-Loève eigenvectors. In particular, we consider Matérn-type covariance operators with unknown correlation length and standard deviation. We suggest a linearisation of the covariance function and describe the associated online-offline decomposition. In numerical experiments we investigate the approximation error of the reduced eigenpairs. As an application we consider forward uncertainty propagation and Bayesian inversion with an elliptic partial differential equation where the logarithm of the diffusion coefficient is a parameterised Gaussian random field. In the Bayesian inverse problem we employ Markov chain Monte Carlo on the reduced space to generate samples from the posterior measure. All numerical experiments are conducted in 2D physical space, with non-separable covariance operators, and finite element grids with ~1E4 degrees of freedom.
</details>

[2] Jonas Latz, Iason Papaioannou, Elisabeth Ullmann (2018)  
**Multilevel Sequential² Monte Carlo for Bayesian Inverse Problems**  
J. Comput. Phys. 368, p. 154-178, [DOI](https://doi.org/10.1016/j.jcp.2018.04.014). ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/LPU18.bib), [arXiv](https://arxiv.org/abs/1709.09763))  
<details>
<summary>Abstract</summary>

The identification of parameters in mathematical models using noisy observations is a common task in uncertainty quantification. We employ the framework of Bayesian inversion: we combine monitoring and observational data with prior information to estimate the posterior distribution of a parameter. Specifically, we are interested in the distribution of a diffusion coefficient of an elliptic PDE. In this setting, the sample space is high-dimensional, and each sample of the PDE solution is expensive. To address these issues we propose and analyse a novel Sequential Monte Carlo (SMC) sampler for the approximation of the posterior distribution. Classical, single-level SMC constructs a sequence of measures, starting with the prior distribution, and finishing with the posterior distribution. The intermediate measures arise from a tempering of the liklihood, or, equivalently, a rescaling of the noise. The resolution of the PDE discretisation is fixed. In contrast, our estimator employs a hierarchy of PDE discretisations to decrease the computational cost. We construct a sequence of intermediate measures by decreasing the temperature or by increasing the discretisation level at the same time. This idea builds on and generalises the multi-resolution sampler proposed in [P.S. Koutsourelakis, J. Comput. Phys., 228 (2009), pp. 6184-6211] where a bridging scheme is used to transfer samples from coarse to fine discretisation levels. Importantly, our choice between tempering and bridging is fully adaptive. We present numerical experiments in 2D space, comparing our estimator to single-level SMC and the multi-resolution sampler.
</details>


___

### Refereed book chapters

[1] Matthieu Bulté, Jonas Latz, Elisabeth Ullmann (2018)  
**A practical example for the non-linear Bayesian filtering of model parameters**  
*Accepted.* ([github](https://github.com/BayesianLearning/PenduSMC), [.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/BLU18.bib), [arXiv](https://arxiv.org/abs/1807.08713)) 
<details>
<summary>Abstract</summary>

In this tutorial we consider the non-linear Bayesian filtering of static parameters in a time-dependent model. We outline the theoretical background and discuss appropriate solvers. We focus on particle-based filters and present Sequential Importance Sampling (SIS) and Sequential Monte Carlo (SMC). Throughout the paper we illustrate the concepts and techniques with a practical example using real-world data. The task is to estimate the gravitational acceleration of the Earth g by using observations collected from a simple pendulum. Importantly, the particle filters enable the adaptive updating of the estimate for g as new observations become available. For tutorial purposes we provide the data set and a Python implementation of the particle filters.
</details>

