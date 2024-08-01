---
title: "StegoGAN: Leveraging Steganography for Non-Bijective Image-to-Image Translation"
collection: publications
permalink: /publication/2024_04_StegoGAN
excerpt: 'This paper is about leveaging steganography in GAN for non-bijective image translation, avoiding spurious synthesis and detecting mismatched features.'
date: 2024-04-01
venue: 'CVPR'
github: https://github.com/sian-wusidi/StegoGAN
paperurl: https://arxiv.org/pdf/2403.20142.pdf
teaser : StegoGAN.jpg
citation: 'Wu S. (2024). &quot;StegoGAN: Leveraging Steganography for Non-Bijective Image-to-Image Translationy&quot; <i>CVPR</i>.'
---

[Sidi Wu](https://scholar.google.com/citations?user=-QdAfx0AAAAJ&hl=en), [Yizi Chen](https://www.umr-lastig.fr/yizi-chen/), Samuel Mermet, Lorenz Hurni, [Konrad Schindler](https://igp.ethz.ch/personen/person-detail.html?persid=143986), **Nicolas Gonthier** and [Loic Landrieu](https://loiclandrieu.com/)

[PDF](https://arxiv.org/pdf/2403.20142.pdf) - [Datasets](https://zenodo.org/records/10839841) - [Code](https://github.com/sian-wusidi/StegoGAN)

Abstract
======

Most image-to-image translation models postulate that a unique correspondence exists between the semantic classes of the source and target domains. However, this assumption does not always hold in real-world scenarios due to divergent distributions, different class sets, and asymmetrical information representation. As conventional GANs attempt to generate images that match the distribution of the target domain, they may hallucinate spurious instances of classes absent from the source domain, thereby diminishing the usefulness and reliability of translated images. CycleGAN-based methods are also known to hide the mismatched information in the generated images to bypass cycle consistency objectives, a process known as steganography. In response to the challenge of non-bijective image translation, we introduce StegoGAN, a novel model that leverages steganography to prevent spurious features in generated images. Our approach enhances the semantic consistency of the translated images without requiring additional postprocessing or supervision. Our experimental evaluations demonstrate that StegoGAN outperforms existing GAN-based models across various non-bijective imageto-image translation tasks, both qualitatively and quantitatively.

Keywords
======

* Non-Bijective Image Translation
* Steganography
* GAN

# ![StegoGAN architecture.](https://ngonthier.github.io/images/StegoGAN.jpg)

Recommended citation: Wu S., Chen Y., Mermet S., Hurni L., Schindler K., Gonthier N. and Landrieu L. "StegoGAN: Leveraging Steganography for Non-Bijective Image-to-Image Translation" <i>CVPR 2024</i>.
