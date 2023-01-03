---
title: Exploring Task Structure for Brain Tumor Segmentation From Multi-Modality MR Images
summary: This is an implementation of the paper Exploring Task Structure for Brain Tumor Segmentation From Multi-Modality MR Images published on IEEE Transaction on Image Processing.
tags:
  - TIP
date: 2020-09-17
url_code: 'https://github.com/lixiaopang221/3datt'
url_pdf: 'https://pubmed.ncbi.nlm.nih.gov/32941137/'
url_slides: ''
url_video: ''

authors: ['张鼎文']

date: '2020-09-17T00:00:00Z'
publication: In *IEEE Transaction on Image Processing*

---

Brain tumor segmentation, which aims at segmenting the whole tumor area, enhancing tumor core area, and tumor core area from each input multi-modality bioimaging data, has received considerable attention from both academia and industry. However, the existing approaches usually treat this problem as a common semantic segmentation task without taking into account the underlying rules in clinical practice. In reality, physicians tend to discover different tumor areas by weighing different modality volume data. Also, they initially segment the most distinct tumor area, and then gradually search around to find the other two. We refer to the first property as the task-modality structure while the second property as the task-task structure, based on which we propose a novel task-structured brain tumor segmentation network (TSBTS net). Specifically, to explore the task-modality structure, we design a modality-aware feature embedding mechanism to infer the important weights of the modality data during network learning. To explore the tasktask structure, we formulate the prediction of the different tumor areas as conditional dependency sub-tasks and encode such dependency in the network stream. Experiments on BraTS benchmarks show that the proposed method achieves superior performance in segmenting the desired brain tumor areas while requiring relatively lower computational costs, compared to other state-of-the-art methods and baseline models.