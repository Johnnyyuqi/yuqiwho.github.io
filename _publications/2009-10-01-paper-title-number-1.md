---
title: "Design and implementation of object detection algorithm based on spiking neural network"
permalink: /publication/2023
venue: 'Object Detection'
---

Object detection is a popular task in the area of computer vision. It classifies all objects in an image while providing their sizes and positions through bounding boxes. In recent years, object detection has achieved extraordinary performances in many datasets and the accuracy of recognition has reached the level of human beings. However, with the further demand for low energy consumption and biological similarity of neural networks, there comes a trend to use spiking neural networks with low consumption, high efficiency and biological similarityto accomplish computer vision tasks. 
Thus, after investigating the theory of object detection algorithms, spiking neural network and spiking camera, I built the spiking dataset based on the large-scale dataset 
COCO2017, PASCAL VOC and the tiny-scale dataset which made by myself. Also, I utilized the ANN to SNN transformation algorithm to transform the tailored tiny-yolo into the spiking neural network. After that, I improved the network’s performance with the optimizations such as channel normalization and robust normalization. As a result, the spiking neural network attains a similar performance with one-tenth energy consumption compared to the artificial neural network.
