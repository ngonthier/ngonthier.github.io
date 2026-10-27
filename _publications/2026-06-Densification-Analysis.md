---
title: "From Orthophotos to Building Footprints over a decade: Model Inference-Based Approach for Urban Densification Analysis in Iasi, Romania"
collection: publications
permalink: /publication/2026-06-Densification-Analysis.md
excerpt: 'We propose an open, model-based workflow that extracts building footprints and tracks change (2011–2024) in Romania, showing that a France-trained segmentation model transfers well spatially.'
date: 2026-06-02
venue: 'ISPRS International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences'
paperurl: https://isprs-archives.copernicus.org/articles/XLIX-B4-2026/25/2026/isprs-archives-XLIX-B4-2026-25-2026.pdf
citation: 'Crenganis, L.-M. (2026). &quot;From Orthophotos to Building Footprints over a decade: Model Inference-Based Approach for Urban Densification Analysis in Iasi, Romania&quot; <i>ISPRS International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences</i>.'
---

[Crenganis, L.-M.](https://scholar.google.com/citations?user=_50kj2AAAAAJ&hl=ro), Loghin, A.-M., Stoian, C., [Olteanu-Raimond, A.-M.](https://www.umr-lastig.fr/fr/members/Ana-Maria-Olteanu-Raimond/), [Le Bris, A.](https://www.umr-lastig.fr/arnaud-le-bris/), [Raimbault, J.](https://www.umr-lastig.fr/juste-raimbault/), [Perret, J.](https://www.umr-lastig.fr/julien-perret/), [Bucher, B.](https://www.umr-lastig.fr/benedicte-bucher/), and **Nicolas Gonthier**

[PDF](https://isprs-archives.copernicus.org/articles/XLIX-B4-2026/25/2026/isprs-archives-XLIX-B4-2026-25-2026.pdf) 

** Best Poster Award ** at ISPRS Congress 2026.

Abstract
======

Urban densification in post-socialist cities involves fine-scale spatial transformations that are difficult to quantify in data-scarce environments. This study proposes FLAIR-HUB2BF, a model inference-based workflow for automated building footprint extraction and multi-temporal change analysis, applied to the city of Ias, i, Romania. The methodology extends the SUBDENSE conceptual framework by integrating the FLAIR-HUB deep learning model for semantic segmentation of very high resolution aerial orthophotos from 2011 and 2024, followed by binary mask extraction, instance segmentation, and Douglas–Peucker polygon generalization. The approach demonstrates good spatial transferability of the FLAIRHUB model which was trained on France to generate buildings (for 2024) and less good temporal transferability (for 2011) due to the quality of orthopothos in 2011. 
To support rigorous evaluation, the first open benchmark building footprint datasets for Romania in 2024 were produced through manual photo-interpretation correction across four morphologically distinct urban neighborhoods of Iași, and assessed against ISO 19157 spatial data quality standards, achieving commission and omission rates of 1.95% and 2.39% respectively. Quantitative evaluation using complementary GMA (Geometric Matching of areas) and MCA (Multi-Criteria Algorithm) data matching algorithms confirms moderate-to-high spatial accuracy for 2024, with MCA surface agreement rates reaching 91%. The proposed workflow establishes a transferable, reproducible, and open methodology for building-level urban monitoring applicable to other Romanian and European cities facing similar data constraints.

Keywords
======
* Semantic segmentation
* Transferability
* Building footprints extraction
* Data matching
* Urban densification

# ![Workflow.](https://ngonthier.github.io/images/1workflow.jpg)

# ![Workflow.](https://ngonthier.github.io/images/Example_dense.png)

