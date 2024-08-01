---
title: "GeoMultiTaskNet: remote sensing unsupervised domain adaptation using geographical coordinates"
collection: publications
permalink: /publication/2023-GeoMultiTaskNet-EarthVision
excerpt: 'This paper is about domain adaptation in remote sensing based on using geographical coordinates of the patches.'
date: 2023-04-19
venue: 'CVPR Workshops EarthVision'
teaser: GeoMT_Teaser.JPG
#paperurl: 
citation: 'Marsocci V. (2023). &quot;GeoMultiTaskNet: remote sensing unsupervised domain adaptation using geographical coordinates&quot; <i>CVPR Workshops EarthVision</i>.'
---

[Valerio Marsocci](http://cedric.cnam.fr/lab/author/vmarsocci/), **Nicolas Gonthier**, [Anatol Garioud](https://scholar.google.fr/citations?user=6c9QX2AAAAAJ&hl=fr), [Simone Scardapane](https://www.sscardapane.it/), [Clément Mallet](https://www.umr-lastig.fr/clement-mallet/)

[PDF](https://arxiv.org/pdf/2304.07750.pdf) - [Dataset](https://ignf.github.io/FLAIR/) 

Abstract
======

Land cover maps are a pivotal element in a wide range of Earth Observation (EO) applications. However, annotating large datasets to develop supervised systems for remote sensing (RS) semantic segmentation is costly and time-consuming. Unsupervised Domain Adaption (UDA) could tackle these issues by adapting a model trained on a source domain, where labels are available, to a target domain, without annotations. UDA, while gaining importance in computer vision, is still under-investigated in RS. Thus, we propose a new lightweight model, GeoMultiTaskNet, based on two contributions: a GeoMultiTask module (GeoMT), which utilizes geographical coordinates to align the source and target domains, and a Dynamic Class Sampling (DCS) strategy, to adapt the semantic segmentation loss to the frequency of classes. This approach is the first to use geographical metadata for UDA in semantic segmentation. It reaches state-of-the-art performances (47,22% mIoU), reducing at the same time the number of parameters (33M), on a subset of the FLAIR dataset, a recently proposed dataset properly shaped for RS UDA, used for the first time ever for research scopes here.

Keywords
======
* Deep learning
* Domain Adaptation
* Geographical coordinates Awared Model 

![Radiometric discrepancies of the aerial images between domains](https://ngonthier.github.io/images/radiometric.png)

Recommended citation: Marsocci V., Gonthier N., Garioud A., Scardapane S., Mallet C. (2023). "GeoMultiTaskNet: remote sensing unsupervised domain adaptation using geographical coordinates
" <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops EarthVision</i>.
