---
title: 'Segmentation in weakly labeled videos via a semantic ranking and optical warping network.'
authors:
  - Dingwen Zhang
  - Le Yang
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

abstract: Weakly supervised video object segmentation (WSVOS) focuses on generating pixel-level object masks for videos only tagged with class labels, which is an essential yet challenging task. For WSVOS, the algorithm is just aware of rough category information rather than the concrete object size and location cues, besides it lacks reliable annotated exemplars to learn temporal evolution in the investigated videos. Basically, there are three challenging factors which may influence the performance of WSVOS foreground object discovery in each frame, coarse object semantic consistency within each video, and fine-grained segmentation smoothness within neighbor frames. In this paper, we establish a semantic ranking and optical warping network to simultaneously solve these three challenges in a unified framework. For the first challenge, we apply the still image saliency detection method and discover the foreground object for each frame via a segmentation network. Due to the huge discrepancies between the image saliency and the video object segmentation, we step further and propose two subnetworks to solve the other two challenges. For the second one, we propose an attentive semantic ranking subnetwork to mine video-level tags, which can learn discriminative features for semantic ranking and lead to semantic consistent segmentation masks. For the third one, we propose an optical flow warping subnetwork to constrain fine-grained segmentation smoothness within neighbor frames, which can suppress the large deformation and thus obtain smooth object boundaries for adjacent frames. Experiments on two benchmark data sets, i.e., DAVIS data set and YouTube-Objects data set, demonstrate the effectiveness of the proposed approach for segmenting out video objects under weak supervision.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Computer Vision
  - Video
  - semantic ranking
  - neural network
  - Segmentation
  - Object Segmentation
  - Optical warping
  - Weakly-supervised
  - Instance Segmentation
featured: true

url_pdf: https://ieeexplore.ieee.org/document/8360132


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
