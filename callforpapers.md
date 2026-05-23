---
layout: page
title: Abstracts and Demos
permalink: /callforpapers/
---

## Extended Abstracts

<div class="paper-list">

<article class="paper-card">
  <h4 class="paper-title">SNAPPIX: Efficient-Coding–Inspired In-Sensor Compression for Edge Vision</h4>
  <div class="paper-authors">Weikai Lin, Tianrui Ma, Adith Boloor, Yu Feng, Ruofan Xing, Xuan Zhang, Yuhao Zhu</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Energy-efficient imaging is essential for edge sensing, where energy is dominated by in-sensor data readout and wireless transmission. In-sensor compression can reduce this cost but faces challenges in hardware overhead, information loss, and task specificity. Inspired by the mammalian visual system, we present SNAPPIX, an in-sensor compression system that uses coded exposure (CE) for lightweight, sensor-compatible compression; learns a task-agnostic CE pattern by maximizing decorrelation among coded pixels based on efficient coding theory; and co-designs tile-repetitive CE patterns with Vision Transformers, augmented by reconstruction-based pre-training. Evaluating on action recognition and video reconstruction, SNAPPIX outperforms state-of-the-art video-based methods while reducing edge energy by up to 15.4x.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">HoloCode: Hybrid Optical-Electronic Edge Encoding for Privacy-Preserving Cloud Training</h4>
  <div class="paper-authors">Ruofan Xing, Arman Akbari, Weikai Lin, Adith Boloor, Alexander Montes McNeil, Michael Moebius, Yongmin Liu, Yuhao Zhu, Xuan Zhang</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Privacy-preserving machine learning defends against adversaries without sacrificing task accuracy. In latency-critical, resource-constrained settings, existing cryptographic and encoding approaches incur heavy overheads, causing intolerable delays and energy costs. We present <strong>HoloCode</strong>, a hybrid optical–electronic pipeline delivering strong privacy with sub-5ms latency at a fraction of state-of-the-art energy. HoloCode encodes task-relevant signals, shields sensitive features, resists inversion attacks, and locks models with a private key preventing misuse. It builds on an edge–cloud framework pushing inference to the edge to cut latency, at the cost of higher edge energy. To break this, we leverage zero-energy optical processing to reduce latency and energy simultaneously. Against strong baselines, HoloCode achieves <strong>10×</strong> faster inference and <strong>50%</strong> lower edge energy, preserving accuracy while resisting leakage and reconstruction attacks.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">PRIMM: Perception Using Integrated Multi-Modal Modularity</h4>
  <div class="paper-authors">lilian lamb, Mohammadreza Mohammadi, Ramtin Zand</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Embedded vision systems face a fundamental trade-off between high-resolution sensing and limited edge resources. In this paper, we propose the PRIMM system, which addresses this challenge through adaptive, multimodal perception that preserves efficiency while improving robustness. Unlike camera-only pipelines that degrade in low-light or occluded scenes, PRIMM fuses RGB imagery with LiDAR-derived dense depth maps generated near the sensor. Depth maps are constructed through LiDAR-to-camera transformation followed by parallelized chunk-based interpolation, enabling efficient preprocessing on near-sensor compute units. Selective sensor activation further reduces redundant workload by engaging LiDAR only when visual confidence is low. Evaluation across multiple datasets shows that PRIMM improves perception robustness and detection accuracy with minimal impact on energy consumption and latency, demonstrating the effectiveness of near-sensor multimodal fusion for adaptive embedded vision.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">From Retina to Silicon: The IRIS Framework for Bio-inspired Visual Intelligence</h4>
  <div class="paper-authors">Subhradip Chakraborty, Shay Snyder, Maryam Parsa, Gregory W Schwartz, Akhilesh Jaiswal</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Traditional frame-based vision systems are ill-suited for extreme-edge intelligence due to high bandwidth, latency, and power overheads. The IRIS framework overcomes these limits through a unified neuroscience, software, and hardware co-design. Inspired by mammalian retinal circuitry, IRIS embeds multiple key visual functions: object motion sensitivity, looming detection, and motion prediction, directly into the image sensor. Using spatio-temporal filtering and predictive coding, it enables efficient mixed-signal CMOS implementations. Leveraging 3D-integration scheme, IRIS delivers real-time, event-driven feature extraction at lower latency, power, and complexity, enabling sensor-level bio-inspired visual intelligence. Our results highlight that IRIS maintains 98% feature fidelity while integrating three individual visual functions and reducing energy consumption by 2.41×.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">Should Sensors Output Raw Images? Content-Adaptive Warping as On-Sensor Preprocessing for Semantic Segmentation</h4>
  <div class="paper-authors">Mayank Singal</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Vision sensors capture images at uniform spatial resolution, allocating equal pixels to featureless sky and to intricate object boundaries. This is wasteful: downstream tasks like semantic segmentation struggle at boundaries and fine structures, not at uniform regions. We ask a question central to on-sensor vision: what should a sensor output instead of a raw image? Our answer is a content-adaptively warped image. A Sobel filter computes gradient magnitude (a pixel-parallel operation native to processor arrays), and the resulting map drives a rectilinear warp that reallocates resolution toward visually complex regions. This warped image, together with its horizontal flip (a trivial on-sensor read-order reversal), forms a pair of content-adaptive views that can be transmitted instead of the raw capture. Off-sensor, a segmentation model processes both views and averages the predictions, following the standard two-pass inference pipeline. The difference is that both views are now information-rich: one concentrates resolution at boundaries and textures, the other adds geometric diversity via flipping. Across Cityscapes, ADE20K, and UAVid with three segmentation architectures, this on-sensor warping improves downstream mIoU by 0.75–1.22 points (1.9–5.9× the gain of the standard raw-image-plus-flip pipeline), with zero additional neural network cost.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">ORBCam: In-Sensor ORB Feature Processing for Ultra-Low-Power Visual-Inertial Odometry</h4>
  <div class="paper-authors">Yiwen Liang, Yuxiang Peng, Guoquan Huang, Weidong Cao, Chuchu Chen</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>In visual–inertial odometry (VIO) systems, image readout and data movement between sensor and processor are increasingly recognized as the dominant power bottleneck, overshadowing on-chip computation. To address this, we present ORBCam, a cross-layer sensor–estimator co-design that eliminates image readout and directly generates motion-required feature measurements within the sensor subsystem. Instead of exporting images or descriptors, ORBCam transmits only quantized pixel coordinates and flow measurements to the host. In system-level simulations at 752 × 480 resolution and 100 FPS, ORBCam is compared against a conventional image sensor consuming 7.88 mW for full-frame acquisition and transmission. ORBCam reduces sensing power to 0.59 mW, achieving up to 13.3× energy efficiency improvement while maintaining comparable odometry accuracy.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">Rethinking Super-Resolution for Near-Sensor Object Detection</h4>
  <div class="paper-authors">Lingjia Shi, Jinendra Malekar, Ramtin Zand</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Deploying computer vision models on edge devices requires carefully balancing accuracy, latency, and data movement. In this work, we investigate super-resolution (SR) not as a means to improve visual quality, but as a near-sensor preprocessing primitive for optimizing end-to-end system efficiency in object detection pipelines. We introduce a split SR framework based on a lightweight hierarchical architecture (Swin-HIER), where the encoder is deployed near the sensor to generate compact feature representations, and the decoder operates on the edge device. This design reduces the need to transmit full-resolution images over bandwidth-limited wireless links, thereby lowering overall latency.</p>
    <p>Through experiments on the COCO dataset using a lightweight detector (YOLO26n), we show that applying 2× SR without retraining leads to only a modest drop in detection performance (from 0.401 to 0.369 mAP@[0.5:0.95]), indicating that SR preserves competitive accuracy despite introducing a distribution shift. At the same time, system-level evaluation on NVIDIA Jetson hardware demonstrates up to 1.26× latency reduction compared to conventional pipelines that transmit raw images. Our results suggest that, in standard-resolution regimes, SR is more effective as a system optimization tool than as a performance enhancer. This work highlights the importance of co-designing data representation, model architecture, and deployment strategy for efficient edge vision systems.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">Cellular Inference Layers for On-Sensor Semantic Segmentation: Convergence Guarantees and Energy Efficiency</h4>
  <div class="paper-authors">Kaustubh S. Bukkapatnam</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>On-sensor vision promises drastically reduced latency and energy consumption by moving inference onto the image sensor itself. Pixel Processor Arrays (PPAs) realise this promise through a dense grid of processing elements that execute a single SIMD instruction stream, communicating only with their four nearest neighbours. We introduce Cellular Inference Layers (CIL), a recurrent computation primitive designed to respect these SIMD and locality constraints. Each CIL step applies a spatially uniform, neighbor-aggregating affine map followed by a ReLU activation. We prove (i) that CIL iteration converges to a unique fixed point whenever the spectral norms of the weight matrices satisfy a simple sufficient condition; (ii) that the effective receptive field grows linearly with the number of iterations; and (iii) a closed-form bound on the fixed-point perturbation caused by <em>q</em>-bit weight quantisation. Evaluated on Cityscapes semantic segmentation, a 16-iteration CIL with four feature channels achieves 41.4% mIoU on the 19-class validation set, while consuming an estimated (≈30×) less energy than off-sensor MobileNetV2-based inference. Our theoretical framework provides practitioners with interpretable design rules for trading iteration count, channel capacity, and weight precision.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">PixVOD: Pixel-Distributed Direct Visual Odometry and Depth Estimation</h4>
  <div class="paper-authors">Shinjeong Kim, Paul H. J. Kelly, Andrew J. Davison</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Images composed of 2D pixel arrays are the standard input to computer vision algorithms, yet many underlying computations can be distributed across pixels. Transmitting raw, redundant, and noisy pixel data off the sensor remains inefficient, motivating a shift toward focal-plane sensor-processors that perform a significant part of the computation directly within each pixel. We envision pixels synthesizing higher-level signals locally, reducing downstream load, and providing richer inputs for higher-level vision tasks.</p>
    <p>We propose a fully parallelizable form of visual odometry and depth estimation across pixels, where sensor-processors exchange information through Gaussian Belief Propagation (GBP) to achieve consensus about camera motion and infer depth from per-pixel photometric observations and a surface normal prior. To maintain geometric stability during optimization, we introduce a keyframe-like anchoring mechanism that regulates the effective baseline between frames, enabling consistent motion and depth updates. Our method is evaluated on realistic datasets, demonstrating the feasibility of GBP-based pixel-level distributed odometry and depth estimation with keyframe anchoring on-sensor.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">Rotation-Robust On-Sensor Feature Tracking via In-Pixel Shear Compensation</h4>
  <div class="paper-authors">Anirudh Kannan</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Descriptor-In-Pixel (DIP) tracking exploits the massively parallel architecture of Pixel Processor Arrays (PPAs) to perform high-speed feature tracking entirely on-sensor. However, the binary ring descriptors used by DIP are inherently rotation-sensitive: a rotation of as little as 5° causes the loss of over 60% of tracked features in the baseline system. We present a PPA-compatible pre-rotation compensation pipeline that applies an inverse in-plane rotation to each query frame, via integer 3-shear decomposition, before descriptor computation. The shear operations are expressible as uniform per-row and per-column pixel shifts, preserving PPA locality and SIMD-style parallelism with no global operations or learned components. Evaluated on real KITTI imagery under controlled synthetic rotations of 0°–45°, our method raises mean feature survival from 26.5% to 60.0% on a highway sequence and from 12.6% to 50.5% on a turning sequence, with peak survival gains of +55% and +59% at 10° respectively. The compensation assumes the rotation angle is known upstream (e.g. from an IMU), and the entire pipeline remains executable within the PPA computational model.</p>
  </details>
