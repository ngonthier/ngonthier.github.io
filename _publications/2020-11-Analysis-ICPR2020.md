---
title: "An analysis of the transfer learning of convolutional neural networks for artistic images"
collection: publications
permalink: /publication/2020-11-Analysis-ICPR2020
excerpt: 'This paper is about CNN analysis with feature visualisation and quantitative metrics. We study the transfer learning from natural images to artistic ones.'
date: 2020-11-01
venue: 'Workshop on Fine Art Pattern Extraction and Recognition, ICPR'
#paperurl: 'https://openaccess.thecvf.com/content_eccv_2018_workshops/w13/html/Gonthier_Weakly_Supervised_Object_Detection_in_Artworks_ECCVW_2018_paper.html'
citation: 'Gonthier, N. (2020). &quot;An analysis of the transfer learning of convolutional neural networks for artistic images&quot; <i>Workshop on Fine Art Pattern Extraction and Recognition, ICPR</i>.'
---

*Nicolas Gonthier*, [Yann Gousseau](https://gousseau.wp.imt.fr/) and [Saïd Ladjal](https://perso.telecom-paristech.fr/ladjal/)

[PDF](https://arxiv.org/abs/2011.02727) - [Dataset](https://artfinetune.telecom-paris.fr/data/)

Abstract
======

Transfer learning from huge natural image datasets, fine-tuning of deep neural networks and the use of the corresponding pre-trained networks have become de facto the core of art analysis applications. Nevertheless, the effects of transfer learning are still poorly understood. In this paper, we first use techniques for visualizing the network internal representations in order to provide clues to the understanding of what the network has learned on artistic images. Then, we provide a quantitative analysis of the changes introduced by the learning process thanks to metrics in both the feature and parameter spaces, as well as metrics computed on the set of maximal activation images. These analyses are performed on several variations of the transfer learning procedure. In particular, we observed that the network could specialize some pre-trained filters to the new image modality and also that higher layers tend to concentrate classes. Finally, we have shown that a double fine-tuning involving a medium-size artistic dataset can improve the classification on smaller datasets, even when the task changes.

Keywords
======
* Deep learning
* Convolutional neural network
* Transfer learning
* Feature visualization

![Optimized Image for the fine-tuned model and the pretrained one.](https://ngonthier.github.io/images/feature_ICPR2020.png)

Recommended citation: Gonthier, N. (2020). "An analysis of the transfer learning of convolutional neural networks for artistic images" <i>Workshop on Fine Art Pattern Extraction and Recognition, ICPR</i>.
