---
title: Clrnet:Component-level refinement network for deep face parsing
summary: Face parsing aims to assign pixel-wise semantic labels to different facial components (e.g., hair, brows, and lips) in given face images. 
tags:
  - TNNLS
date: 2021-08-31
url_code: ''
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9525038&tag=1'
url_slides: ''
url_video: ''

authors: ['黄培亮']

date: '2021-08-31T00:00:00Z'
publication: In *IEEE Transactions on Neural Networks and Learning System*

---

Face parsing aims to assign pixel-wise semantic labels to different facial components (e.g., hair, brows, and lips) in given face images. However, directly predicting pixel-level labels for each facial component over the whole face image would obtain limited accuracy, especially for tiny facial components. To address this problem, some recent works propose to first crop tiny patches from the whole face image and then predict masks for each facial component. However, such cropping-and-segmenting strategy consists of two independent stages, which cannot be jointly optimized. Besides, as one valuable piece of information for parsing the highly structured facial components, context cues are not elaborately explored by the existing works. To address these issues, we propose a component-level refinement network (CLRNet) for precisely segmenting out each facial component. Specifically, we introduce an attention mechanism to bridge the two independent stages together and form an end-to-end trainable pipeline for face parsing. Furthermore, we incorporate the global context information into the refining process for each cropped facial component patch, providing informative cues for accurate parsing. Extensive experiments are carried out on two benchmark datasets, LFW-PL and HELEN. The results demonstrate the superiority of the proposed CLRNet over other state-of-the-art methods, especially for tiny facial components.
