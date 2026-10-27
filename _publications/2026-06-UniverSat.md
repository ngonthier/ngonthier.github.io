---
title: "UniverSat: Resolution- and Modality-Agnostic Transformers for Earth Observation"
collection: publications
permalink: /publication/2026-06-UniverSat
excerpt: 'This paper is about AnySat: a JEPA-based multimodal Earth Observation model that trains simultaneously on diverse datasets with different scales, resolutions (spatial, spectral, temporal), and modality combinations.'
date: 2026-06-30
venue: 'NeurIPS'
github: https://github.com/gastruc/UniverSat
paperurl: https://arxiv.org/pdf/2606.23503.pdf
citation: 'Perron Y. (2026). &quot;UniverSat: Resolution- and Modality-Agnostic Transformers for Earth Observation&quot; <i>NeurIPS</i>.'
teaser: UniverSat_overview.png
---

[Yohann Perron](https://yohannperron.github.io/WebPage/) - [Guillaume Astruc](https://imagine-lab.enpc.fr/staff-members/guillaume-astruc/), **Nicolas Gonthier**, [Clément Mallet](https://www.umr-lastig.fr/clement-mallet/) and [Loic Landrieu](https://loiclandrieu.com/)

[PDF](https://arxiv.org/abs/2606.23503) - [Code](https://github.com/gastruc/UniverSat) - [Demo](https://github.com/gastruc/UniverSat/blob/main/demo.ipynb) - [Project Page](https://gastruc.github.io/universat)

Abstract
======

Vision Transformers (ViT) dominate computer vision. However, their reliance on rigid patch projectors hinders transfer to Earth Observation (EO), where input modalities, scales, and resolutions vary widely. We introduce UniverSat, a ViT-style backbone built around a Universal Patch Encoder that maps patches from arbitrary spatial, spectral, and temporal resolutions, and from both optical and non-optical sensors, into a shared embedding space with a shared set of weights. This enables training a single model on heterogeneous multimodal corpora via self-supervision, yielding robust, sensor-agnostic spatial features. We validate this approach with strong results across classification and segmentation on standard EO benchmarks from GeoBench, PANGEABench, and SpectralEarth.

Keywords
======
* Modality-Agnostic
* Multi modalities
* Modalities fusion
* Satellite Times Series
* Self-supervised learning

# ![Architecture of the UniverSat model.](https://ngonthier.github.io/images/UniverSat_architecture.png)

# ![UniverSat Embeddings.](https://ngonthier.github.io/images/UniverSat_embeddings)


