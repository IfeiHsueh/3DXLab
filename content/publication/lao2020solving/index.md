---
title: 'Solving rolling shutter 3d vision problems using analogies with non-rigidity'
authors:
  - yz.lao
  - Omar Ait-Aider
  - Adrien Bartoli
author_notes:
  - 'Corresponding'
  - 
  - 
date: '2023-06-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: 'International Journal of Computer Vision) '
publication_short: 'IJCV'

abstract: We propose an original approach to absolute pose and structure-from-motion (SfM) which handles rolling shutter (RS) effects. Unlike most existing methods which either augment global shutter projection with velocity parameters or impose continuous time and motion through pose interpolation, we use local differential constraints. These are established by drawing analogies with non-rigid 3D vision techniques, namely shape-from-template and non-rigid SfM (NRSfM). The proposed idea is to interpret the images of a rigid surface acquired by a moving RS camera as those of a virtually deformed surface taken by a GS camera. These virtually deformed surfaces are first recovered by relaxing the RS constraint using SfT or NRSfM. Then we upgrade the virtually deformed surface to the actual rigid structure and compute the camera pose and ego-motion by reintroducing the RS constraint. This uses a new 3D-3D registration procedure that minimizes a cost function based on the Euclidean 3D point distance. This is more stable and physically meaningful than the reprojection error or the algebraic distance used in previous work. Experimental results obtained with synthetic and real data show that the proposed methods outperform existing ones in terms of accuracy and stability, even in the known critical configurations.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - SLAM
  - Rolling Shutter
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/DelinQu/rspy/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**3DXLab**](https://3dxlab.netlify.app/)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).
