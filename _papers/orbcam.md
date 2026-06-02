---
sequence_id: 105
layout: paper
permalink: /html/ORBCam_In-Sensor_ORB_Feature_Processing_for_Ultra-Low-Power_Visual-Inertial_Odometry.html
title: "ORBCam: In-Sensor ORB Feature Processing for Ultra-Low-Power Visual-Inertial Odometry"
authors: Yiwen Liang, Yuxiang Peng, Guoquan Huang, Weidong Cao, Chuchu Chen
pdf: /pdf/ORBCam_In-Sensor_ORB_Feature_Processing_for_Ultra-Low-Power_Visual-Inertial_Odometry.pdf
# supp: /pdf/ORBCam_In-Sensor_ORB_Feature_Processing_for_Ultra-Low-Power_Visual-Inertial_Odometry_supplementary.pdf
bibtex: |
  @inproceedings{liang2026orbcam,
    author    = {Liang, Yiwen and Peng, Yuxiang and Huang, Guoquan and Cao, Weidong and Chen, Chuchu},
    title     = {ORBCam: In-Sensor ORB Feature Processing for Ultra-Low-Power Visual-Inertial Odometry},
    booktitle = {CVPR 2026 Workshop on On-Sensor Vision},
    year      = {2026},
    url       = {https://onsensor-vision.github.io/pdf/ORBCam_In-Sensor_ORB_Feature_Processing_for_Ultra-Low-Power_Visual-Inertial_Odometry.pdf},
    note      = {Workshop extended abstract}
  }
---
<p>In visual–inertial odometry (VIO) systems, image readout and data movement between sensor and processor are increasingly recognized as the dominant power bottleneck, overshadowing on-chip computation. To address this, we present ORBCam, a cross-layer sensor–estimator co-design that eliminates image readout and directly generates motion-required feature measurements within the sensor subsystem. Instead of exporting images or descriptors, ORBCam transmits only quantized pixel coordinates and flow measurements to the host. In system-level simulations at 752 × 480 resolution and 100 FPS, ORBCam is compared against a conventional image sensor consuming 7.88 mW for full-frame acquisition and transmission. ORBCam reduces sensing power to 0.59 mW, achieving up to 13.3× energy efficiency improvement while maintaining comparable odometry accuracy.</p>