</article>

</div>

## Demos

<div class="paper-list">

<article class="paper-card">
  <h4 class="paper-title">Silicon Retina on Pixel Processor Array</h4>
  <div class="paper-authors">Maciej Lewandowski, Prince Philip, André van Schaik, Piotr Dudek</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Standard Dynamic Vision Sensors (DVS) approximate retinal processing by detecting temporal contrast, offering high speed and dynamic range but omitting key biological mechanisms such as spatial filtering and contrast gain control. We present the first implementation of a multi-stage silicon retina model on the SCAMP-5 Pixel Processor Array (PPA), incorporating center-surround filtering, contrast gain control, and Leaky Integrate-and-Fire spiking directly at the focal plane. To enable broader research, we also provide a GPU-based simulation framework. Evaluating on video saliency prediction, the retina model achieves a 13% lower validation loss than a standard DVS baseline while generating 47% fewer events, demonstrating that biological pre-filtering can produce more efficient representations for downstream semantic tasks.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">Segment This Thing, Bit by Bit</h4>
  <div class="paper-authors">Maciej Lewandowski, Shinjeong Kim, Nicholas Fry, Piotr Dudek, Paul H. J. Kelly, Andrew J. Davison</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Inspired by biological vision, where foveated retina and early neural circuits compress visual input before it leaves the eye, we implement a point-directed segmentation pipeline based on the "Segment This Thing" architecture on a custom bit-serial, near-memory SIMD processor array. The hardware is prototyped on an Xilinx KV260 FPGA, and consists of 2,304 processing elements with bit-flexible arithmetic capabilities. We co-design the model and hardware using a Python instruction-set simulator and verify them against a cycle-accurate RTL co-simulation, which enables rapid iteration without synthesis. Foveated tokenisation reduces the input from 64 to 10 tokens (≈85% reduction), while preserving resolution near the query point. To our knowledge, this is the first implementation of a transformer encoder on a pixel processor array-like system.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">Demonstration of a Logarithmic Image Sensor with On-Chip Normal Flow Compute</h4>
  <div class="paper-authors">Mika Laiho, Ari Paasio, Eero Lehtonen, Petteri Mäki, Mika Kutila, Mika Grönroos, Tuomo Komulainen, Tero Säntti, Kalle Paasio, Jonne Poikonen</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>We demonstate RECER R1 chip that has 880x480 logarithmic HDR pixels accompanied with on-chip column-parallel normal flow compute. Visitors can interact with the demo by holding and moving the RECER R1 camera, observe the results of the normal flow compute, as well as the logarithmic HDR intensity image provided by the sensor.</p>
  </details>
