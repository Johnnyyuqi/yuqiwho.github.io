---
title: "Neurite Morphology Analysis"
collection: research
permalink: /research/neurite_analysis
date: 2025-01-03
venue: 'Neurite Analysis'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
---
<div style="text-align: justify;">
Quantitative measurement of neurite reactions to different medicines is often significant for physiological experiments. Currently, most measurements are performed using plugins in ImageJ, which requires extensive manual labeling and is time-consuming. Additionally, most medical image analyses are based on pixel-level characteristics and may overlook morphological features, potentially leading to less accurate results. To address these issues, I designed a pipeline to analyze the neurite area and neuronal survival index. Statistical analysis comparing manual and automatic analysis methods demonstrates that the automatic analysis produces acceptable results.
</div>

<br>

<div style="text-align: justify;">
The most common method for neurite analysis relies on ImageJ's Simple Neurite Tracer plugin, which requires users to manually select soma points for the plugin to trace neurites between them. This process is time-consuming, especially when images contain dozens of soma. To address this limitation, I developed a pipeline for measuring neurite area across the entire image using pixel-level analysis, which includes image type conversion, contrast enhancement, noise reduction, and binarization. To improve analysis accuracy, I incorporated semantic segmentation to enhance the quantitative characteristics of neurites. The neurite contrast was significantly improved after the machine learning model learned morphological features from annotated training images. The neurite area analysis results proved to be acceptable, as the significance tests between groups aligned with manual analysis results, while processing time was reduced from approximately ten minutes to one minute per image.
</div>


<figure>
  <img style="width: 100%; height: auto; object-fit: contain;" src="{{ site.baseurl }}/images/circle_comparison.png">
  <figcaption style="text-align: center; font-style: italic;">From the area within the red circle, we can observe that semantic segmentation enhances the quantitative characterization of the neurite</figcaption>
</figure>

<figure style="text-align: center;">
  <img style="width: 100%; height: auto; object-fit: contain;" src="{{ site.baseurl }}/images/neurite_process.png">
  <figcaption style="text-align: center; font-style: italic;">The designed automatic process pipeline</figcaption>
</figure>

<div style="text-align: justify;">
For normalization and survival index calculation, cell counting is a prerequisite step. I developed a pipeline based on ImageJ's StarDist plugin to recognize cells, incorporating threshold settings to eliminate small particles and generate final count results. Comparison with manual counting demonstrated that the automatic counting method is not only acceptable but achieves superior results due to the implemented image enhancement strategies.
</div>
