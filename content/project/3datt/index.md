---
title: Cross-Modality Deep Feature Learning for Brain Tumor Segmentation
summary: This is an implementation of the paper Cross-Modality Deep Feature Learning for Brain Tumor Segmentation published on Pattern Recognition. The "2m_re1" program is for BraTS 2018.
tags:
  - PR
date: 2021-02-20
url_code: 'https://github.com/lixiaopang221/2m_re1'
url_pdf: 'https://ieeexplore.ieee.org/document/9199562/'
url_slides: ''
url_video: ''

authors: ['张鼎文']

date: '2021-02-20T00:00:00Z'
publication: In *Pattern Recognition*

---

Recent advances in machine learning and prevalence of digital medical images have opened up an opportunity to address the challenging brain tumor segmentation (BTS) task by using deep convolutional neural networks. However, different from the RGB image data that are very widespread, the medical image data used in brain tumor segmentation are relatively scarce in terms of the data scale but contain the richer information in terms of the modality property. To this end, this paper proposes a novel cross-modality deep feature learning framework to segment brain tumors from the multi-modality MRI data. The core idea is to mine rich patterns across the multi-modality data to make up for the insufficient data scale. The proposed cross-modality deep feature learning framework consists of two learning processes: the cross-modality feature transition (CMFT) process and the cross-modality feature fusion (CMFF) process, which aims at learning rich feature representations by transiting knowledge across different modality data and fusing knowledge from different modality data, respectively. Comprehensive experiments are conducted on the BraTS benchmarks, which show that the proposed cross-modality deep feature learning framework can effectively improve the brain tumor segmentation performance when compared with the baseline methods and state-of-the-art methods.