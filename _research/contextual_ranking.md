---
title: "Ranking-Aware Contrastive Learning with Large Language Models"
collection: research
permalink: /research/contextual ranking
date: 2023-05-27
venue: 'Retrieval Augmented Generation'
---

<div style="text-align: justify;">
Generating high-quality word and sentence representations is a foundational task in natural language processing (NLP). In recent years, various embedding methodologies have been proposed, notably those leveraging the capabilities of large language models for in-context learning. Research has shown that language model performance can be enhanced by integrating a query with multiple examples. Inspired by this research, this project explores the use of a contrastive learning framework combined with ranking knowledge to enhance the generation and retrieval of sentence embeddings, aiming to more accurately identify the most similar sentences in in-context learning scenarios.  
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
