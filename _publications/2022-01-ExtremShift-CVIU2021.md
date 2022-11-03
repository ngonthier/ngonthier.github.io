---
title: "Multiple instance learning on deep features for weakly supervised object detection with extreme domain shifts"
collection: publications
permalink: /publication/2022-01-ExtremShift-CVIU2021
excerpt: 'This paper is about weakly supervised object in artworks (paintings, watercolor etc) based on multiple instance learning. We propose a simple multiple instance approach applied on pre-trained deep features to learn new classes on non-photographic datasets.'
date: 2022-01-01
venue: 'Computer Vision and Image Understanding'
#paperurl: 'https://openaccess.thecvf.com/content_eccv_2018_workshops/w13/html/Gonthier_Weakly_Supervised_Object_Detection_in_Artworks_ECCVW_2018_paper.html'
citation: 'Gonthier, N. (2022). &quot;Multiple instance learning on deep features for weakly supervised object detection with extreme domain shifts&quot; <i>Computer Vision and Image Understanding</i>.'
---

*Nicolas Gonthier*, [Saïd Ladjal](https://perso.telecom-paristech.fr/ladjal/) and [Yann Gousseau](https://gousseau.wp.imt.fr/)

[PDF](https://arxiv.org/abs/2008.01178) - [Code](https://github.com/ngonthier/Mi_max) - [Dataset](https://wsoda.telecom-paristech.fr/downloads/dataset/) - [Project](https://wsoda.telecom-paristech.fr/) - [Journal](https://www.sciencedirect.com/science/article/abs/pii/S1077314221001430)

Abstract
======

Weakly supervised object detection (WSOD) using only image-level annotations has attracted a growing attention over the past few years. Whereas such task is typically addressed with a domain-specific solution focused on natural images, we show that a simple multiple instance approach applied on pre-trained deep features yields excellent performances on non-photographic datasets, possibly including new classes. The approach does not include any fine-tuning or cross-domain learning and is therefore efficient and possibly applicable to arbitrary datasets and classes. We investigate several flavors of the proposed approach, some including multi-layers perceptron and polyhedral classifiers. Despite its simplicity, our method shows competitive results on a range of publicly available datasets, including paintings (People-Art, IconArt), watercolors, cliparts and comics and allows to quickly learn unseen visual categories.

Keywords
======
* Deep learning
* Convolutional neural networks
* Weakly supervised object detection
* Non-photographic images
* Art analysis
* Multiple instance learning

![Examples of detection with our polyhedral model.](https://ngonthier.github.io/images/featured_CVIU.PNG)

Recommended citation: Gonthier, N., Ladjal S. and Gousseau Y. (2022). "Multiple instance learning on deep features for weakly supervised object detection with extreme domain shifts" <i>Computer Vision and Image Understanding</i>.
