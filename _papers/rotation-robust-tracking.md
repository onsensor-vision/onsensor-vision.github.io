---
sequence_id: 111
layout: paper
permalink: /html/Rotation-Robust_On-Sensor_Feature_Tracking_via_In-Pixel_Shear_Compensation.html
title: "Rotation-Robust On-Sensor Feature Tracking via In-Pixel Shear Compensation"
authors: Anirudh Kannan
# pdf: /pdf/Rotation-Robust_On-Sensor_Feature_Tracking_via_In-Pixel_Shear_Compensation.pdf   # full paper not provided yet -> [pdf] shown greyed/disabled
# supp: /pdf/Rotation-Robust_On-Sensor_Feature_Tracking_via_In-Pixel_Shear_Compensation_supplementary.pdf
bibtex: |
  @inproceedings{kannan2026rotation,
    author    = {Kannan, Anirudh},
    title     = {Rotation-Robust On-Sensor Feature Tracking via In-Pixel Shear Compensation},
    booktitle = {CVPR 2026 Workshop on On-Sensor Vision},
    year      = {2026},
    url       = {https://onsensor-vision.github.io/pdf/Rotation-Robust_On-Sensor_Feature_Tracking_via_In-Pixel_Shear_Compensation.pdf},
    note      = {Workshop extended abstract}
  }
---
<p>Descriptor-In-Pixel (DIP) tracking exploits the massively parallel architecture of Pixel Processor Arrays (PPAs) to perform high-speed feature tracking entirely on-sensor. However, the binary ring descriptors used by DIP are inherently rotation-sensitive: a rotation of as little as 5° causes the loss of over 60% of tracked features in the baseline system. We present a PPA-compatible pre-rotation compensation pipeline that applies an inverse in-plane rotation to each query frame, via integer 3-shear decomposition, before descriptor computation. The shear operations are expressible as uniform per-row and per-column pixel shifts, preserving PPA locality and SIMD-style parallelism with no global operations or learned components. Evaluated on real KITTI imagery under controlled synthetic rotations of 0°–45°, our method raises mean feature survival from 26.5% to 60.0% on a highway sequence and from 12.6% to 50.5% on a turning sequence, with peak survival gains of +55% and +59% at 10° respectively. The compensation assumes the rotation angle is known upstream (e.g. from an IMU), and the entire pipeline remains executable within the PPA computational model.</p>
