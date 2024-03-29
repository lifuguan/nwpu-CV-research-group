---
title: Equivalent Classification Mapping for Weakly Supervised Temporal Action Localization
summary: Weakly supervised temporal action localization is a newly emerging yet widely studied topic in recent years. The existing methods can be categorized into two localization-by-classification pipelines, i.e., the pre-classification pipeline and the post-classification pipeline.
tags:
  - TPAMI
date: 2020-10-06
url_code: 'https://github.com/VividLe/Equivalent-Classification-Mapping'
url_pdf: 'https://arxiv.org/pdf/2008.07728.pdf'
url_slides: ''
url_video: ''

authors: ['杨乐']

date: '2020-10-06T00:00:00Z'
publication: In *IEEE TRANSACTIONS ON PATTERN ANALYSIS AND MACHINE INTELLIGENCE*

---

Weakly supervised temporal action localization is a newly emerging yet widely studied topic in recent years. The existing methods can be categorized into two localization-by-classification pipelines, i.e., the pre-classification pipeline and the post-classification pipeline. The pre-classification pipeline first performs classification on each video snippet and then aggregate the snippet-level classification scores to obtain the video-level classification score. In contrast, the post-classification pipeline aggregates the snippet-level features first and then predicts the video-level classification score based on the aggregated feature. Although the classifiers in these two pipelines are used in different ways, the role they play is exactly the same---to classify the given features to identify the corresponding action categories. To this end, an ideal classifier can make both pipelines work. This inspires us to simultaneously learn these two pipelines in a unified framework to obtain an effective classifier. Specifically, in the proposed learning framework, we implement two parallel network streams to model the two localization-by-classification pipelines simultaneously and make the two network streams share the same classifier. This achieves the novel Equivalent Classification Mapping (ECM) mechanism. Moreover, we discover that an ideal classifier may possess two characteristics: 1) The frame-level classification scores obtained from the pre-classification stream and the feature aggregation weights in the post-classification stream should be consistent; 2) The classification results of these two streams should be identical. Based on these two characteristics, we further introduce a weight-transition module and an equivalent training strategy into the proposed learning framework, which assists to thoroughly mine the equivalence mechanism.