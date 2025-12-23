---
title: 'Scribble-Supervised Video Object Segmentation'
authors:
  - Peiliang Huang
  - Dingwen Zhang
  - Junwei Han
date: '2021-07-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-07-28T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CAA Journal of Automatica Sinica*
publication_short: In *JAS*

abstract: Recently, video object segmentation has received great attention in the computer vision community. Most of the existing methods heavily rely on the pixel-wise human annotations, which are expensive and time-consuming to obtain. To tackle this problem, we make an early attempt to achieve video object segmentation with scribble-level supervision, which can alleviate large amounts of human labor for collecting the manual annotation. However, using conventional network architectures and learning objective functions under this scenario cannot work well as the supervision information is highly sparse and incomplete. To address this issue, this paper introduces two novel elements to learn the video object segmentation model. The first one is the scribble attention module, which captures more accurate context information and learns an effective attention map to enhance the contrast between foreground and background. The other one is the scribble-supervised loss, which can optimize the unlabeled pixels and dynamically correct inaccurate segmented areas during the training stage. To evaluate the proposed method, we implement experiments on two video object segmentation benchmark datasets, YouTube-video object segmentation (VOS), and densely annotated video segmentation (DAVIS)-2017. We first generate the scribble annotations from the original per-pixel annotations. Then, we train our model and compare its test performance with the baseline models and other existing works. Extensive experiments demonstrate that the proposed method can work effectively and approach to the methods requiring the dense per-pixel annotations.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Computer Vision
  - Few-shot
  - Object
  - Segmentation
  - Scribble
  - Video
  - Scribble-Supervised
  - Instance Segmentation
featured: true


url_pdf: https://ieeexplore.ieee.org/document/9500146


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
