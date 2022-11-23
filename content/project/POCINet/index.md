---
title: Integrating Part-Object Relationship and Contrast for Camouflaged Object Detection
summary: Object detectors that solely rely on image contrast are struggling to detect camouflaged objects in images because of the high similarity between camouflaged objects and their surroundings. To address this issue, in this paper, we investigate the role of the part-object relationship for camouflaged object detection.
tags:
  - Others
date: 2021-12-04
url_code: 'https://github.com/liuyi1989/POCINet'
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9334445'
url_slides: ''
url_video: ''

authors: ['张鼎文']

date: '2020-12-04T00:00:00Z'
publication: In *IEEE Transactions on Information Forensics and Security*

---

Object detectors that solely rely on image contrast are struggling to detect camouflaged objects in images because of the high similarity between camouflaged objects and their surroundings. To address this issue, in this paper, we investigate the role of the part-object relationship for camouflaged object detection. Specifically, we propose a Part-Object relationship and Contrast Integrated Network (POCINet) covering both search and identification stages, where each stage adopts an appropriate scheme to engage the contrast information and part-object relational knowledge for camouflaged pattern decoding. Besides, we bridge these two stages via a Search-to-Identification Guidance (SIG) module, in which the search result, as well as decoded semantic knowledge, jointly enhances the features encoding ability of the identification stage. Experimental results demonstrate the superiority of our algorithm on three datasets. Notably, our algorithm raises Fβ of the best existing method by approximately 17 points on the CPD1K dataset. The source code will be released soon.