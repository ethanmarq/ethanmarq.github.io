---
title: "Mitigating I/O Bottlenecks in LiDAR Pipelines by Directly Merging Neural Decompression and Semantic Segmentation"
collection: publications
category: posters
permalink: /publication/mitigatingIO
excerpt: 'This poster is about improving real-time performance of LiDAR autonomous vehciles in rural enviroments.'
date: 2025-11-18
venue: 'Super Computing 2025'
slidesurl: 'https://ethanmarq.github.io/files/mitigatingIO-slides.pdf'
paperurl: 'https://ethanmarq.github.io/files/mitigatingIO-paper.pdf'
citation: '*Marquez, E., M. Faykus, O. Odetoye, Smith, M. Calhoun, J. (2025) Mitigating I/O Bottlenecks in LiDAR Pipelines by Directly Merging Neural Decompression and Semantic Segmentation.'
---


The increasing volume of high-resolution LiDAR data poses a significant I/O bottleneck in large-scale analysis and high-performance computing pipelines due to costly intermediary data storage and retrieval. We introduce a novel, end-to-end framework that addresses this issue by proposing the first unified RENO-based neural autoencoder with a Point Transformer v3 (PTV3) segmentation backbone. This integrated architecture directly feeds the high rank feature tensors of the RENO decoder into the segmentation backbone, completely bypassing the need for costly intermediary file storage and I/O operations. Evaluated on the German Outdoor and Offroad (GOOSE) dataset, this approach enables direct semantic analysis on compressed data. Our results demonstrate that this method significantly reduces storage overhead, saving 29.9 GB per 13,076 point clouds and 2.7 GB per minute of LiDAR operation, all while maintaining the accuracy of semantic segmentation. This unified framework represents a major step towards efficient, real-time processing of large-scale point cloud datasets.