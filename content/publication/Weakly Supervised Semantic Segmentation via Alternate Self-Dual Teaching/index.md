---
title: 'Weakly Supervised Semantic Segmentation via Alternate Self-Dual Teaching'
authors:
  - Dingwen Zhang
  - Hao Li
  - Wenyuan Zeng
  - Chaowei Fang
  - Lechao Cheng
  - Ming-Ming Cheng
  - Junwei Han
date: '2023-12-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing*
publication_short: In *TIP*

abstract: Weakly supervised semantic segmentation (WSSS) is a challenging yet important research field in vision community. In WSSS, the key problem is to generate high-quality pseudo segmentation masks (PSMs). Existing approaches mainly depend on the discriminative object part to generate PSMs, which would inevitably miss object parts or involve surrounding image background, as the learning process is unaware of the full object structure. In fact, both the discriminative object part and the full object structure are critical for deriving of high-quality PSMs. To fully explore these two information cues, we build a novel end-to-end learning framework, alternate self-dual teaching (ASDT), based on a dual-teacher single-student network architecture. The information interaction among different network branches is formulated in the form of knowledge distillation (KD). Unlike the conventional KD, the knowledge of the two teacher models would inevitably be noisy under weak supervision. Inspired by the Pulse Width (PW) modulation, we introduce a PW wave-like selection signal to alleviate the influence of the imperfect knowledge from either teacher model on the KD process. Comprehensive experiments on the PASCAL VOC 2012 and COCO-Stuff 10K demonstrate the effectiveness of the proposed ASDT framework, and new state-of-the-art results are achieved.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Semi-Supervised Segmentation
  - Semantic Segmentation
featured: true

url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10367821


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