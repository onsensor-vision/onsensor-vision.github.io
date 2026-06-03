---
sequence_id: 109
layout: paper
permalink: /html/Implementation_of_a_Retina_Model_on_the_SCAMP-5_Vision_Sensor.html
title: "Implementation of a Retina Model on the SCAMP-5 Vision Sensor"
authors: Maciej Lewandowski, Prince Philip, André van Schaik, Piotr Dudek
pdf: /pdf/Implementation_of_a_Retina_Model_on_the_SCAMP-5_Vision_Sensor.pdf
# supp: /pdf/Implementation_of_a_Retina_Model_on_the_SCAMP-5_Vision_Sensor_supplementary.pdf
bibtex: |
  @inproceedings{lewandowski2026retina,
    author    = {Lewandowski, Maciej and Philip, Prince and Schaik, André van and Dudek, Piotr},
    title     = {Implementation of a Retina Model on the SCAMP-5 Vision Sensor},
    booktitle = {CVPR 2026 Workshop on On-Sensor Vision},
    year      = {2026},
    url       = {https://onsensor-vision.github.io/pdf/Implementation_of_a_Retina_Model_on_the_SCAMP-5_Vision_Sensor.pdf},
    note      = {Workshop demo}
  }
---
<p>Standard Dynamic Vision Sensors (DVS) approximate retinal processing by detecting temporal contrast, offering high speed and dynamic range but omitting key biological mechanisms such as spatial filtering and contrast gain control. We present the first implementation of a multi-stage silicon retina model on the SCAMP-5 Pixel Processor Array (PPA), incorporating center-surround filtering, contrast gain control, and Leaky Integrate-and-Fire spiking directly at the focal plane. To enable broader research, we also provide a GPU-based simulation framework. Evaluating on video saliency prediction, the retina model achieves a 13% lower validation loss than a standard DVS baseline while generating 47% fewer events, demonstrating that biological pre-filtering can produce more efficient representations for downstream semantic tasks.</p>
