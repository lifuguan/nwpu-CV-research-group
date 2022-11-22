---
title: Scribble-Supervised Video Object Segmentation
summary: Recently, video object segmentation has received great attention in the computer vision community. Most of the existing methods heavily rely on the pixel-wise human annotations, which are expensive and time-consuming to obtain.
tags:
  - JAS
date: 2022-02-02
url_code: ''
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9500146'
url_slides: ''
url_video: ''

authors: ['黄培亮']

date: '2022-02-02T00:00:00Z'
publication: In *IEEE/CAA JOURNAL OF AUTOMATICA SINICA*

---

Recently, video object segmentation has received great attention in the computer vision community. Most of the existing methods heavily rely on the pixel-wise human annotations, which are expensive and time-consuming to obtain. To tackle this problem, we make an early attempt to achieve video object segmentation with scribble-level supervision, which can alleviate large amounts of human labor for collecting the manual annotation. However, using conventional network architectures and learning objective functions under this scenario cannot work well as the supervision information is highly sparse and incomplete. To address this issue, this paper introduces two novel elements to learn the video object segmentation model. The first one is the scribble attention module, which captures more accurate context information and learns an effective attention map to enhance the contrast between foreground and background. The other one is the scribble-supervised loss, which can optimize the unlabeled pixels and dynamically correct inaccurate segmented areas during the training stage. To evaluate the proposed method, we implement experiments on two video object segmentation benchmark datasets, YouTube-video object segmentation (VOS), and densely annotated video segmentation (DAVIS)-2017. We first generate the scribble annotations from the original per-pixel annotations. Then, we train our model and compare its test performance with the baseline models and other existing works. Extensive experiments demonstrate that the proposed method can work effectively and approach to the methods requiring the dense per-pixel annotations.