---
title: Onfocus Detection:Identifying Individual-Camera Eye Contact from Unconstrained Images
summary: This repository is the official implementation of Onfocus Detection:Identifying Individual-Camera Eye Contact from Unconstrained Images.
tags:
  - SICS
date: 2022-04-20
url_code: 'https://github.com/wintercho/focus'
url_pdf: 'https://link.springer.com/article/10.1007/s11432-020-3181-9'
url_slides: ''
url_video: ''

authors: ['张鼎文']

date: '2022-04-20T00:00:00Z'
publication: In *Science China Information Sciences*

---

Onfocus detection aims at identifying whether the focus of the individual captured by a camera is on the camera or not. Based on the behavioral research, the focus of an individual during face-to-camera communication leads to a special type of eye contact, i.e., the individual-camera eye contact, which is a powerful signal in social communication and plays a crucial role in recognizing irregular individual status (e.g., lying or suffering mental disease) and special purposes (e.g., seeking help or attracting fans). Thus, developing effective onfocus detection algorithms is of significance for assisting the criminal investigation, disease discovery, and social behavior analysis. However, the review of the literature shows that very few efforts have been made toward the development of onfocus detector owing to the lack of large-scale public available datasets as well as the challenging nature of this task. To this end, this paper engages in the onfocus detection research by addressing the above two issues. Firstly, we build a large-scale onfocus detection dataset, named as the onfocus detection in the wild (OFDIW). It consists of 20623 images in unconstrained capture conditions (thus called “in the wild”) and contains individuals with diverse emotions, ages, facial characteristics, and rich interactions with surrounding objects and background scenes. On top of that, we propose a novel end-to-end deep model, i.e., the eye-context interaction inferring network (ECIIN), for onfocus detection, which explores eye-context interaction via dynamic capsule routing. Finally, comprehensive experiments are conducted on the proposed OFDIW dataset to benchmark the existing learning models and demonstrate the effectiveness of the proposed ECIIN.