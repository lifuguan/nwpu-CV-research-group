---
title: Colar: Effective and Efficient Online Action Detection by Consulting Exemplars
summary: This repository is the official implementation of Colar. In this work, we study the online action detection and develop an effective and efficient exemplar-consultation mechanism. Paper from arXiv.
tags:
  - CVPR
date: 2022-03-01
url_code: 'https://github.com/VividLe/Online-Action-Detection'
url_pdf: 'https://arxiv.org/abs/2203.01057'
url_slides: 'Colar-Poster.pptx'
url_video: ''

authors: ['杨乐']

date: '2022-03-01T00:00:00Z'
publication: In *IEEE / CVF Computer Vision and Pattern Recognition Conference*

---

Online action detection has attracted increasing research interests in recent years. Current works model historical dependencies and anticipate the future to perceive the action evolution within a video segment and improve the detection accuracy. However, the existing paradigm ignores category-level modeling and does not pay sufficient attention to efficiency. Considering a category, its representative frames exhibit various characteristics. Thus, the category-level modeling can provide complimentary guidance to the temporal dependencies modeling. This paper develops an effective exemplar-consultation mechanism that first measures the similarity between a frame and exemplary frames, and then aggregates exemplary features based on the similarity weights. This is also an efficient mechanism, as both similarity measurement and feature aggregation require limited computations. Based on the exemplar-consultation mechanism, the long-term dependencies can be captured by regarding historical frames as exemplars, while the category-level modeling can be achieved by regarding representative frames from a category as exemplars. Due to the complementarity from the category-level modeling, our method employs a lightweight architecture but achieves new high performance on three benchmarks. In addition, using a spatio-temporal network to tackle video frames, our method makes a good trade-off between effectiveness and efficiency. Code is available at https://github.com/VividLe/Online-Action-Detection.
