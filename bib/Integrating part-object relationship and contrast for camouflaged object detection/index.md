---
title: 'Integrating part-object relationship and contrast for camouflaged object detection'
authors:
  - Yi Liu
  - Dingwen Zhang
date: '2022-11-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Information Forensics and Security*
publication_short: In *TIFS*

abstract: Object detectors that solely rely on image contrast are struggling to detect camouflaged objects in images because of the high similarity between camouflaged objects and their surroundings. To address this issue, in this paper, we investigate the role of the part-object relationship for camouflaged object detection. Specifically, we propose a Part-Object relationship and Contrast Integrated Network (POCINet) covering both search and identification stages, where each stage adopts an appropriate scheme to engage the contrast information and part-object relational knowledge for camouflaged pattern decoding. Besides, we bridge these two stages via a Search-to-Identification Guidance (SIG) module, in which the search result, as well as decoded semantic knowledge, jointly enhances the features encoding ability of the identification stage. Experimental results demonstrate the superiority of our algorithm on three datasets. Notably, our algorithm raises Fβ of the best existing method by approximately 17 points on the CPD1K dataset. The source code will be released soon.



# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Camouflaged object detection
  - contrast
  - part-object relationships
  - encoder-decoder
  - multi-stage
featured: true

url_pdf: https://ieeexplore.ieee.org/abstract/document/9600863


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
