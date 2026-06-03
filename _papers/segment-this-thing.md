---
sequence_id: 112
layout: paper
permalink: /html/Segment_This_Thing_Bit_by_Bit.html
title: "Segment This Thing, Bit by Bit"
authors: Maciej Lewandowski, Shinjeong Kim, Nicholas Fry, Piotr Dudek, Paul H. J. Kelly, Andrew J. Davison
# pdf: /pdf/Segment_This_Thing_Bit_by_Bit.pdf   # full paper not provided yet -> [pdf] shown greyed/disabled
# supp: /pdf/Segment_This_Thing_Bit_by_Bit_supplementary.pdf
bibtex: |
  @inproceedings{lewandowski2026segment,
    author    = {Lewandowski, Maciej and Kim, Shinjeong and Fry, Nicholas and Dudek, Piotr and Kelly, Paul H. J. and Davison, Andrew J.},
    title     = {Segment This Thing, Bit by Bit},
    booktitle = {CVPR 2026 Workshop on On-Sensor Vision},
    year      = {2026},
    url       = {https://onsensor-vision.github.io/pdf/Segment_This_Thing_Bit_by_Bit.pdf},
    note      = {Workshop demo}
  }
---
<p>Inspired by biological vision, where foveated retina and early neural circuits compress visual input before it leaves the eye, we implement a point-directed segmentation pipeline based on the "Segment This Thing" architecture on a custom bit-serial, near-memory SIMD processor array. The hardware is prototyped on an Xilinx KV260 FPGA, and consists of 2,304 processing elements with bit-flexible arithmetic capabilities. We co-design the model and hardware using a Python instruction-set simulator and verify them against a cycle-accurate RTL co-simulation, which enables rapid iteration without synthesis. Foveated tokenisation compresses the input image into just 40 tokens, achieving an 84% reduction in memory while preserving resolution around the query point. To our knowledge, this is the first implementation of a foveated transformer encoder on a pixel processing device.</p>
