---
title: 'Equivalent classification mapping for weakly supervised temporal action localization'
authors:
  - Le Yang
  - Dingwen Zhang
  - Junwei Han
date: '2021-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence*
publication_short: In *T-PAMI*

abstract: Weakly supervised temporal action localization is a newly emerging yet widely studied topic in recent years. The existing methods can be categorized into the pre-classification pipeline and the post-classification pipeline. The pre-classification pipeline first performs classification on each video snippet and then aggregates the snippet-level classification scores to obtain the video-level classification score. In contrast, the post-classification pipeline aggregates the snippet-level features first and then predicts the video-level classificationscore based on the aggregated feature. Although the classifiers in these two pipelines are used in different ways, the role they play is exactly the same. To this end, an ideal classifier can make both pipelines work. This inspires us to simultaneously learn these two pipelines in a unified framework to obtain an effective classifier. Specifically, we implement two parallel network streams to model the two localization-by-classification pipelines simultaneously and make the two network streams share the same classifier. This achieves the novel Equivalent Classification Mapping (ECM) mechanism. Moreover, we discover that an ideal classifier may possess two characteristics 1) The frame-level classification scores obtained from the pre-classification stream and the feature aggregation weights in the post-classification stream should be consistent; 2) The classification results of these two streams should be identical. Based on these two characteristics, we further introduce a weight-transition module and an equivalent training strategy into the proposed learning framework, which assists to thoroughly mine the equivalence mechanism. Comprehensive experiments are conducted on three benchmarks and ECM achieves accurate action localization results.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Equivalent classification
  - weakly supervised
  - Equivalent mechanism
  - temporal action localization
  - post-classification pipeline
  - pre-classification pipeline
featured: true

url_pdf: https://openaccess.thecvf.com/content_cvpr_2018/papers/Han_Reinforcement_Cutting-Agent_Learning_CVPR_2018_paper.pdf


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
