---
sequence_id: 3
speaker: Dr. Mika Laiho
webpage: https://kovilta.fi/
affil: Kovilta
affil_link: https://kovilta.fi/
img: mika_laiho.png
title: "On-Sensor Computer Vision: Heterogeneous Architectures for Low-Latency Perception"
time: 9:30 - 10:00
---
On-sensor computing is emerging as a powerful approach to reducing latency, energy consumption, and off-chip data transfers in modern vision systems. By integrating sensing and computation on the same chip, it enables real-time perception directly at the source of data. However, this integration also introduces new design constraints, including limited flexibility, shared manufacturing technology, and tight area budgets—requiring a fundamental rethinking of both hardware architectures and their coupling to vision algorithms.
In this talk, I will explore heterogeneous on-sensor computer vision architectures, focusing on latency-critical applications such as collision avoidance in autonomous drones, robots, and vehicles. I will discuss how efficient hardware–algorithm co-design and careful dataflow planning can eliminate bottlenecks and reduce intermediate storage.
As a case study, I will present a prototype heterogeneous on-sensor vision chip (RECER S1), which integrates a 640×480 pixel array with multiple specialized computing cores, including pitch-matched column-parallel processing units, a 2D cellular neural network, associative memory, and an embedded RISC-V processor. I will explain how its key architectural choices and dataflow strategy enable low-latency processing directly on the sensor.