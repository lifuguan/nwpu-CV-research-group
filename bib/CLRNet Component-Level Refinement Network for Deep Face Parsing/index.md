---
title: 'CLRNet: Component-Level Refinement Network for Deep Face Parsing'
authors:
  - Peiliang Huang
  - Dingwen Zhang
  - Junwei Han
date: '2021-08-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-30T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Neural Networks and Learning Systems*
publication_short: In *TNNLS*

abstract: Face parsing aims to assign pixel-wise semantic labels to different facial components (e.g., hair, brows, and lips) in given face images. However, directly predicting pixel-level labels for each facial component over the whole face image would obtain limited accuracy, especially for tiny facial components. To address this problem, some recent works propose to first crop tiny patches from the whole face image and then predict masks for each facial component. However, such cropping-and-segmenting strategy consists of two independent stages, which cannot be jointly optimized. Besides, as one valuable piece of information for parsing the highly structured facial components, context cues are not elaborately explored by the existing works. To address these issues, we propose a component-level refinement network (CLRNet) for precisely segmenting out each facial component. Specifically, we introduce an attention mechanism to bridge the two independent stages together and form an end-to-end trainable pipeline for face parsing. Furthermore, we incorporate the global context information into the refining process for each cropped facial component patch, providing informative cues for accurate parsing. Extensive experiments are carried out on two benchmark datasets, LFW-PL and HELEN. The results demonstrate the superiority of the proposed CLRNet over other state-of-the-art methods, especially for tiny facial components.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Faces
  - Component-Level
  - Refinement Network
  - Deep Face Parsing
  - Image segmentation
  - Convolution
  - Shape
  - Agriculture
  - Customer relationship management
featured: true

url_pdf: https://ieeexplore.ieee.org/abstract/document/9525038


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
