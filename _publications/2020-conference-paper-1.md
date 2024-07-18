---
title: "Real-time Survivor Detection in UAV Thermal Imagery based on Deep Learning"
collection: publications
permalink: /publication/2020-conference-paper-1
date: 2020-12-17
venue: 'IEEE 16th International Conference on Mobility, Sensing and Networking (Best Paper Award, CCF-C)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9394263'
---

Unmanned Aerial Vehicles (UAVs) uses evolved significantly due to its high durability, lower costs, easy implementation, and flexibility. After a natural disaster occurs, UAVs can quickly search the affected area to save more survivors. Dataset is crucial in developing a round-the-clock rescue system applying deep learning methods. In this paper, we collected a new thermal image dataset captured by UAV for post-disaster search and rescue (SAR) activities. After that, we employed several different deep convolutional neural networks to train the pedestrian detection models on our datasets, including YOLOV3, YOLOV3-MobileNetV1 and YOLOV3-MobileNetV3. Because the onboard microcomputer has limited computing capacity and memory, for balancing the inference time and accuracy, we find optimal points to prune and fine-tune the network based on the sensitivity of convolutional layers. We validate on NVIDIA's Jetson TX2 and achieve 26.60 FPS (Frames per second) real-time performance.

