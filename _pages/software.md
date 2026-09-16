---
permalink: /software/
title: "Software & Code"
excerpt: "Software & Code"
author_profile: true
---

## Software
- [bayesbridge v0.2](https://github.com/OHDSI/bayes-bridge) &mdash; [documentation](https://bayes-bridge.readthedocs.io/en/latest/) <br> 
  Python package for Bayesian sparse regression based on the Bayesian bridge priors. The package implements the standard (Polya-Gamma augmented) Gibbs sampler as well as the CG-accelerated sampler of [Nishimura & Suchard (2023)](https://doi.org/10.1080/01621459.2022.2057859).

- [PRSBridge](https://github.com/YuzhengDun1999/PRSBridge) <br>
  Command line tool for constructing polygenic risk scores (PRS) from summary statistics, built on an adaptation of the bayesbridge package. Methodological details and benchmark comparisons against other PRS methods are provided in [Dun, Y., Chatterjee, N., Jin, J., & Nishimura, A. (2026)](https://doi.org/10.1080/01621459.2026.2663587). The benchmark results can be reproduced by [this code](https://github.com/YuzhengDun1999/PRS-Bridge-article-code).

- [htdg](https://github.com/suchard-group/hdtg) <br>
  R package for sampling from *h*igh-*d*imensional *t*runcated *g*aussians. In particular, it implements the Hamiltonian zigzag sampler of [Nishimura, A., Zhang, Z., and Suchard, M. A. (2025)](https://doi.org/10.1080/01621459.2024.2395587). Benchmark results and example code are provided in [this R Journal article](https://doi.org/10.32614/RJ-2026-038).

- [CausalSurvival](https://github.com/nishimura-zeger-lab/CausalSurvival) <br>
  R package implementing state-of-the-art doubly robust methods for estimating counterfactual survival curves, including augmented inverse probability weighting and targeted maximum likelihood estimation. More traditional procedures such as inverse probability weighting and stratified Cox model are also included.

## Code
- [Bouncy Hamiltonian Monte Carlo](https://github.com/chinandrew/bouncy_hamiltonian_monte_carlo) <br>
  Python module implementing the bouncy Hamiltonian sampler of [Chin, A. and Nishimura, A. (2024)](https://doi.org/10.48550/arXiv.2405.08290). The Gibbs samplers using the bouncy sampler for conditional updates, as presented in the article, are implemented [here](https://github.com/chinandrew/gi_bleed_hbps/) and [here](https://github.com/chinandrew/beast-mcmc/tree/hbps_develop). 

- [Hoseshoe scale sampler](https://github.com/aki-nishimura/horseshoe-scale-sampler) <br>
  Efficient rejection sampler for updating the local scale parameter in Gibbs sampling posterior distributions under (regularized) horseshoe models. Details and theoretical analysis can be found in the appendix of [Nishimura and Suchard (2022)](https://doi.org/10.1214/22-BA1308).

- [Discontinuous Hamiltonian Monte Carlo](https://github.com/aki-nishimura/discontinuous-hmc) <br>
  Python module implementing the discontinuous Hamiltonian Monte Carlo of [Nishimura et. al. (2022)](https://doi.org/10.1093/biomet/asz083). Other codes used in the paper are also provided, including the modules to efficiently compute the log-likelihoods and their gradients of the Jolly-Seber and PAC Bayesian inference.

- [Probabilistic importance weighted matrix factorization](https://github.com/aki-nishimura/probabilistic-matrix-factorization)
  <br> Python module for the Bayesian heteroscedastic matrix factorization model as described in [Yang et. al. (2017)](https://www.researchgate.net/publication/320883956_Bayesian_Heteroscedastic_Matrix_Factorization_for_Conversion_Rate_Prediction).

- [(Recycled) No-U-Turn sampler](https://github.com/aki-nishimura/NUTS-matlab)
  <br> Matlab functions for the No-U-Turn sampler of [Hoffman & Gelman (2014)](http://www.jmlr.org/papers/volume15/hoffman14a/hoffman14a.pdf) as well as its improvement via the recycling algorithm of [Nishimura & Dunson (2016)](https://arxiv.org/abs/1511.06925).
