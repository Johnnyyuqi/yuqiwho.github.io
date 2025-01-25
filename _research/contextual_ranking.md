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
The initial experiment assessed various contrastive learning frameworks, revealing that the DiffCSE framework slightly outperforms the SimCSE framework. Substituting the pre-trained BERT model with the large language model “OPT-2.3b” can further enhance contrastive learning outcomes. Subsequently, the RankCSE model, which integrates ranking consistency into the framework, yielded additional performance gains. Moreover, the application of ranking distillation, leveraging insights from multiple pre-trained teacher models, demonstrated that an optimal ratio of distilled knowledge (2:1) from DiffCSE and SimCSE maximizes the RankCSE model's efficacy.  Finally, evaluations across different supervisory approaches and ranking algorithms indicated that unsupervised learning combined with ListMLE for parameter updates results in superior performance.
</div>

<div style="text-align: justify;">
The initial experiment assessed various contrastive learning frameworks, revealing that the DiffCSE framework slightly outperforms the SimCSE framework. Substituting the pre-trained BERT model with the large language model “OPT-2.3b” can further enhance contrastive learning outcomes. Subsequently, the RankCSE model, which integrates ranking consistency into the framework, yielded additional performance gains. Moreover, the application of ranking distillation, leveraging insights from multiple pre-trained teacher models, demonstrated that an optimal ratio of distilled knowledge (2:1) from DiffCSE and SimCSE maximizes the RankCSE model's efficacy.  Finally, evaluations across different supervisory approaches and ranking algorithms indicated that unsupervised learning combined with ListMLE for parameter updates results in superior performance.
</div>

<div style="text-align: justify;">
Future research could involve deploying the pre-trained RankCSE model as a retriever in conjunction with large language models such as ChatGPT to assess its efficacy in real-life scenarios.
</div>


<figure>
  <img style="width: 100%; height: auto; object-fit: contain;" src="{{ site.baseurl }}/images/spike_accuracy_result.png">
  <figcaption style="text-align: center; font-style: italic;">Figure 1: Accuracy results of the spiking neural network compared to traditional networks.</figcaption>
</figure>
<figure>
  <img style="width: 100%; height: auto; object-fit: contain;" src="{{ site.baseurl }}/images/energy_consumption.jpg">
  <figcaption style="text-align: center; font-style: italic;">Figure 2: Energy consumption comparison between the spiking neural network and the artificial neural network.</figcaption>
</figure>
