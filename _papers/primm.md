---
sequence_id: 103
layout: paper
permalink: /html/PRIMM_Perception_Using_Integrated_Multi-Modal_Modularity.html
title: "PRIMM: Perception Using Integrated Multi-Modal Modularity"
authors: lilian lamb, Mohammadreza Mohammadi, Ramtin Zand
pdf: /pdf/PRIMM_Perception_Using_Integrated_Multi-Modal_Modularity.pdf
# supp: /pdf/PRIMM_Perception_Using_Integrated_Multi-Modal_Modularity_supplementary.pdf
bibtex: |
  @inproceedings{lamb2026primm,
    author    = {lamb, lilian and Mohammadi, Mohammadreza and Zand, Ramtin},
    title     = {PRIMM: Perception Using Integrated Multi-Modal Modularity},
    booktitle = {CVPR 2026 Workshop on On-Sensor Vision},
    year      = {2026},
    url       = {https://onsensor-vision.github.io/pdf/PRIMM_Perception_Using_Integrated_Multi-Modal_Modularity.pdf},
    note      = {Workshop extended abstract}
  }
---
<p>Embedded vision systems face a fundamental trade-off between high-resolution sensing and limited edge resources. In this paper, we propose the PRIMM system, which addresses this challenge through adaptive, multimodal perception that preserves efficiency while improving robustness. Unlike camera-only pipelines that degrade in low-light or occluded scenes, PRIMM fuses RGB imagery with LiDAR-derived dense depth maps generated near the sensor. Depth maps are constructed through LiDAR-to-camera transformation followed by parallelized chunk-based interpolation, enabling efficient preprocessing on near-sensor compute units. Selective sensor activation further reduces redundant workload by engaging LiDAR only when visual confidence is low. Evaluation across multiple datasets shows that PRIMM improves perception robustness and detection accuracy with minimal impact on energy consumption and latency, demonstrating the effectiveness of near-sensor multimodal fusion for adaptive embedded vision.</p>
