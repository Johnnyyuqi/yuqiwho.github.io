---
title: "Design and implementation of object detection algorithm based on spiking neural network"
collection: research
permalink: /research/object_detection
date: 2023-05-27
venue: 'Object Detection'
---
<video width="560" height="315" controls>
  <source src="{{ site.baseurl }}/images/20230527_121914.mp4" type="video/mp4">
  The result of the spiking object detection
</video>

<div style="text-align: justify;">
Object detection is a popular task in the area of computer vision. It classifies all objects in an image while providing their sizes and positions through bounding boxes. In recent years, object detection has achieved extraordinary performances in many datasets and the accuracy of recognition has reached the level of human beings. However, with the further demand for low energy consumption and biological similarity of neural networks, there comes a trend to use spiking neural networks with low consumption, high efficiency and biological similarityto accomplish computer vision tasks. 
</div>

<br>

<div style="text-align: justify;">
Thus, after investigating the theory of object detection algorithms, spiking neural network and spiking camera, I built the spiking dataset based on the large-scale dataset COCO2017, PASCAL VOC and the tiny-scale dataset which made by myself. Also, I utilized the ANN to SNN transformation algorithm to transform the tailored tiny-yolo into the spiking neural network. After that, I improved the network’s performance with the optimizations such as channel normalization and robust normalization. As a result, the spiking neural network attains a similar performance with one-tenth energy consumption compared to the artificial neural network.
</div>

<figure>
  <img style="width: 100%; height: auto; object-fit: contain;" src="{{ site.baseurl }}/images/spike_accuracy_result.png">
  <figcaption style="text-align: center; font-style: italic;">Figure 1: Accuracy results of the spiking neural network compared to traditional networks.</figcaption>
</figure>
<figure>
  <img style="width: 100%; height: auto; object-fit: contain;" src="{{ site.baseurl }}/images/energy_consumption.jpg">
  <figcaption style="text-align: center; font-style: italic;">Figure 2: Energy consumption comparison between the spiking neural network and the artificial neural network.</figcaption>
</figure>
