![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Devraux.ImageProcessingToolset)

# Image Processing Toolkit (C++ for Raspberry Pi Zero 2 W)

## Overview

This project is a C++ library implementing a collection of practical and useful image processing algorithms, designed with a focus on performance and efficiency on embedded hardware, specifically the Raspberry Pi Zero 2 W.

The goal is to build a dedicated and reusable set of algorithms that can be applied in real-world scenarios, with particular emphasis on understanding their computational cost and behavior under constrained resources. Each implemented method is evaluated in terms of performance, providing insight into achievable throughput and suitability for tasks such as real-time image processing.

The library is intended to serve as a foundation for systems that operate on image data streams, including applications like camera-based processing pipelines where predictable performance and low overhead are critical.

## Scope

The project does not aim to fully reproduce existing libraries or cover all known algorithms. Instead, it focuses on implementing selected techniques that are considered:

- practically useful,
- computationally interesting,
- relevant for embedded or real-time applications.

Algorithms are implemented from scratch with attention to clarity, control over data representation, and performance characteristics on the target platform.

## Performance Considerations

All implementations are designed and tested with the Raspberry Pi Zero 2 W in mind. The project includes evaluation of:

- execution time,
- memory usage,
- scalability with image resolution,
- feasibility of real-time processing.

These benchmarks help determine which algorithms are suitable for deployment in continuous image processing pipelines.

## References

The implementations in this project are based on selected concepts and algorithms described in:

- *Digital Image Processing* — Rafael C. Gonzalez, Richard E. Woods  
- *Computer Vision: Algorithms and Applications (2nd Edition)* — Richard Szeliski  

Only a subset of algorithms from these references is implemented, focusing on those that are most relevant or applicable in practice.

## Purpose

The long-term objective of this project is to provide a compact, efficient, and well-understood image processing library that can be directly used in embedded systems, including real-time camera processing on low-power hardware.
