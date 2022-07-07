---
title: 'Revisiting anchor mechanisms for temporal action localization'
authors:
  - Le Yang
  - Dingwen Zhang
  - Junwei Han
date: '2018-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing*
publication_short: In *T-IP*

abstract: Most of the current action localization methods follow an anchor-based pipeline depicting action instances by pre-defined anchors, learning to select the anchors closest to the ground truth, and predicting the confidence of anchors with refinements. Pre-defined anchors set prior about the location and duration for action instances, which facilitates the localization for common action instances but limits the flexibility for tackling action instances with drastic varieties, especially for extremely short or extremely long ones. To address this problem, this paper proposes a novel anchor-free action localization module that assists action localization by temporal points. Specifically, this module represents an action instance as a point with its distances to the starting boundary and ending boundary, alleviating the pre-defined anchor restrictions in terms of action localization and duration. The proposed anchor-free module is capable of predicting the action instances whose duration is either extremely short or extremely long. By combining the proposed anchor-free module with a conventional anchor-based module, we propose a novel action localization framework, called A2Net. The cooperation between anchor-free and anchor-based modules achieves superior performance to the state-of-the-art on THUMOS14 (45.5% vs. 42.8%). Furthermore, comprehensive experiments demonstrate the complementarity between the anchor-free and the anchor-based module, making A2Net simple but effective.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Temporal action localization
  - Default anchor
  - Anchor free
featured: true

url_pdf: https://ieeexplore.ieee.org/document/9171561


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
