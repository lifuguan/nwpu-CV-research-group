---
title: 'Uncertainty Modeling for Gaze Estimation'
authors:
  - Wenqi Zhong
  - Chen Xia
  - Dingwen Zhang
  - Junwei Han

date: '2024-02-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing*
publication_short: In *TIP*

abstract: Gaze estimation is an important fundamental task in computer vision and medical research. Existing works have explored various effective paradigms and modules for precisely predicting eye gazes. However, the uncertainty for gaze estimation, e.g ., input uncertainty and annotation uncertainty, have been neglected in previous research. Existing models use a deterministic function to estimate the gaze, which cannot reflect the actual situation in gaze estimation. To address this issue, we propose a probabilistic framework for gaze estimation by modeling the input uncertainty and annotation uncertainty. We first utilize probabilistic embeddings to model the input uncertainty, representing the input image as a Gaussian distribution in the embedding space. Based on the input uncertainty modeling, we give an instance-wise uncertainty estimation to measure the confidence of prediction results, which is critical in practical applications. Then, we propose a new label distribution learning method, probabilistic annotations, to model the annotation uncertainty, representing the raw hard labels as Gaussian distributions. In addition, we develop an Embedding Distribution Smoothing (EDS) module and a hard example mining method to improve the consistency between embedding distribution and label distribution. We conduct extensive experiments, demonstrating that the proposed approach achieves significant improvements over baseline and state-of-the-art methods on two widely used benchmark datasets, GazeCapture and MPIIFaceGaze, as well as our collected dataset using mobile devices.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Estimation
  - Uncertainty
  - Probabilistic logic
  - Annotations
  - Gaussian distribution
  - Task analysis
  - Lighting
featured: true

url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10438351


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