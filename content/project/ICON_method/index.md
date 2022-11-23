---
title: Salient Object Detection via Integrity Learning
summary: To facilitate integrity learning for SOD, we design a novel Integrity Cognition Network (ICON), which explores three important components to learn strong integrity features.
tags:
  - TPAMI
date: 2022-06-06
url_code: 'https://github.com/mczhuge/ICON'
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9789317'
url_slides: ''
url_video: ''

authors: ['张鼎文']

date: '2022-06-06T00:00:00Z'
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence*

---

To facilitate integrity learning for SOD, we design a novel Integrity Cognition Network (ICON), which explores three important components to learn strong integrity features. 1) Unlike the existing models that focus more on feature discriminability, we introduce a diverse feature aggregation (DFA) component to aggregate features with various receptive fields (i.e., kernel shape and context) and increase the feature diversity. Such diversity is the foundation for mining the integral salient objects. 2) Based on the DFA features, we introduce the integrity channel enhancement (ICE) component with the goal of enhancing feature channels that highlight the integral salient objects (i.e., micro and macro levels) while suppressing the other distracting ones. 3) After extracting the enhanced features, the part-whole verification (PWV) method is employed to determine whether the part and whole object features have strong agreement. Such part-whole agreements can further improve the micro-level integrity for each salient object.