</article>

<article class="paper-card">
  <h4 class="paper-title">On-Sensor Background Event Suppression with FeFETs</h4>
  <div class="paper-authors">Leo Liu, Brandon Cai, Kwabena Boahen</div>
  <details class="schedule-abstract">
    <summary>Abstract</summary>
    <p>Event cameras promise microsecond latency, but background activity from leakage currents and egomotion congests the readout network and inflates latency and jitter. Existing suppression algorithms, which depend on timestamping, precludes pixel-level integration and thus must be relegated to the chip periphery, occuring after event readout. To circumvent this bottleneck, we propose to use dense ferroelectric FETs to detect spatiotemporally-correlated events and reject noise without timestamping. Our simulations show that over 90% of leakage- and egomotion-induced events are suppressed while preserving over 80% of foreground events. That cuts a 140 million events per second stream 14-fold to 10 million events per second, and consequently reduces latency and jitter by a factor 1,000 and 2,500, respectively.</p>
  </details>
</article>

</div>

## <s>Call for Abstracts and Demos</s>

<p style="color: red;"><strong>The submission and review periods are now closed.</strong></p>

We invite submissions of **extended abstracts** and **live demonstrations** showcasing novel work in on-sensor and near-sensor vision. This is an opportunity to present early-stage research, works-in-progress, recently published results, or hardware prototypes to an audience of researchers working at the intersection of computer vision, computer architecture, and near-memory processing.

