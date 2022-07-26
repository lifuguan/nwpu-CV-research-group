---
title: Robust Region Feature Synthesizer for Zero-Shot Object Detection
summary: We design a unified region feature synthesizer for feature synthesizing in real-world detection scenarios.
tags:
  - CVPR
date: 2022-06-01
url_code: 'https://github.com/HPL123/RRFS'
url_pdf: 'https://arxiv.org/abs/2203.01057'
url_slides: '3827_poster.pdf'
url_video: '1658710652088375.mp4'

authors: ['黄培亮']

date: '2022-06-01T00:00:00Z'
publication: In *IEEE / CVF Computer Vision and Pattern Recognition Conference*

---

{{< video src="1658710652088375.mp4" controls="yes" >}}

Zero-shot object detection aims at incorporating class semantic vectors to realize the detection of (both seen and) unseen classes given an unconstrained test image. In this study, we reveal the core challenges in this research area how to synthesize robust region features (for unseen objects) that are as intra-class diverse and inter-class separable as the real samples, so that strong unseen object detectors can be trained upon them. To address these challenges, we build a novel zero-shot object detection framework that contains an Intra-class Semantic Diverging component and an Inter-class Structure Preserving component. The former is used to realize the one-to-more mapping to obtain diverse visual features from each class semantic vector, preventing miss-classifying the real unseen objects as image backgrounds. While the latter is used to avoid the synthesized features too scattered to mix up the inter-class and foreground-background relationship. To demonstrate the effectiveness of the proposed approach, comprehensive experiments on PASCAL VOC, COCO, and DIOR datasets are conducted. Notably, our approach achieves the new state-of-the-art performance on PASCAL VOC and COCO and it is the first study to carry out zero-shot object detection in remote sensing imagery.
