---
title: "The Learnable Typewriter: A Generative Approach to Text Line Analysis"
collection: publications
permalink: /publication/2023-Learnable_typewriter
excerpt: 'This paper is about unsupervised text recognition based on analysis-by-synthesis method.'
date: 2023-02-01
venue: 'preprint'
#paperurl: 'https://'
citation: 'Siglidis, I. (2023). &quot; The Learnable Typewriter: A Generative Approach to Text Line Analysis &quot; <i>preprint</i>.'
---

[Ioannis Siglidis](https://imagine.enpc.fr/~siglidii/), *Nicolas Gonthier*, [Julien Gaubil](https://juliengaubil.github.io/),  [Tom Monnier](https://www.tmonnier.com/) and [Mathieu Aubry](http://imagine.enpc.fr/~aubrym/)


[arxiv](https://arxiv.org/abs/2302.01660) - [Code](https://github.com/ysig/learnable-typewriter) - [suppmat](http://imagine.enpc.fr/~siglidii/learnable-typewriter/supmat.pdf) - [Project](http://imagine.enpc.fr/~siglidii/learnable-typewriter/)

Abstract
======

We present a generative document-specific approach to character analysis and recognition in text lines. Our main idea is to build on unsupervised multi-object segmentation approaches and in particular methods which reconstruct images based on a limited amount of visual elements, called sprites. Our approach can learn a large number of different characters and leverage line-level annotations when available. Our contributions are twofold. First, we provide the first adaptation and evaluation of a deep unsupervised multi-object segmentation approach for text line analysis. Since these methods have mainly been evaluated on synthetic data in a completely unsupervised setting, demonstrating they can be adapted and quantitatively evaluated on real images, even as structured as text images, and using weak supervision are significant progresses. Second, we demonstrate the potential of the method we present for new applications, in particular in the field of paleography, which studies the history and variations of handwriting. We evaluate our approach on three very different datasets: a printed volume of the Google1000 dataset, the Copiale cipher and historical handwritten charters from the XIIth and early XIIIth century.

Keywords
======
* Deep learning
* Unsupervised Learning
* Optical and Handwritten Text Recognition
* Analysis-by-Synthesis
* Paleography

![Overview of the approach](https://ngonthier.github.io/images/teaser_learnable_typewriter.jpg)

Recommended citation: Siglidis, I. and Gonthier, N. and Gaubil, J. and Monnier, T. and Aubry, M. (2023). "The Learnable Typewriter: A Generative Approach to Text Line Analysis" <i>preprint</i>.
