---
title: "Generalized Multi-Output Gaussian Process Censored Regression"
collection: publications
permalink: /publication/2020-09-10-Generalized-Multi-Output-Gaussian-Process-Censored-Regression
excerpt: 'In this work, we show how (i) exploiting correlations between multiple signals (i.e. multi-output) and (ii) allow for input-dependent noise (i.e. heteroscedasticity) can fundamentally improve censored data estimation.'
date: 2020-09-10
venue: '(Submitted)'
---
[[PDF]](https://arxiv.org/abs/2009.04822) [[Code]](https://github.com/DanieleGammelli/multi-output-gp-censored-regression)

**Abstract:** When modelling censored observations, a typical approach in current regression methods is to use a censored-Gaussian (i.e. Tobit) model to describe the conditional output distribution. In this paper, as in the case of missing data, we argue that exploiting correlations between multiple outputs can enable models to better address the bias introduced by censored data. To do so, we introduce a heteroscedastic multi-output Gaussian process model which combines the non-parametric flexibility of GPs with the ability to leverage information from correlated outputs under input-dependent noise conditions. To address the resulting inference intractability, we further devise a variational bound to the marginal log-likelihood suitable for stochastic optimization. We empirically evaluate our model against other generative models for censored data on both synthetic and real world tasks and further show how it can be generalized to deal with arbitrary likelihood functions. Results show how the added flexibility allows our model to better estimate the underlying non-censored (i.e. true) process under potentially complex censoring dynamics.

**BibTex:** 
```
@misc{gammelli2020generalized,
      title={Generalized Multi-Output Gaussian Process Censored Regression}, 
      author={Daniele Gammelli and Kasper Pryds Rolsted and Dario Pacino and Filipe Rodrigues},
      year={2020},
      eprint={2009.04822},
      archivePrefix={arXiv},
      primaryClass={stat.ML}
}
```
