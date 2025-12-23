---
title: 'Htd: Heterogeneous task decoupling for two-stage object detection'
authors:
  - Wuyang Li
  - Zhen Chen
  - Baopu Li
  - Dingwen Zhang
date: '2021-11-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing*
publication_short: In *TIP*

abstract: Decoupling the sibling head has recently shown great potential in relieving the inherent task-misalignment problem in two-stage object detectors. However, existing works design similar structures for the classification and regression, ignoring task-specific characteristics and feature demands. Besides, the shared knowledge that may benefit the two branches is neglected, leading to potential excessive decoupling and semantic inconsistency. To address these two issues, we propose Heterogeneous task decoupling (HTD) framework for object detection, which utilizes a Progressive Graph (PGraph) module and a Border-aware Adaptation (BA) module for task-decoupling. Specifically, we first devise a Semantic Feature Aggregation (SFA) module to aggregate global semantics with image-level supervision, serving as the shared knowledge for the task-decoupled framework. Then, the PGraph module performs progressive graph reasoning, including local spatial aggregation and global semantic interaction, to enhance semantic representations of region proposals for classification. The proposed BA module integrates multi-level features adaptively, focusing on the low-level border activation to obtain representations with spatial and border perception for regression. Finally, we utilize the aggregated knowledge from SFA to keep the instance-level semantic consistency (ISC) of decoupled frameworks. Extensive experiments demonstrate that HTD outperforms existing detection works by a large margin, and achieves single-model 50.4%AP and 33.2% AP s on COCO test-dev set using ResNet-101-DCN backbone, which is the best entry among state-of-the-arts under the same configuration. Our code is available at https://github.com/CityU-AIM-Group/HTD .


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Object detectio
  - task-decoupled framework
featured: true

url_pdf: https://ieeexplore.ieee.org/abstract/document/9615001


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
