---
title: 'Continual All-in-One Adverse Weather Removal With Knowledge Replay on a Unified Network Structure'
authors:
  - De Cheng
  - Yanling Ji
  - Dong Gong
  - Yan Li
  - NanNan Wang
  - Junwei Han
  - Dingwen Zhang
date: '2024-03-19T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-19T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Multimedia*
publication_short: In *TMM*

abstract: In real-world applications, image degeneration caused by adverse weather is always complex and changes with different weather conditions from days and seasons. Systems in real-world environments constantly encounter adverse weather conditions that are not previously observed. Therefore, it practically requires adverse weather removal models to continually learn from incrementally collected data reflecting various degeneration types. Existing adverse weather removal approaches, for either single or multiple adverse weathers, are mainly designed for a static learning paradigm, which assumes that the data of all types of degenerations to handle can be finely collected at one time before a single-phase learning process. They thus cannot directly handle the incremental learning requirements. To address this issue, we made the earliest effort to investigate the continual all-in-one adverse weather removal task, in a setting closer to real-world applications. Specifically, we develop a novel continual learning framework with effective knowledge replay (KR) on a unified network structure. Equipped with a principal component projection and an effective knowledge distillation mechanism, the proposed KR techniques are tailored for the all-in-one weather removal task. It considers the characteristics of the image restoration task with multiple degenerations in continual learning, and the knowledge for different degenerations can be shared and accumulated in the unified network structure. Extensive experimental results demonstrate the effectiveness of the proposed method to deal with this challenging task, which performs competitively to existing dedicated or joint training image restoration methods. Our code is available at https://github.com/xiaojihh/CL_all-in-one .


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Continual Learning
  - Adverse Weather Removal
  - Image Restoration
featured: true

url_pdf: https://ieeexplore.ieee.org/document/10473168


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