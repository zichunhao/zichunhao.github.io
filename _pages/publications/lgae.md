---
layout: page
title: Lorentz Group Equivariant Autoencoders
permalink: /publications/lgae/
nav: false
---

Zichun Hao, Raghav Kansal, Javier Duarte, Nadezda Chernyavskaya

Published in The European Physical Journal C, volume 83, page 485 (2023).

<div style="text-align: center">
  <img src="/assets/img/publication_preview/lgae-page.png" alt="LGAE architecture" style="max-width: min(420px, 100%); border-radius: 8px" loading="lazy">
</div>

## Abstract

> There has been significant work recently in developing machine learning (ML) models in high energy physics (HEP) for tasks such as classification, simulation, and anomaly detection. Often these models are adapted from those designed for datasets in computer vision or natural language processing, which lack inductive biases suited to HEP data, such as equivariance to its inherent symmetries. Such biases have been shown to make models more performant and interpretable, and reduce the amount of training data needed. To that end, we develop the Lorentz group autoencoder (LGAE), an autoencoder model equivariant with respect to the proper, orthochronous Lorentz group SO+(3,1), with a latent space living in the representations of the group. We present our architecture and several experimental results on jets at the LHC and find it outperforms graph and convolutional neural network baseline models on several compression, reconstruction, and anomaly detection metrics. We also demonstrate the advantage of such an equivariant model in analyzing the latent space of the autoencoder, which can improve the explainability of potential anomalies discovered by such ML models.

## Links

- [Journal article (EPJC)](https://doi.org/10.1140/epjc/s10052-023-11633-5)
- [arXiv:2212.07347](https://arxiv.org/abs/2212.07347)
- [Code on GitHub](https://github.com/zichunhao/lgn-autoencoder)

## Cite

```bibtex
@article{Hao2023lgae,
    author = "Hao, Zichun and Kansal, Raghav and Duarte, Javier and Chernyavskaya, Nadezda",
    title = "{Lorentz group equivariant autoencoders}",
    journal = "The European Physical Journal C",
    volume = "83",
    pages = "485",
    year = "2023",
    doi = "10.1140/epjc/s10052-023-11633-5",
    eprint = "2212.07347",
    archivePrefix = "arXiv",
    primaryClass = "hep-ex"
}
```
