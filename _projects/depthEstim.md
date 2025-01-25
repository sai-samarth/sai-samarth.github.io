---
layout: page
title: Object Detection with Depth Estimation
description: Prototype of detecting the closest outdoor object with monocular lens.
img: assets/img/depthEsti.jpg
importance: 2
category:
related_publications: False
---

This repository showcases my team project developed during my internship at NUS with HP. We created an application to assist the visually impaired by providing information about their surroundings. The system utilizes a finetuned YOLOv5 model on selected outdoor object classes and integrates the MiDaS relative depth estimation framework to identify the nearest objects and their classes. This information is conveyed to the user through audio signals, enhancing their ability to navigate outdoor environments effectively.

Later, during my university studies, we applied this project to a practical use case, resulting in a research paper titled "An Assistive Model for the Visually Impaired Integrating the Domains of IoT, Blockchain and Deep Learning." The solution leverages IoT devices, blockchain for secure data transmission, and deep learning for real-time object detection. A camera attached to a Raspberry Pi captures live video frames, which are stored on a private blockchain network. Deep learning models analyze these frames to detect obstacles, and users receive audio notifications with an average response time of under 2 seconds using an RTX 3090 GPU.

Explore the project on [GitHub.](https://github.com/sai-samarth/GAIP_Project)
