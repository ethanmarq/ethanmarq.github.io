---
title: "Real-Time Inference for Unmanned Ground Vehicles Using Lossy Compression and Deep Learning"
collection: publications
category: manuscripts
permalink: /publication/realTimeInference
excerpt: 'This paper explores the effects of compression on efficient transformers and how it may be applied to autonomous vehicles.'
date: 2025-3-20
venue: 'Journal of ITEA test and evaluation'
slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: #'http://academicpages.github.io/files/paper2.pdf'
citation: 'Marquez, E., Niemczura, A., Taylor, C., Faykus III, M., Smith, M., & Calhoun, J. (2025). Real-Time Inference for Unmanned Ground Vehicles Using Lossy Compression and Deep Learning. In The ITEA Journal of Test and Evaluation (Vol. 46, Issue 1). International Test and Evaluation Association. https://doi.org/10.61278/itea.46.1.1004'
---


Autonomous vehicles rely on on-board perception systems for safe terrain navigation which becomes exceedingly important in rural areas. The aim of this study is to explore the effect compressed training images have on the performance of deep learning segmentation architectures and determine if lossy compression is a practical solution for providing real-time transfer speed for autonomous vehicle perception systems. To test the performance of compression on deep learning we apply ZFP, JPEG, and SZ3 to EfficientViT and UNet and rank test accuracy. As a result, this study found JPEG to achieve the highest compression ratio of 144.49× at JPEG quality level 0; while also achieving the fastest transfer speed of the compressors used on the Nvidia Xavier Edge Device. Furthermore, JPEG achieved the highest mIoU accuracy for both architectures tested in comparison to SZ3 and ZFP. Of the two deep learning architectures tested, EfficientViT outperforms U-Net for all lossy compressors at all levels of compression. EfficientViT achieves a peak mIoU of 95.5% at a JPEG quality level of 70. While U-Net peaks with an mIoU of 90.683% at a JPEG quality of 40.

This study advances autonomous vehicle development in two ways. First, it demonstrates that JPEG compression outperforms specialized scientific compressors (SZ3/ZFP) for off-road RGB perception systems. Second, it validates EfficeintViT’s effectiveness for resource-constrained autonomous navigation. These findings benefit autonomous vehicle engineers implementing perception systems, computer vision researchers working on embedded applications, and industry teams deploying off-road autonomous navigation solutions.