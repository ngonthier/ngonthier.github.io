---
title: "The Change You Want To Detect: Semantic Change Detection In Earth Observation With Hybrid Data Generation"
collection: publications
permalink: /publication/2025-03-ChangeWantToDetect.md
excerpt: 'This paper is about a new pipeline to create a hybrid semantic change detection dataset for pretraining models. We provide a comprehensive evaluation of transfer learning on 5 differents datasets and 4 scenarios.'
date: 2025-03-02
venue: 'CVPR'
github: https://github.com/yb23/HySCDG
paperurl: https://arxiv.org/pdf/2503.15683.pdf
citation: 'Benidir Y. (2025). &quot; The Change You Want To Detect: Semantic Change Detection In Earth Observation With Hybrid Data Generation&quot; <i>CVPR</i>.'
teaser: teaser_CWTD_short.png
---

[Yanis Benidir](https://yb23.github.io/), **Nicolas Gonthier** and [Clément Mallet](https://www.umr-lastig.fr/clement-mallet/)

[PDF](https://arxiv.org/abs/2503.15683) - [HF Dataset Page](https://huggingface.co/datasets/Yanis236/fsc-180k) - [Project Page]([https://gastruc.github.io/anysat](https://yb23.github.io/projects/cywd/)

Abstract
======

Bi-temporal change detection at scale based on Very High Resolution (VHR) images is crucial for Earth monitoring. This remains poorly addressed so far: methods either require large volumes of annotated data (semantic case), or are limited to restricted datasets (binary set-ups). Most approaches do not exhibit the versatility required for temporal and spatial adaptation: simplicity in architecture design and pretraining on realistic and comprehensive datasets. Synthetic datasets are the key solution but still fail to handle complex and diverse scenes. In this paper, we present HySCDG a generative pipeline for creating a large hybrid semantic change detection dataset that contains both real VHR images and inpainted ones, along with land cover semantic map at both dates and the change map. Being semantically and spatially guided, HySCDG generates realistic images, leading to a comprehensive and hybrid transfer-proof dataset FSC-180k. We evaluate FSC-180k on five change detection cases (binary and semantic), from zero-shot to mixed and sequential training, and also under low data regime training. Experiments demonstrate that pretraining on our hybrid dataset leads to a significant performance boost, outperforming SyntheWorld, a fully synthetic dataset, in every configuration. All codes, models, and data are available.

Keywords
======
* Change Detection
* Image Synthesis
* Transfer Learning
* Diffusion Model
* Very High Resolution

# ![The Change You Want To Detect Overview.](https://ngonthier.github.io/images/teaser_CWTD.png)

# ![Architecture of the generation pipeline.](https://ngonthier.github.io/images/pipeline_CWTD.png)
