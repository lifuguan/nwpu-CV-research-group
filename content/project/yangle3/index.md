---
title: Revisiting anchor mechanisms for temporal action localization
summary: Most of the current action localization methods follow an anchor-based pipeline:depicting action instances by pre-defined anchors, learning to select the anchors closest to the ground truth, and predicting the confidence of anchors with refinements.
tags:
  - TIP
date: 2020-08-19
url_code: ''
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9171561'
url_slides: ''
url_video: ''

authors: ['杨乐']

date: '2020-08-19T00:00:00Z'
publication: In *IEEE Transactions on Image Processing*

---

Most of the current action localization methods follow an anchor-based pipeline: depicting action instances by pre-defined anchors, learning to select the anchors closest to the ground truth, and predicting the confidence of anchors with refinements. Pre-defined anchors set prior about the location and duration for action instances, which facilitates the localization for common action instances but limits the flexibility for tackling action instances with drastic varieties, especially for extremely short or extremely long ones. To address this problem, this paper proposes a novel anchor-free action localization module that assists action localization by temporal points. Specifically, this module represents an action instance as a point with its distances to the starting boundary and ending boundary, alleviating the pre-defined anchor restrictions in terms of action localization and duration. The proposed anchor-free module is capable of predicting the action instances whose duration is either extremely short or extremely long. By combining the proposed anchor-free module with a conventional anchor-based module, we propose a novel action localization framework, called A2Net. The cooperation between anchor-free and anchor-based modules achieves superior performance to the state-of-the-art on THUMOS14 (45.5% vs. 42.8%). Furthermore, comprehensive experiments demonstrate the complementarity between the anchor-free and the anchor-based module, making A2Net simple but effective.