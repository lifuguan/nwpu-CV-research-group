---
title: 'Learning Self-supervised Low-Rank Network for Single-Stage Weakly and Semi-supervised Semantic Segmentation'
authors:
  - Junwen Pan
  - Dingwen Zhang
  - Junwei Han
date: '2022-03-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Computer Vision*
publication_short: In *IJCV*

abstract: Semantic segmentation with limited annotations, such as weakly supervised semantic segmentation (WSSS) and semi-supervised semantic segmentation (SSSS), is a challenging task that has attracted much attention recently. Most leading WSSS methods employ a sophisticated multi-stage training strategy to estimate pseudo-labels as precise as possible, but they suffer from high model complexity. In contrast, there exists another research line that trains a single network with image-level labels in one training cycle. However, such a single-stage strategy often performs poorly because of the compounding effect caused by inaccurate pseudo-label estimation. To address this issue, this paper presents a Self-supervised Low-Rank Network (SLRNet) for single-stage WSSS and SSSS. The SLRNet uses cross-view self-supervision, that is, it simultaneously predicts several complementary attentive LR representations from different views of an image to learn precise pseudo-labels. Specifically, we reformulate the LR representation learning as a collective matrix factorization problem and optimize it jointly with the network learning in an end-to-end manner. The resulting LR representation deprecates noisy information while capturing stable semantics across different views, making it robust to the input variations, thereby reducing overfitting to self-supervision errors. The SLRNet can provide a unified single-stage framework for various label-efficient semantic segmentation settings (1) WSSS with image-level labeled data, (2) SSSS with a few pixel-level labeled data, and (3) SSSS with a few pixel-level labeled data and many image-level labeled data. Extensive experiments on the Pascal VOC 2012, COCO, and L2ID datasets demonstrate that our SLRNet outperforms both state-of-the-art WSSS and SSSS methods with a variety of different settings, proving its good generalizability and efficacy.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Weakly-supervised learning
  - Semi-supervised Learning
  - Semantic segmentation
featured: true

url_pdf: https://doi.org/10.1007/s11263-022-01590-z


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
