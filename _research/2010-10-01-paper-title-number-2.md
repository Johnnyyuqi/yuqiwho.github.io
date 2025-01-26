---
title: "Paper Title Number 2"
collection: research
permalink: /research/2010-10-01-paper-title-number-2
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2010-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Quantitative measurement of neurite reactions to different medicines is often significant for physiological experiments. Currently, most measurements are performed using plugins in ImageJ, which requires extensive manual labeling and is time-consuming. Additionally, most medical image analyses are based on pixel-level characteristics and may overlook morphological features, potentially leading to less accurate results. To address these issues, I designed a pipeline to analyze the neurite area and neuronal survival index. Statistical analysis comparing manual and automatic analysis methods demonstrates that the automatic analysis produces acceptable results.

The most common method for neurite analysis relies on ImageJ's Simple Neurite Tracer plugin, which requires users to manually select soma points for the plugin to trace neurites between them. This process is time-consuming, especially when images contain dozens of soma. To address this limitation, I developed a pipeline for measuring neurite area across the entire image using pixel-level analysis, which includes image type conversion, contrast enhancement, noise reduction, and binarization. To improve analysis accuracy, I incorporated semantic segmentation to enhance the quantitative characteristics of neurites. The neurite contrast was significantly improved after the machine learning model learned morphological features from annotated training images. 

[Download paper here](http://academicpages.github.io/files/paper2.pdf)

Recommended citation: Your Name, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2).
