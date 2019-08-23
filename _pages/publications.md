---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


___
### Refereed journal articles

[4] Christian Kahle, Kei Fong Lam, Jonas Latz, Elisabeth Ullmann (2019)  
**Bayesian parameter identification in Cahn-Hilliard models for biological growth**  
SIAM/ASA J. Uncertain. Quantif. 7(2), p. 526-552, DOI. (Abstract, .bib, arXiv)  

[3] Jonas Latz, Marvin Eisenberger, Elisabeth Ullmann (2019)  
**Fast Sampling of parameterised Gaussian random fields**  
Comput. Methods in Appl. Mech. Engrg. 348, p. 978-1012, DOI. (Abstract, .bib, arXiv)  

[2] Jonas Latz, Iason Papaioannou, Elisabeth Ullmann (2018)  
**Multilevel Sequential² Monte Carlo for Bayesian Inverse Problems**  
J. Comput. Phys. 368, p. 154-178, DOI. (Abstract, .bib, arXiv)  
<details>
<summary>Abstract</summary>

The identification of parameters in mathematical models using noisy observations is a common task in uncertainty quantification. We employ the framework of Bayesian inversion: we combine monitoring and observational data with prior information to estimate the posterior distribution of a parameter. Specifically, we are interested in the distribution of a diffusion coefficient of an elliptic PDE. In this setting, the sample space is high-dimensional, and each sample of the PDE solution is expensive. To address these issues we propose and analyse a novel Sequential Monte Carlo (SMC) sampler for the approximation of the posterior distribution. Classical, single-level SMC constructs a sequence of measures, starting with the prior distribution, and finishing with the posterior distribution. The intermediate measures arise from a tempering of the liklihood, or, equivalently, a rescaling of the noise. The resolution of the PDE discretisation is fixed. In contrast, our estimator employs a hierarchy of PDE discretisations to decrease the computational cost. We construct a sequence of intermediate measures by decreasing the temperature or by increasing the discretisation level at the same time. This idea builds on and generalises the multi-resolution sampler proposed in [P.S. Koutsourelakis, J. Comput. Phys., 228 (2009), pp. 6184-6211] where a bridging scheme is used to transfer samples from coarse to fine discretisation levels. Importantly, our choice between tempering and bridging is fully adaptive. We present numerical experiments in 2D space, comparing our estimator to single-level SMC and the multi-resolution sampler.
</details>


___

### Refereed book chapters

[1] Matthieu Bulté, Jonas Latz, Elisabeth Ullmann (2018)  
**A practical example for the non-linear Bayesian filtering of model parameters**  
*Accepted.* (github, Abstract, .bib, arXiv) 
<details>
<summary>Abstract</summary>

In this tutorial we consider the non-linear Bayesian filtering of static parameters in a time-dependent model. We outline the theoretical background and discuss appropriate solvers. We focus on particle-based filters and present Sequential Importance Sampling (SIS) and Sequential Monte Carlo (SMC). Throughout the paper we illustrate the concepts and techniques with a practical example using real-world data. The task is to estimate the gravitational acceleration of the Earth g by using observations collected from a simple pendulum. Importantly, the particle filters enable the adaptive updating of the estimate for g as new observations become available. For tutorial purposes we provide the data set and a Python implementation of the particle filters.
</details>

