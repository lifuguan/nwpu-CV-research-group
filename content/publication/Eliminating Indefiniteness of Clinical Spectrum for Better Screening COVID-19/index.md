---
title: 'Eliminating Indefiniteness of Clinical Spectrum for Better Screening COVID-19'
authors:
  - Guoyu Guang
  - Dingwen Zhang
  - Junwei Han
date: '2021-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-07-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Journal of Biomedical and Health Informatics*
publication_short: In *JBHI*

abstract: The coronavirus disease 2019 (COVID-19) has swept all over the world. Due to the limited detection facilities, especially in developing countries, a large number of suspected cases can only receive common clinical diagnosis rather than more effective detections like Reverse Transcription Polymerase Chain Reaction (RT-PCR) tests or CT scans. This motivates us to develop a quick screening method via common clinical diagnosis results. However, the diagnostic items of different patients may vary greatly, and there is a huge variation in the dimension of the diagnosis data among different suspected patients, it is hard to process these indefinite dimension data via classical classification algorithms. To resolve this problem, we propose an Indefiniteness Elimination Network (IE-Net) to eliminate the influence of the varied dimensions and make predictions about the COVID-19 cases. The IE-Net is in an encoder-decoder framework fashion, and an indefiniteness elimination operation is proposed to transfer the indefinite dimension feature into a fixed dimension feature. Comprehensive experiments were conducted on the public available COVID-19 Clinical Spectrum dataset. Experimental results show that the proposed indefiniteness elimination operation greatly improves the classification performance, the IE-Net achieves 94.80% accuracy, 92.79% recall, 92.97% precision and 94.93% AUC for distinguishing COVID-19 cases from non-COVID-19 cases with only common clinical diagnose data. We further compared our methods with 3 classical classification algorithms random forest, gradient boosting and multi-layer perceptron (MLP). To explore each clinical test item's specificity, we further analyzed the possible relationship between each clinical test item and COVID-19.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Medical Imaging
  - Clinical Spectrum
  - Eliminating
  - Indefiniteness
  - COVID-19
  - clinical spectrum
  - indefiniteness elimination
  - neural network
  - quick screening
featured: true

url_pdf: https://ieeexplore.ieee.org/document/9357911


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
