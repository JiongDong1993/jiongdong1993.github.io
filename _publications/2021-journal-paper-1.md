---
title: "UAV-based Real-time Survivor Detection System in Post-disaster Search and Rescue Operations"
collection: publications
permalink: /publication/2021-journal-paper-1
date: 2021-05-25
venue: 'IEEE Journal on Miniaturization for Air and Space Systems'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9440534'
---

When a natural disaster occurs, the most critical task is to search and rescue trapped people as soon as possible. In recent years, unmanned aerial vehicles (UAVs) have been widely employed because of their high durability, low cost, ease of implementation, and flexibility. In this article, we collected a new thermal image dataset captured by drones. After that, we used several different deep convolutional neural networks to train survivor detection models on our dataset, including YOLOV3, YOLOV3-MobileNetV1, and YOLOV3- MobileNetV3. Due to the limited computing power and memory of the onboard microcomputer, to balance the inference time and accuracy, we found the optimal points to prune and fine-tune the survivor detection network based on the sensitivity of the convolutional layer. We verified it on NVIDIA’s Jetson TX2 and achieved a real-time performance of 26.60 frames/s (FPS). Moreover, we designed a real-time survivor detection system based on DJI Matrice 210 and Manifold 2-G to provide search and rescue services after the disaster.
