---
layout: page
title: An Evaluation of Representation Learning Methods in Particle Physics Foundation Models
permalink: /publications/foundation-model-evaluation/
nav: false
---

Michael Chen, Raghav Kansal, Abhijith Gandrakota, Zichun Hao, Jennifer Ngadiuba, Maria Spiropulu

Presented at the ML4PS workshop at NeurIPS 2025. I served as a mentor on this work.

<div style="text-align: center">
  <img src="/assets/img/publication_preview/arxiv-2511.12829-page.png" alt="Evaluation framework overview" style="max-width: min(420px, 100%); border-radius: 8px" loading="lazy">
</div>

## Abstract

> We present a systematic evaluation of representation learning objectives for particle physics within a unified framework. Our study employs a shared transformer-based particle-cloud encoder with standardized preprocessing, matched sampling, and a consistent evaluation protocol on a jet classification dataset. We compare contrastive (supervised and self-supervised), masked particle modeling, and generative reconstruction objectives under a common training regimen. In addition, we introduce targeted supervised architectural modifications that achieve state-of-the-art performance on benchmark evaluations. This controlled comparison isolates the contributions of the learning objective, highlights their respective strengths and limitations, and provides reproducible baselines. We position this work as a reference point for the future development of foundation models in particle physics, enabling more transparent and robust progress across the community.

## Links

- [arXiv:2511.12829](https://arxiv.org/abs/2511.12829)
- [ML4PS workshop paper](https://ml4physicalsciences.github.io/2025/files/NeurIPS_ML4PS_2025_70.pdf)
- [Poster at the ML4PS workshop at NeurIPS 2025](https://neurips.cc/media/PosterPDFs/NeurIPS%202025/123039.png)

## Cite

```bibtex
@article{Chen:2025nei,
    author = "Chen, Michael and Kansal, Raghav and Gandrakota, Abhijith and Hao, Zichun and Ngadiuba, Jennifer and Spiropulu, Maria",
    title = "{An Evaluation of Representation Learning Methods in Particle Physics Foundation Models}",
    eprint = "2511.12829",
    archivePrefix = "arXiv",
    primaryClass = "cs.LG",
    reportNumber = "FERMILAB-PUB-25-0821-CMS-LDRD-PPD",
    month = "11",
    year = "2025"
}
```
