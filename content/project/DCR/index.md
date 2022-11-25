---
title: Disentangled Capsule Routing for Fast Part-Object Relational Saliency
summary: Recently, the Part-Object Relational (POR) saliency underpinned by the Capsule Network (CapsNet) has been demonstrated to be an effective modeling mechanism to improve the saliency detection accuracy. However, it is widely known that the current capsule routing operations have huge computational complexity, which seriously limited the usability of the POR saliency models in real-time applications.
tags:
  - TIP
date: 2022-10-25
url_code: 'https://github.com/liuyi1989/DCR'
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9929280'
url_slides: ''
url_video: ''

authors: ['张鼎文']

date: '2022-10-25T00:00:00Z'
publication: In *IEEE Transactions on Image Processing*

---

Recently, the Part-Object Relational (POR) saliency underpinned by the Capsule Network (CapsNet) has been demonstrated to be an effective modeling mechanism to improve the saliency detection accuracy. However, it is widely known that the current capsule routing operations have huge computational complexity, which seriously limited the usability of the POR saliency models in real-time applications. To this end, this paper takes an early step towards a fast POR saliency inference by proposing a novel disentangled part-object relational network. Concretely, we disentangle horizontal routing and vertical routing from the original omnidirectional capsule routing, thus generating Disentangled Capsule Routing (DCR). This mechanism enjoys two advantages. On one hand, DCR that disentangles orthogonal 1D (i.e., vertical and horizontal) routing greatly reduces parameters and routing complexity, resulting in much faster inference than omnidirectional 2D routing adopted by existing CapsNets. On the other hand, thanks to the light POR cues explored by DCR, we could conveniently integrate the part-object routing process to different feature layers in CNN, rather than just applying it to the small-scaled one as in previous works. This helps to increase saliency inference accuracy. Compared to previous POR saliency detectors, DPORTNet infers visual saliency (5∼9)× faster, and is more accurate. DPORTNet is available under the open-source license at https://github.com/liuyi1989/DCR .