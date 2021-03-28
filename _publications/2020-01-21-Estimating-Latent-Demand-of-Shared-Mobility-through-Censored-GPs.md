---
title: "Estimating Latent Demand of Shared Mobility through Censored Gaussian Processes"
collection: publications
permalink: /publication/2020-01-21-Estimating-Latent-Demand-of-Shared-Mobility-through-Censored-GPs
excerpt: 'How can we estimate the true (i.e. latent) demand of mobility from incomplete historical observations? This paper approaches this problem by introducing a novel Gaussian process architecture to overcome the censored nature of the demand process.'
date: 2020-01-21
venue: 'Transportation Research Part C: Emerging Technologies'
---
[[PDF]](https://arxiv.org/abs/2001.07402) [[Code]](https://github.com/DanieleGammelli/CensoredGP)

**Abstract:** Transport demand is highly dependent on supply, especially for shared transport services where availability is often limited. As observed demand cannot be higher than available supply, historical transport data typically represents a biased, or censored, version of the true underlying demand pattern. Without explicitly accounting for this inherent distinction, predictive models of demand would necessarily represent a biased version of true demand, thus less effectively predicting the needs of service users. To counter this problem, we propose a general method for censorship-aware demand modeling, for which we devise a censored likelihood function. We apply this method to the task of shared mobility demand prediction by incorporating the censored likelihood within a Gaussian Process model, which can flexibly approximate arbitrary functional forms. Experiments on artificial and real-world datasets show how taking into account the limiting effect of supply on demand is essential in the process of obtaining an unbiased predictive model of user demand behavior.

**BibTex:** 
```
@misc{gammelli2020estimating,
      title={Estimating Latent Demand of Shared Mobility through Censored Gaussian Processes}, 
      author={Daniele Gammelli and Inon Peled and Filipe Rodrigues and Dario Pacino and Haci A. Kurtaran and Francisco C. Pereira},
      year={2020},
      eprint={2001.07402},
      archivePrefix={arXiv},
      primaryClass={stat.ML}
}
```
