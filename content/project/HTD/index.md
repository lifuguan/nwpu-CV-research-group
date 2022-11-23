---
title: HTD:Heterogeneous Task Decoupling for Two-stage Object Detection
summary: Decoupling the sibling head has recently shown great potential in relieving the inherent task-misalignment problem in two-stage object detectors. However, existing works design similar structures for the classification and regression, ignoring task-specific characteristics and feature demands. 
tags:
  - TIP
date: 2022-03-08
url_code: 'https://github.com/CityU-AIM-Group/HTD'
url_pdf: 'https://ieeexplore.ieee.org/document/9615001'
url_slides: ''
url_video: ''

authors: ['张鼎文']

date: '2022-03-08T00:00:00Z'
publication: In *IEEE Transactions on Image Processing*

---

Decoupling the sibling head has recently shown great potential in relieving the inherent task-misalignment problem in two-stage object detectors. However, existing works design similar structures for the classification and regression, ignoring task-specific characteristics and feature demands. Besides, the shared knowledge that may benefit the two branches is neglected, leading to potential excessive decoupling and semantic inconsistency. To address these two issues, we propose Heterogeneous task decoupling (HTD) framework for object detection, which utilizes a Progressive Graph (PGraph) module and a Border-aware Adaptation (BA) module for task-decoupling. Specifically, we first devise a Semantic Feature Aggregation (SFA) module to aggregate global semantics with image-level supervision, serving as the shared knowledge for the task-decoupled framework. Then, the PGraph module performs progressive graph reasoning, including local spatial aggregation and global semantic interaction, to enhance semantic representations of region proposals for classification. The proposed BA module integrates multi-level features adaptively, focusing on the low-level border activation to obtain representations with spatial and border perception for regression. Finally, we utilize the aggregated knowledge from SFA to keep the instance-level semantic consistency (ISC) of decoupled frameworks. Extensive experiments demonstrate that HTD outperforms existing detection works by a large margin, and achieves single-model 50.4%AP and 33.2% AP s on COCO test-dev set using ResNet-101-DCN backbone, which is the best entry among state-of-the-arts under the same configuration.

