---
title: Incremental Cross-view Mutual Distillation for Self-supervised Medical CT Synthesis
summary: This paper aims at building a medical slice synthesis model to increase the inter-slice resolution of an input 3D volume.
tags:
  - CVPR
date: 2021-12-10
url_code: 'https://github.com/wangliang88/cvpr_ct_synthesis'
url_pdf: 'https://arxiv.org/pdf/2112.10325'
url_slides: '3827_poster.pdf'
url_video: '202207261910.mp4'

authors: ['方超伟']

date: '2022-06-01T00:00:00Z'
publication: In *IEEE / CVF Computer Vision and Pattern Recognition Conference*

---

{{< video src="202207261910.mp4" controls="yes" >}}

Considering that the ground-truth intermediate medical slices are always absent in clinical practice, we introduce the incremental cross-view mutual distillation strategy to accomplish this task in the self-supervised learning manner. Specifically, we model this problem from three different views: slice-wise interpolation from axial view and pixel-wise interpolation from coronal and sagittal views. Under this circumstance, the models learned from different views can distill valuable knowledge to guide the learning processes of each other. We can repeat this process to make the models synthesize intermediate slice data with increasing inter-slice resolution.
