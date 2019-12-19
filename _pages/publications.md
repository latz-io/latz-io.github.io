---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Preprints

[12] Fabian Wagner, Jonas Latz, Iason Papaioannou, Elisabeth Ullmann (2019):  **Multilevel Sequential Importance Sampling for Rare Event Estimation.** *Under review.* ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/WLPU19.bib), [arXiv](https://arxiv.org/abs/1909.07680))  
<!-- (<details>
<>(<summary>Abstract</summary>)
<>
<>(The estimation of the probability of rare events is an important task in reliability and risk assessment. We consider failure events that are expressed in terms of a limit state function, which depends on the solution of a partial differential equation (PDE). Since numerical evaluations of PDEs are computationally expensive, estimating such probabilities of failure by Monte Carlo sampling is intractable. More efficient sampling methods from reliability analysis, such as Subset Simulation, are popular, but can still be impracticable if the PDE evaluations are very costly. In this article, we develop a novel, highly efficient estimator for probabilities of rare events. Our method is based on a Sequential Importance sampler using discretizations of PDE-based limit state functions with different accuracies. A twofold adaptive algorithm ensures that we obtain an estimate based on the desired discretization accuracy. In contrast to the Multilevel Subset Simulation estimator of [Ullmann, Papaioannou 2015; SIAM/ASA J. Uncertain. Quantif. 3(1):922-953], our estimator overcomes the nestedness problem. Of particular importance in Sequential Importance sampling algorithms is the correct choice of the MCMC kernel. Instead of the popular adaptive conditional sampling method, we propose a new algorithm that uses independent proposals from an adaptively constructed von Mises-Fischer-Nakagami distribution. The proposed algorithm is applied to test problems in 1D and 2D space, respectively, and is compared to the Multilevel Subset Simulation estimator and to single-level versions of Sequential Importance Sampling and Subset Simulation. 
</details>)-->


[11] Felipe Uribe, Iason Papaioannou, Jonas Latz, Wolfgang Betz, Elisabeth Ullmann, Daniel Straub (2019): **Bayesian inference with subset simulation in spaces of varying dimension.**  *Under review.* ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/UPLBUS19.bib), [full text](https://www.bgu.tum.de/fileadmin/w00blj/era/Papers/2019_uribe_et_al_JCP.pdf))  
<details>
<summary>Abstract</summary>

Uncertainties associated with spatially varying parameters are modeled through random fields discretized into a finite number of random variables. Standard discretization methods, such as the Karhunen-Loève expansion,are based on functional representations that use series expansions for which the truncation order is specified a priori. However, when data is used to update random fields through Bayesian inference, a different truncation order might be necessary to adequately represent the posterior random field. This is an inference problem that not only requires the determination of the often high-dimensional set of coefficients, but also their dimension. In this paper, we develop a sequential algorithm to handle such inference settings, and propose a prior distribution for the dimension parameter that penalizes increasing dimensionality. The method is a variable-dimensional extension of the BUS (Bayesian Updating with Structural reliability methods)approach, combined with subset simulation (SuS). The key idea is to replace the standard Markov chain Monte Carlo (MCMC) algorithm within SuS by a trans-dimensional MCMC sampler that is able to populate the discrete-continuous parameter space. To address this task, we consider two types of MCMC algorithms that operate in a fixed-dimensional saturated parameter space. The performance of the proposed method with both MCMC variants is assessed numerically for two example problems: A 1D cantilever beam with spatially varying flexibility, and a 2D groundwater flow problem with uncertain hydraulic conductivity field.
</details>

___
### Refereed journal articles and book chapters

[10] Jonas Latz (2019): **On the well-posedness of Bayesian inverse problems.** *Accepted in* SIAM/ASA J. Uncertain. Quantif. ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/La19.bib), [arXiv](https://arxiv.org/abs/1902.10257))  
<details>
<summary>Abstract</summary>

The subject of this article is the introduction of a new concept of well-posedness of Bayesian inverse problems. The conventional concept of (Lipschitz, Hellinger) well-posedness in [Stuart 2010, Acta Numerica 19, pp. 451-559] is difficult to verify in practice and may be inappropriate in some contexts. Our concept simply replaces the Lipschitz continuity of the posterior measure in the Hellinger distance by continuity in an appropriate distance between probability measures. Aside from the Hellinger distance, we investigate well-posedness with respect to  weak convergence, the total variation distance, the Wasserstein distance, and also the Kullback--Leibler divergence. We demonstrate that the weakening to continuity is tolerable and that the generalisation to other distances is important. The main results of this article are proofs of well-posedness with respect to some of the aforementioned distances for large classes of Bayesian inverse problems. Here, little or no information about the underlying model is necessary; making these results particularly interesting for practitioners using black-box models. We illustrate our findings with numerical examples motivated from machine learning and image processing.
</details>


[9] Ionuţ-Gabriel Farcaş, Jonas Latz, Elisabeth Ullmann, Tobias Neckel, Hans-Joachim Bungartz (2019): **Multilevel Adaptive Sparse Leja Approximations for Bayesian Inverse Problems.** *Accepted in* SIAM J. Sci. Comput. ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/FLUNB19.bib), [arXiv](https://arxiv.org/abs/1904.12204))  
<details>
<summary>Abstract</summary>

Deterministic interpolation and quadrature methods are often unsuitable to address Bayesian inverse problems depending on computationally expensive forward mathematical models. While interpolation may give precise posterior approximations, deterministic quadrature is usually unable to efficiently investigate an informative and thus concentrated likelihood. This leads to a large number of required expensive evaluations of the mathematical model. To overcome these challenges, we formulate and test a multilevel adaptive sparse Leja algorithm. At each level, adaptive sparse grid interpolation and quadrature are used to approximate the posterior and perform all quadrature operations, respectively. Specifically, our algorithm uses coarse discretizations of the underlying mathematical model to investigate the parameter space and to identify areas of high posterior probability. Adaptive sparse grid algorithms are then used to place points in these areas, and ignore other areas of small posterior probability. The points are weighted Leja points. As the model discretization is coarse, the construction of the sparse grid is computationally efficient. On this sparse grid, the posterior measure can be approximated accurately with few expensive, fine model discretizations. The efficiency of the algorithm can be enhanced further by exploiting more than two discretization levels. We apply the proposed multilevel adaptive sparse Leja algorithm in numerical experiments involving elliptic inverse problems in 2D and 3D space, in which we compare it with Markov chain Monte Carlo sampling and a standard multilevel approximation.
</details>


[8] Christian Kahle, Kei Fong Lam, Jonas Latz, Elisabeth Ullmann (2019): **Bayesian parameter identification in Cahn-Hilliard models for biological growth.** SIAM/ASA J. Uncertain. Quantif. 7(2), p. 526-552, [doi](https://doi.org/10.1137/18M1210034). ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/KLLU19.bib), [arXiv](https://arxiv.org/abs/1805.03304))  
<details>
<summary>Abstract</summary>

We consider the inverse problem of parameter estimation in a diffuse interface model for tumor growth. The model consists of a fourth-order Cahn-Hilliard system and contains three phenomenological parameters: the tumor proliferation rate, the nutrient consumption rate, and the chemotactic sensitivity. We study the inverse problem within the Bayesian framework and construct the likelihood and noise for two typical observation settings. One setting involves an infinite-dimensional data space where we observe the full tumor. In the second setting we observe only the tumor volume; hence the data space is finite-dimensional. We show the well-posedness of the posterior measure for both settings, building upon and improving the analytical results in [C. Kahle and K. F. Lam, Appl. Math. Optim., (2018)]. A numerical example involving synthetic data is presented in which the posterior measure is numerically approximated by the sequential Monte Carlo approach with tempering.
</details>


[7] Jonas Latz, Marvin Eisenberger, Elisabeth Ullmann (2019): **Fast Sampling of parameterised Gaussian random fields.** Comput. Methods in Appl. Mech. Engrg. 348, p. 978-1012, [doi](https://doi.org/10.1016/j.cma.2019.02.003). ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/LEU19.bib), [arXiv](https://arxiv.org/abs/1804.11157))  
<details>
<summary>Abstract</summary>

Gaussian random fields are popular models for spatially varying uncertainties, arising for instance in geotechnical engineering, hydrology or image processing. A Gaussian random field is fully characterised by its mean function and covariance operator. In more complex models these can also be partially unknown. In this case we need to handle a family of Gaussian random fields indexed with hyperparameters. Sampling for a fixed configuration of hyperparameters is already very expensive due to the nonlocal nature of many classical covariance operators. Sampling from multiple configurations increases the total computational cost severely. In this report we employ parameterised Karhunen-Loève expansions for sampling. To reduce the cost we construct a reduced basis surrogate built from snapshots of Karhunen-Loève eigenvectors. In particular, we consider Matérn-type covariance operators with unknown correlation length and standard deviation. We suggest a linearisation of the covariance function and describe the associated online-offline decomposition. In numerical experiments we investigate the approximation error of the reduced eigenpairs. As an application we consider forward uncertainty propagation and Bayesian inversion with an elliptic partial differential equation where the logarithm of the diffusion coefficient is a parameterised Gaussian random field. In the Bayesian inverse problem we employ Markov chain Monte Carlo on the reduced space to generate samples from the posterior measure. All numerical experiments are conducted in 2D physical space, with non-separable covariance operators, and finite element grids with ~1E4 degrees of freedom.
</details>


[6] Matthieu Bulté, Jonas Latz, Elisabeth Ullmann (2018): **A practical example for the non-linear Bayesian filtering of model parameters.** *Accepted.* ([github](https://github.com/BayesianLearning/PenduSMC), [.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/BLU18.bib), [arXiv](https://arxiv.org/abs/1807.08713)) 
<details>
<summary>Abstract</summary>

In this tutorial we consider the non-linear Bayesian filtering of static parameters in a time-dependent model. We outline the theoretical background and discuss appropriate solvers. We focus on particle-based filters and present Sequential Importance Sampling (SIS) and Sequential Monte Carlo (SMC). Throughout the paper we illustrate the concepts and techniques with a practical example using real-world data. The task is to estimate the gravitational acceleration of the Earth g by using observations collected from a simple pendulum. Importantly, the particle filters enable the adaptive updating of the estimate for g as new observations become available. For tutorial purposes we provide the data set and a Python implementation of the particle filters.
</details>


[5] Jonas Latz, Iason Papaioannou, Elisabeth Ullmann (2018): **Multilevel Sequential² Monte Carlo for Bayesian Inverse Problems.**  J. Comput. Phys. 368, p. 154-178, [doi](https://doi.org/10.1016/j.jcp.2018.04.014). ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/LPU18.bib), [arXiv](https://arxiv.org/abs/1709.09763))  
<details>
<summary>Abstract</summary>

The identification of parameters in mathematical models using noisy observations is a common task in uncertainty quantification. We employ the framework of Bayesian inversion: we combine monitoring and observational data with prior information to estimate the posterior distribution of a parameter. Specifically, we are interested in the distribution of a diffusion coefficient of an elliptic PDE. In this setting, the sample space is high-dimensional, and each sample of the PDE solution is expensive. To address these issues we propose and analyse a novel Sequential Monte Carlo (SMC) sampler for the approximation of the posterior distribution. Classical, single-level SMC constructs a sequence of measures, starting with the prior distribution, and finishing with the posterior distribution. The intermediate measures arise from a tempering of the liklihood, or, equivalently, a rescaling of the noise. The resolution of the PDE discretisation is fixed. In contrast, our estimator employs a hierarchy of PDE discretisations to decrease the computational cost. We construct a sequence of intermediate measures by decreasing the temperature or by increasing the discretisation level at the same time. This idea builds on and generalises the multi-resolution sampler proposed in [P.S. Koutsourelakis, J. Comput. Phys., 228 (2009), pp. 6184-6211] where a bridging scheme is used to transfer samples from coarse to fine discretisation levels. Importantly, our choice between tempering and bridging is fully adaptive. We present numerical experiments in 2D space, comparing our estimator to single-level SMC and the multi-resolution sampler.
</details>

___

### Theses

[4] Jonas Latz (2019): **Exploring and exploiting hierarchies in Bayesian inverse problems.**  Doctoral thesis, Technical University of Munich. ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/La19b.bib), [full text](https://mediatum.ub.tum.de/?id=1518069)) 
<details>
<summary>Abstract</summary>
  
We make several novel contributions to aspects of the Bayesian approach to inverse problems: well-posedness, discretisation, and algorithms. The first main contribution of this work is a new concept of well-posedness of Bayesian inverse problems. In contrast to the existing concepts, our slightly simplified concept allows us to make well-posedness statements with respect to general mathematical models. Under e.g. finite-dimensional, non-degenerate Gaussian noise assumptions, we only need to show measurability of the underlying model. 

Next, we move on to the discretisation of Bayesian inverse problems. We consider hierarchical Bayesian inverse problems in which the prior random field is parameterised. Typically, random fields are discretised by truncated spectral expansions, such as the Karhunen–Loève expansion. Such discretisation strategies may adhoc be not suitable in hierarchical settings, since the parameterisation may require a large number of random field discretisations. This is computationally infeasible. The second main contribution of this thesis is a reduced basis method allowing for a computationally cheap, parameterised discretisation. 

The solution of a Bayesian inverse problem is the posterior distribution. Sampling from the posterior distribution, with e.g. Markov chain Monte Carlo (MCMC) or Importance Sampling, may be unsuitable if the Bayesian inverse problems are constrained by a computationally tasking mathematical model, e.g. by a partial differential equation (PDE). More suitable are Sequential Monte Carlo strategies that use hierarchies of model discretisations and tempered likelihoods. An adaptive combination of these hierarchies leads to the third main contribution of this work: the highly efficient Multilevel Sequential² Monte Carlo algorithm. We derive this method and compare it numerically with standard Sequential Monte Carlo methods. Moreover, we interpret Sequential Monte Carlo in a framework where it is a Markov chain of random measures. In this setting, we discuss the long-time behaviour of these Markov chains and, thus, the convergence of Sequential Monte Carlo. This is the fourth main contribution of this work. We conclude by pointing the reader to directions for future research. 
</details>


[3] Jonas Latz (2016): **Bayes Linear Methods for Inverse Problems.**  Master's thesis, University of Warwick. ([.bib](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/bibtex/La16.bib), [full text](https://github.com/latz-io/latz-io.github.io/blob/master/_publications/Dissertation_Jonas_Latz.pdf)) 
<details>
<summary>Abstract</summary>
  
The objective of this report is the development and the examination of  Bayes Linear methods in the Bayesian inverse problems framework. Firstly, this framework, along with that of the classical inverse problem, is motivated and briefly introduced. Thereafter, a rigorous presentation of the theory of both conditional expectations and Bayes Linear approximations for Hilbert space valued random variables is given, both of which focus on the best estimator property. These estimators will then be used as point estimators of the solution of a Bayesian inverse problem. However, due to the complexity of the examined model, the (mostly simulation based) derivation of the conditional expectation is relatively computationally expensive and the results of the less expensive Bayes Linear estimator are typically rather poor. Thus, the Ensemble Kalman Filter, which is an efficient  method to approximate  conditional expectations, is motivated as a sequential Bayes Linear strategy and presented in both the data assimilation and the Sequential Monte Carlo setting. With the aim of improving the efficiency of the Ensemble Kalman Filter by an adaptive step length, a gradient-free Wolfe-type condition is constructed based on the Bayes Linear estimator and discussed.

All presented techniques are numerically examined in several experiments. In particular, estimation results of analytical and simulation based Bayes Linear estimators are compared with the Ensemble Kalman Filter and with a Monte Carlo simulation (based on autonormalised importance sampling) of the conditional expectation. Furthermore, the Ensemble Kalman Filter both with and without the above-mentioned Bayes Linear line search are tested against each other. Finally, the Ensemble Kalman Filter is considered in a situation, where the posterior distribution is multi modal.
</details>


[2] Jonas Latz (2014): **Äußere Hausdorff-Maße: Anwendungen und Eigenschaften.**  Bachelor's thesis, University of Trier (in German).


___


### Miscellaneous (non-refereed)

[1] Jonas Latz (2019): **On the well-posedness of Bayesian inverse problems: The Gaussian noise case.** Oberwolfach Report 12/2019, p. 35-36, [doi](https://doi.org/10.4171/OWR/2019/12). ([preliminary full text](https://www.mfo.de/document/1911/preliminary_OWR_2019_12.pdf))  

