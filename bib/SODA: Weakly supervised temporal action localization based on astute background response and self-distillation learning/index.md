---
title: 'Background-click supervision for temporal action localization'
authors:
  - Le Yang
  - Junwei Han
  - Dingwen Zhang
date: '2018-06-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-06-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence*
publication_short: In *T-PAMI*

abstract: Weakly supervised temporal action localization aims at learning the instance-level action pattern from the video-level labels, where a challenge is action-context confusion. To overcome this challenge, one recent work builds an action-click supervision framework. It requires similar annotation costs but can steadily improve the localization performance when compared to the conventional weakly supervised methods. In this paper, we find a stronger action localizer can be trained with the same annotation costs if the labels are annotated on the background video frames, because the performance bottleneck of the existing approaches mainly comes from the background errors. To this end, we convert the action-click supervision to the background-click supervision and develop a novel method, called BackTAL. BackTAL implements two-fold modeling on the background video frames, i.e. the position modeling and the feature modeling. In position modeling, we not only conduct supervised learning on the annotated video frames but also design a score separation module to enlarge the score differences between the potential action frames and backgrounds. In feature modeling, we propose an affinity module to measure frame-specific similarities among neighboring frames and dynamically attend to informative neighbors when calculating temporal convolution. Experiments on three benchmarks demonstrate the high performance of our BackTAL.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Background-click
  - supervision
  - Temporal action localization
  - Weakly-supervised
featured: true

url_pdf: https://ieeexplore.ieee.org/document/8579044


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
