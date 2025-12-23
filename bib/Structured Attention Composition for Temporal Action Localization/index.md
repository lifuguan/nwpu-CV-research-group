---
title: 'Structured Attention Composition for Temporal Action Localization'
authors:
  - Le Yang
  - Dingwen Zhang
  - Junwei Han
date: '2022-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing*
publication_short: In *T-IP*

abstract: Temporal action localization aims at localizing action instances from untrimmed videos. Existing works have designed various effective modules to precisely localize action instances based on appearance and motion features. However, by treating these two kinds of features with equal importance, previous works cannot take full advantage of each modality feature, making the learned model still sub-optimal. To tackle this issue, we make an early effort to study temporal action localization from the perspective of multi-modality feature learning, based on the observation that different actions exhibit specific preferences to appearance or motion modality. Specifically, we build a novel structured attention composition module. Unlike conventional attention, the proposed module would not infer frame attention and modality attention independently. Instead, by casting the relationship between the modality attention and the frame attention as an attention assignment process, the structured attention composition module learns to encode the frame-modality structure and uses it to regularize the inferred frame attention and modality attention, respectively, upon the optimal transport theory. The final frame-modality attention is obtained by the composition of the two individual attentions. The proposed structured attention composition module can be deployed as a plug-and-play module into existing action localization frameworks. Extensive experiments on two widely used benchmarks show that the proposed structured attention composition consistently improves four state-of-the-art temporal action localization methods and builds new state-of-the-art performance on THUMOS14. Code is availabel at this https URL.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Temporal action localization
  - Deep Learning
  - Attention
  - Structured Attention
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