Accepted works will be published on the On-Sensor Vision CVPR 2026 workshop website but will **not** appear in the official CVPR 2026 proceedings.

### Submission Format

We welcome **2-4 page submissions** (excluding citations) describing either:
- **Extended abstracts** presenting novel algorithms, architectures, or results
- **Demonstrations** of hardware prototypes or system implementations

Please use the [official CVPR LaTeX template](https://github.com/cvpr-org/author-kit) for your submission. Submit a **single PDF file** that clearly indicates whether the work will be presented as a poster or demonstration.

**Demonstrations are strongly encouraged** and will be given dedicated exhibition space during the workshop.

### Topics of Interest 
We welcome submissions on all aspects of on-sensor vision, including but not limited to: 

**Algorithms and Methods:**
- Algorithms for on or near sensor computer vision
- Cellular automata for vision
- On-sensor neural networks
- Bio-inspired vision sensing
- Graph algorithms for fine-grained parallelism
- Programming and learning for processing arrays
- Analog processing for computer vision

**Architectures and Systems:**
- Architectures for on-sensor / near-sensor (digital or analogue)
- Single layer and stacked architectures
- Architecture simulators (functional and hardware level)
- Dividing processing between on-sensor and off-sensor
- Communication between on-sensor and off-sensor processors (bandwidth and direction)

### Submission Guidelines

**Timeline:**
- **Submission deadline:** April 10, 2026
- **Notification of acceptance:** April 17, 2026
- **Camera-ready deadline:**  May 15, 2026

**Submission Portal:**
[OpenReview OSV Workshop Website](https://openreview.net/group?id=thecvf.com/CVPR/2026/Workshop/OSV)
<!-- The submission portal is being finalized. We will update this page once the portal is available. -->
