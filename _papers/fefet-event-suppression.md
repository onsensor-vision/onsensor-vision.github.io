---
sequence_id: 108
layout: paper
permalink: /html/On-Sensor_Background_Event_Suppression_with_FeFETs.html
title: "On-Sensor Background Event Suppression with FeFETs"
authors: Leo Liu, Brandon Cai, Kwabena Boahen
pdf: /pdf/On-Sensor_Background_Event_Suppression_with_FeFETs.pdf
# supp: /pdf/On-Sensor_Background_Event_Suppression_with_FeFETs_supplementary.pdf
bibtex: |
  @inproceedings{liu2026fefet,
    author    = {Liu, Leo and Cai, Brandon and Boahen, Kwabena},
    title     = {On-Sensor Background Event Suppression with FeFETs},
    booktitle = {CVPR 2026 Workshop on On-Sensor Vision},
    year      = {2026},
    url       = {https://onsensor-vision.github.io/pdf/On-Sensor_Background_Event_Suppression_with_FeFETs.pdf},
    note      = {Workshop extended abstract}
  }
---
<p>Event cameras promise microsecond latency, but background activity from leakage currents and egomotion congests the readout network and inflates latency and jitter. Existing suppression algorithms, which depend on timestamping, precludes pixel-level integration and thus must be relegated to the chip periphery, occuring after event readout. To circumvent this bottleneck, we propose to use dense ferroelectric FETs to detect spatiotemporally-correlated events and reject noise without timestamping. Our simulations show that over 90% of leakage- and egomotion-induced events are suppressed while preserving over 80% of foreground events. That cuts a 140 million events per second stream 14-fold to 10 million events per second, and consequently reduces latency and jitter by a factor 1,000 and 2,500, respectively.</p>
