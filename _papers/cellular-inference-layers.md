---
sequence_id: 110
layout: paper
permalink: /html/Cellular_Inference_Layers_for_On-Sensor_Semantic_Segmentation_Convergence_Guarantees_and_Energy_Efficiency.html
title: "Cellular Inference Layers for On-Sensor Semantic Segmentation: Convergence Guarantees and Energy Efficiency"
authors: Kaustubh S. Bukkapatnam
# pdf: /pdf/Cellular_Inference_Layers_for_On-Sensor_Semantic_Segmentation_Convergence_Guarantees_and_Energy_Efficiency.pdf   # full paper not provided yet -> [pdf] shown greyed/disabled
# supp: /pdf/Cellular_Inference_Layers_for_On-Sensor_Semantic_Segmentation_Convergence_Guarantees_and_Energy_Efficiency_supplementary.pdf
bibtex: |
  @inproceedings{bukkapatnam2026cellular,
    author    = {Bukkapatnam, Kaustubh S.},
    title     = {Cellular Inference Layers for On-Sensor Semantic Segmentation: Convergence Guarantees and Energy Efficiency},
    booktitle = {CVPR 2026 Workshop on On-Sensor Vision},
    year      = {2026},
    url       = {https://onsensor-vision.github.io/pdf/Cellular_Inference_Layers_for_On-Sensor_Semantic_Segmentation_Convergence_Guarantees_and_Energy_Efficiency.pdf},
    note      = {Workshop extended abstract}
  }
---
<p>On-sensor vision promises drastically reduced latency and energy consumption by moving inference onto the image sensor itself. Pixel Processor Arrays (PPAs) realise this promise through a dense grid of processing elements that execute a single SIMD instruction stream, communicating only with their four nearest neighbours. We introduce Cellular Inference Layers (CIL), a recurrent computation primitive designed to respect these SIMD and locality constraints. Each CIL step applies a spatially uniform, neighbor-aggregating affine map followed by a ReLU activation. We prove (i) that CIL iteration converges to a unique fixed point whenever the spectral norms of the weight matrices satisfy a simple sufficient condition; (ii) that the effective receptive field grows linearly with the number of iterations; and (iii) a closed-form bound on the fixed-point perturbation caused by <em>q</em>-bit weight quantisation. Evaluated on Cityscapes semantic segmentation, a 16-iteration CIL with four feature channels achieves 41.4% mIoU on the 19-class validation set, while consuming an estimated (≈30×) less energy than off-sensor MobileNetV2-based inference. Our theoretical framework provides practitioners with interpretable design rules for trading iteration count, channel capacity, and weight precision.</p>
