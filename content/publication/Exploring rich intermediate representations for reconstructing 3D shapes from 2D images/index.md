---
title: 'Exploring rich intermediate representations for reconstructing 3D shapes from 2D images'
authors:
  - Yang Yang
  - Junwei Han
  - Dingwen Zhang
date: '2022-02-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-02-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Pattern Recognition*
publication_short: In *PR*

abstract: Recovering 3D voxelized shapes with fine details from single-view 2D images is an extremely challenging and ill-conditioned problem. Most of the existing methods learn the 3D reconstruction process by encoding the 3D shapes and the 2D images into the same low-dimensional latent vector, which lacks the capacity to capture detailed features in the surface of the 3D object shapes. To address this issue, we propose to explore rich intermediate representation for 3D shape reconstruction by using a newly designed network architecture. We first use a two-steam network to infer the depth map and the topology-specific mean shape from the given 2D image, which forms the intermediate representation prediction branch. The intermediate representations capture the global spatial structure and the visible surface geometric structure, which are important for reconstructing high-quality 3D shapes. Based on the obtained intermediate representation, a novel shape transformation network is then proposed to reconstruct the fine details of the whole 3D object shapes. The experimental results on the challenging ShapeNet and Pix3D datasets show that our approach outperforms the existing state-of-the-art methods.



# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - 3D Reconstruction
  - Shape transformation
  - Intermediate representations
featured: true

url_pdf: https://doi.org/10.1016/j.patcog.2021.108295


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
