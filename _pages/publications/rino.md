---
layout: page
title: "RINO: Renormalization Group Invariance with No Labels"
permalink: /publications/rino/
nav: false
---

Zichun Hao, Raghav Kansal, Abhijith Gandrakota, Chang Sun, Jennifer Ngadiuba, Javier Duarte, Maria Spiropulu

Spotlight paper at the ML4PS workshop at NeurIPS 2025, offered to about 1% of the workshop's accepted papers. 

## Abstract

> A common challenge with supervised machine learning (ML) in high energy physics (HEP) is the reliance on simulations for labeled data, which can often mismodel the underlying collision or detector response. To help mitigate this problem of domain shift, we propose RINO (Renormalization Group Invariance with No Labels), a self-supervised learning approach that can instead pretrain models directly on collision data, learning embeddings invariant to renormalization group flow scales. In this work, we pretrain a transformer-based model on jets originating from quantum chromodynamic (QCD) interactions from the JetClass dataset, emulating real QCD-dominated experimental data, and then finetune on the JetNet dataset -- emulating simulations -- for the task of identifying jets originating from top quark decays. RINO demonstrates improved generalization from the JetNet training data to JetClass data compared to supervised training on JetNet from scratch, demonstrating the potential for RINO pretraining on real collision data followed by fine-tuning on small, high-quality MC datasets, to improve the robustness of ML models in HEP.

## Links

- [arXiv:2509.07486](https://arxiv.org/abs/2509.07486)
- [Code on GitHub](https://github.com/zichunhao/RINO)
- [Spotlight talk at NeurIPS 2025](https://neurips.cc/virtual/2025/loc/san-diego/135882)
- [ML4PS workshop paper](https://ml4physicalsciences.github.io/2025/files/NeurIPS_ML4PS_2025_81.pdf)
- [Poster at NeurIPS 2025](https://neurips.cc/media/PosterPDFs/NeurIPS%202025/122856.png)
