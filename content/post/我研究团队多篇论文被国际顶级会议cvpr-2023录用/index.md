---
title: One Paper Have Been Accepted by CVPR 2023
date: 2023-03-24T03:42:32.972Z
draft: false
featured: false

---
CVPR 2023 officially released the list of accepted papers. Dr. Li's paper from our team is included.

<!--more-->

## Boosting Low-Data Instance Segmentation by Unsupervised Pre-training with Saliency Prompt

Authors：李昊，张鼎文，韩军伟

Recently, inspired by DETR variants, query-based end-to-end instance segmentation (QEIS) methods have outperformed CNN-based models on large-scale datasets. Yet they would lose efficacy when only a small amount of training data is available since it's hard for the crucial queries/kernels to learn localization and shape priors. To this end, this work offers a novel unsupervised pre-training solution for low-data regimes. Inspired by the recent success of the Prompting technique, we introduce a new pre-training method that boosts QEIS models by giving Saliency Prompt for queries/kernels. Our method contains three parts: 1) Saliency Masks Proposal is responsible for generating pseudo masks from unlabeled images based on the saliency mechanism. 2) Prompt-Kernel Matching transfers pseudo masks into prompts and injects the corresponding localization and shape priors to the best-matched kernels. 3) Kernel Supervision is applied to supply supervision at the kernel level for robust learning. From a practical perspective, our pre-training method helps QEIS models achieve a similar convergence speed and comparable performance with CNN-based models in low-data regimes. Experimental results show that our method significantly boosts several QEIS models on three datasets.