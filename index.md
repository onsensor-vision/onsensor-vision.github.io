---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: Home
layout: home
---
![](assets/img/banner.jpg)

Many exciting computer vision applications operate at the edge; this could be in drones, IoT devices, or AR/VR systems. These demand visual processing that is fast, energy-efficient, and privacy-preserving. On-sensor vision meets these needs by unifying sensing and computation within a single chip, producing information-rich outputs instead of raw images. By minimizing costly data transfers, such architectures enable real-time, low-power operation. Prototypes like Manchester’s SCAMP integrate sensing, memory, and parallel processing directly on-chip. This workshop explores algorithms and architectures for near-pixel, in-sensor, and stacked sensor-processor devices, and how to best partition computation between on-sensor and off-sensor processing.


### About this Workshop
While much focus in the recent explosion of computer vision has been on cloud-based processing of datasets, some of the most challenging and exciting applications are at the edge, where portable or mobile devices are required to exhibit autonomous operation via sophisticated visual processing using on-board hardware resources. The edge applications bring stringent requirements on operating speed (e.g. latency of processing in a fast-flying drone or a head/gaze tracking in a VR system), low-energy (e.g. power consumption in a battery-operated Internet-of-Things sensor device) or data security (e.g. privacy concerns in a security camera). These requirements are best satisfied when the processing of the data stream from an image sensor happens as close as possible to the sensor itself. Even better than attaching a camera to a dedicated microprocessor or mobile GPU is to unify the sensor and processor into a single device. In the paradigm of on-sensor computer vision we perform processing within the sensor itself, on the same chip; and this chip produces abstract, information-rich output rather than images.

It is now well understood that in a computing system most energy and time cost is associated with data communications — whether transfers of data between subsystems, or within a subsystem itself (e.g. processor-memory transfers in a conventional CPU or GPU). We have already seen prototypes such as the SCAMP project from the University of Manchester where image sensing, processing and memory are closely integrated with processing carried out by a very large number of processor nodes, each equipped with physically co-located memory. Integration of further processing capabilities on the same silicon chip, possibly within the sensor/processor array itself or in a stacked 3D device may enable a significant fraction of a full computer vision stack to be performed very close to sensing pixels, with an abstract output of only “relevant information” to other computing elements within a robot or other system. What is considered “relevant information” depends on the context and application, and a major scientific question to be addressed is how to partition the processing system between the near-sensor computations provided by the pixel-parallel processor array and off-sensor processing hardware.

### Topics 
- Algorithms for on or near sensor computer vision
- Architectures (digital or analogue)
- Efficiency and power usage
- Cellular automata for vision
- On-sensor neural networks
- Bio-inspired vision sensing
- Graph algorithms for fine-grained parallelism
- Single layer and stacked architectures
- Architecture simulators (functional and hardware level)
- Visualisation and graphics for processor and algorithm design
- Programming and learning for processing arrays
- Analog processing for computer vision
- Dividing processing between on-sensor and off-sensor
- Communication between on-sensor and off-sensor processors (bandwidth and direction)