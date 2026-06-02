---
sequence_id: 106
layout: paper
permalink: /html/Rethinking_Super-Resolution_for_Near-Sensor_Object_Detection.html
title: "Rethinking Super-Resolution for Near-Sensor Object Detection"
authors: Lingjia Shi, Jinendra Malekar, Ramtin Zand
pdf: /pdf/Rethinking_Super-Resolution_for_Near-Sensor_Object_Detection.pdf
# supp: /pdf/Rethinking_Super-Resolution_for_Near-Sensor_Object_Detection_supplementary.pdf
bibtex: |
  @inproceedings{shi2026superresolution,
    author    = {Shi, Lingjia and Malekar, Jinendra and Zand, Ramtin},
    title     = {Rethinking Super-Resolution for Near-Sensor Object Detection},
    booktitle = {CVPR 2026 Workshop on On-Sensor Vision},
    year      = {2026},
    url       = {https://onsensor-vision.github.io/pdf/Rethinking_Super-Resolution_for_Near-Sensor_Object_Detection.pdf},
    note      = {Workshop extended abstract}
  }
---
<p>Deploying computer vision models on edge devices requires carefully balancing accuracy, latency, and data movement. In this work, we investigate super-resolution (SR) not as a means to improve visual quality, but as a near-sensor preprocessing primitive for optimizing end-to-end system efficiency in object detection pipelines. We introduce a split SR framework based on a lightweight hierarchical architecture (Swin-HIER), where the encoder is deployed near the sensor to generate compact feature representations, and the decoder operates on the edge device. This design reduces the need to transmit full-resolution images over bandwidth-limited wireless links, thereby lowering overall latency.</p>
<p>Through experiments on the COCO dataset using a lightweight detector (YOLO26n), we show that applying 2× SR without retraining leads to only a modest drop in detection performance (from 0.401 to 0.369 mAP@[0.5:0.95]), indicating that SR preserves competitive accuracy despite introducing a distribution shift. At the same time, system-level evaluation on NVIDIA Jetson hardware demonstrates up to 1.26× latency reduction compared to conventional pipelines that transmit raw images. Our results suggest that, in standard-resolution regimes, SR is more effective as a system optimization tool than as a performance enhancer. This work highlights the importance of co-designing data representation, model architecture, and deployment strategy for efficient edge vision systems.</p>
