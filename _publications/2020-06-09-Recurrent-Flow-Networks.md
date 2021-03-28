---
title: "Recurrent Flow Networks: A Recurrent Latent Variable Model for Spatio-Temporal Density Modelling"
collection: publications
permalink: /publication/2020-06-09-Recurrent-Flow-Networks
excerpt: 'Spatio-Temporal density estimation is one the open challenges in machine learning and statistical sciences. In this work we introduce *Recurrent Flow Netwroks*, a novel generative neural architecture to model complex data distributions. We show how these models can effectively model and predict future urban mobility distributions.'
date: 2020-06-09
venue: '(Submitted)'
---
[[PDF]](https://arxiv.org/abs/2006.05256) [[Code]](https://github.com/DanieleGammelli/recurrent-flow-nets)

**Abstract:** When modelling real-valued sequences, a typical approach in current RNN architectures is to use a Gaussian mixture model to describe the conditional output distribution. In this paper, we argue that mixture-based distributions could exhibit structural limitations when faced with highly complex data distributions such as for spatial densities. To address this issue, we introduce recurrent flow networks which combine deterministic and stochastic recurrent hidden states with conditional normalizing flows to form a probabilistic neural generative model capable of describing the kind of variability observed in highly structured spatio-temporal data. Inspired by the model's factorization, we further devise a structured variational inference network to approximate the intractable posterior distribution by exploiting a spatial representation of the data. We empirically evaluate our model against other generative models for sequential data on three real-world datasets for the task of spatio-temporal transportation demand modelling. Results show how the added flexibility allows our model to generate distributions matching potentially complex urban topologies.

**BibTex:** 
```
@misc{gammelli2020recurrent,
      title={Recurrent Flow Networks: A Recurrent Latent Variable Model for Spatio-Temporal Density Modelling}, 
      author={Daniele Gammelli and Filipe Rodrigues},
      year={2020},
      eprint={2006.05256},
      archivePrefix={arXiv},
      primaryClass={stat.ML}
}
```
