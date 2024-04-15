---
title: "OmniSat: Self-Supervised Modality Fusion for Earth Observation"
collection: publications
permalink: /publication/2024-04_Omnisat
excerpt: 'This paper is about self-supervised multimodal learning modal for more efficient training scheme (with very high resolution aerial image and satellite time series).'
date: 2024-04-15
venue: 'preprint'
github: https://github.com/gastruc/OmniSat
link: https://ignf.github.io/FLAIR/
paperurl: https://arxiv.org/pdf/2404.08351.pdf
citation: 'Astruc G. (2024). &quot;OmniSat: Self-Supervised Modality Fusion for Earth Observation&quot; <i>preprint</i>.'
---

[Guillaume Astruc](https://imagine-lab.enpc.fr/staff-members/guillaume-astruc/), **Nicolas Gonthier**, [Clément Mallet](https://www.umr-lastig.fr/clement-mallet/) and [Loic Landrieu](https://loiclandrieu.com/)

[PDF](https://arxiv.org/pdf/2404.08351.pdf) - [Dataset PASTIS-HD](https://huggingface.co/datasets/IGNF/PASTIS-HD) - [Dataset TreeSatAI-Time Series](https://huggingface.co/datasets/IGNF/TreeSatAI-Time-Series)

Abstract
======

The field of Earth Observations (EO) offers a wealth of data from diverse sensors, presenting a great opportunity for advancing self-supervised multimodal learning. However, current multimodal EO datasets and models focus on a single data type, either mono-date images or time series, which limits their expressivity. We introduce OmniSat, a novel architecture that exploits the spatial alignment between
multiple EO modalities to learn expressive multimodal representations without labels. To demonstrate the advantages of combining modalities of different natures, we augment two existing datasets with new modalities. As demonstrated on three downstream tasks— forestry, land cover classification, and crop mapping—OmniSat can learn rich representations in an unsupervised manner, leading to improved performance in the semi- and fully-supervised settings, even when only
one modality is available for inference.

Keywords
======
* Multi modalities
* Modalities fusion
* Aerial and Satellite Images
* Self-supervised learning

# ![Architecture of the OmniSat model.](https://ngonthier.github.io/images/OmniSat_Archi.JPG)

Recommended citation: Astruc G., Gonthier N, Mallet C. and Landrieu L. (2024). "OmniSat: Self-Supervised Modality Fusion for Earth Observation" <i>preprint</i>.
