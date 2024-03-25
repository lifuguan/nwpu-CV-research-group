---
title: Multiple Papers of Our Team Have Been Accepted by TIP
date: 2024-02-15T03:42:32.972Z
draft: false
featured: false

---
Two papers of our team have been accepted by *IEEE Transactions on Image Processing* recently.

<!--more-->

## Uncertainty Modeling for Gaze Estimation

Authors Wenqi Zhong, Chen Xia, Dingwen Zhang, Junwei Han

Gaze estimation is an important fundamental task in computer vision and medical research. Existing works have explored various effective paradigms and modules for precisely predicting eye gazes. However, the uncertainty for gaze estimation, e.g ., input uncertainty and annotation uncertainty, have been neglected in previous research. Existing models use a deterministic function to estimate the gaze, which cannot reflect the actual situation in gaze estimation. To address this issue, we propose a probabilistic framework for gaze estimation by modeling the input uncertainty and annotation uncertainty. We first utilize probabilistic embeddings to model the input uncertainty, representing the input image as a Gaussian distribution in the embedding space. Based on the input uncertainty modeling, we give an instance-wise uncertainty estimation to measure the confidence of prediction results, which is critical in practical applications. Then, we propose a new label distribution learning method, probabilistic annotations, to model the annotation uncertainty, representing the raw hard labels as Gaussian distributions. In addition, we develop an Embedding Distribution Smoothing (EDS) module and a hard example mining method to improve the consistency between embedding distribution and label distribution. We conduct extensive experiments, demonstrating that the proposed approach achieves significant improvements over baseline and state-of-the-art methods on two widely used benchmark datasets, GazeCapture and MPIIFaceGaze, as well as our collected dataset using mobile devices.



## Weakly Supervised Semantic Segmentation via Alternate Self-Dual Teaching

Authors: Dingwen Zhang, Hao Li, Wenyuan Zeng, Chaowei Fang, Lechao Cheng, Ming-Ming Cheng, Junwei Han

Weakly supervised semantic segmentation (WSSS) is a challenging yet important research field in vision community. In WSSS, the key problem is to generate high-quality pseudo segmentation masks (PSMs). Existing approaches mainly depend on the discriminative object part to generate PSMs, which would inevitably miss object parts or involve surrounding image background, as the learning process is unaware of the full object structure. In fact, both the discriminative object part and the full object structure are critical for deriving of high-quality PSMs. To fully explore these two information cues, we build a novel end-to-end learning framework, alternate self-dual teaching (ASDT), based on a dual-teacher single-student network architecture. The information interaction among different network branches is formulated in the form of knowledge distillation (KD). Unlike the conventional KD, the knowledge of the two teacher models would inevitably be noisy under weak supervision. Inspired by the Pulse Width (PW) modulation, we introduce a PW wave-like selection signal to alleviate the influence of the imperfect knowledge from either teacher model on the KD process. Comprehensive experiments on the PASCAL VOC 2012 and COCO-Stuff 10K demonstrate the effectiveness of the proposed ASDT framework, and new state-of-the-art results are achieved.