---
sequence_id: 100
layout: paper
permalink: /html/PixVOD_Pixel-Distributed_Direct_Visual_Odometry_and_Depth_Estimation.html
title: "PixVOD: Pixel-Distributed Direct Visual Odometry and Depth Estimation"
authors: Shinjeong Kim, Ignacio Alzugaray, Callum Rhodes, Paul H. J. Kelly, Andrew J. Davison
pdf: /pdf/PixVOD_Pixel-Distributed_Direct_Visual_Odometry_and_Depth_Estimation.pdf
# supp: /pdf/PixVOD_Pixel-Distributed_Direct_Visual_Odometry_and_Depth_Estimation_supplementary.pdf
bibtex: |
  @inproceedings{kim2026pixvod,
    author    = {Kim, Shinjeong and Alzugaray, Ignacio and Rhodes, Callum and Kelly, Paul H. J. and Davison, Andrew J.},
    title     = {PixVOD: Pixel-Distributed Direct Visual Odometry and Depth Estimation},
    booktitle = {CVPR 2026 Workshop on On-Sensor Vision},
    year      = {2026},
    url       = {https://onsensor-vision.github.io/pdf/PixVOD_Pixel-Distributed_Direct_Visual_Odometry_and_Depth_Estimation.pdf},
    note      = {Workshop extended abstract}
  }
---
Images composed of 2D pixel arrays are the standard input to computer vision algorithms, yet many underlying computations can be distributed across pixels. Transmitting raw, redundant, and noisy pixel data off the sensor remains inefficient, motivating a shift toward focal-plane sensor-processors that perform a significant part of the computation directly within each pixel. We envision pixels synthesizing higher-level signals locally, reducing downstream load, and providing richer inputs for higher-level vision tasks.

We propose a fully parallelizable form of visual odometry and depth estimation across pixels, where sensor-processors exchange information through Gaussian Belief Propagation (GBP) to achieve consensus about camera motion and infer depth from per-pixel photometric observations and a surface normal prior. To maintain geometric stability during optimization, we introduce a keyframe-like anchoring mechanism that regulates the effective baseline between frames, enabling consistent motion and depth updates. Our method is evaluated on realistic datasets, demonstrating the feasibility of GBP-based pixel-level distributed odometry and depth estimation with keyframe anchoring on-sensor.
