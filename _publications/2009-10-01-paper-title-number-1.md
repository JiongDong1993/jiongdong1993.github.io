---
title: "UAV-based Real-time Survivor Detection System in Post-disaster Search and Rescue Operations"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
date: 2021-05-25
venue: 'IEEE Journal on Miniaturization for Air and Space Systems'
---

Unmanned Aerial Vehicles (UAVs) uses evolved significantly due to its high durability, lower costs, easy implementation, and flexibility. After a natural disaster occurs, UAVs can quickly search the affected area to save more survivors. Dataset is crucial in developing a round-the-clock rescue system applying deep learning methods. In this paper, we collected a new thermal image dataset captured by UAV for post-disaster search and rescue (SAR) activities. After that, we employed several different deep convolutional neural networks to train the pedestrian detection models on our datasets, including YOLOV3, YOLOV3-MobileNetV1 and YOLOV3-MobileNetV3. Because the onboard microcomputer has limited computing capacity and memory, for balancing the inference time and accuracy, we find optimal points to prune and fine-tune the network based on the sensitivity of convolutional layers. We validate on NVIDIA's Jetson TX2 and achieve 26.60 FPS (Frames per second) real-time performance.
