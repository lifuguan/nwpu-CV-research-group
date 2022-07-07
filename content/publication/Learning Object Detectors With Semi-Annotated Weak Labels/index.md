---
title: 'Learning Object Detectors with Semi-Annotated Weak Labels'
authors:
  - Guoyu Guang
  - Dingwen Zhang
  - Junwei Han
date: '2019-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-07-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Circuits and Systems for Video Technology*
publication_short: In *TCSVT*

abstract: For alleviating the human labor associated with annotating the training data for learning object detectors, recent research has focused on semi-supervised object detection (SSOD) and weakly supervised object detection (WSOD) approaches. In SSOD, instead of annotating all the instances in the whole training set, people only need to annotate the part of the training instances using bounding boxes. In WSOD, people need to annotate the image-level tags on all training images to indicate the object categories contained by the corresponding images since more detailed bounding box annotations are no longer needed. Along this line of research, this paper makes a further step to alleviate the human labor in annotating training data, leading to the problem of object detection with semi-annotated weak labels (ODSAWLs). Instead of labeling image-level tags on all training images, ODSAWL only needs the image-level tags for a small portion of the training images, and then, the object detectors can be learned from a small portion of the weakly-labeled training images and from the remaining unlabeled training images. To address such a challenging problem, this paper proposes a cross model co-training framework that collaborates an object localizer and a tag generator in an alternative optimization procedure. Specifically, during the learning procedure, these two (deep) models can transfer the needed knowledge (including labels and visual patterns) between each other. The whole learning procedure is accomplished in a few stages under the guidance of a progressive learning curriculum. To demonstrate the effectiveness of the proposed approach, we implement the comprehensive experiments on three benchmark datasets, where the obtained experimental results are quite encouraging. Notably, by using only about 15% weakly labeled training images, the proposed approach can effectively approach, or even outperform, the state-of-the-art WSOD methods.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Computer vision
  - image processing
  - object detection
  - Semi-Annotated
  - Weak Labels
  - Semi-supervised Learning
featured: true

url_pdf: https://ieeexplore.ieee.org/document/8554285


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
