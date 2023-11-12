---
title: 'Rolling shutter homography and its applications'
authors:
  - yz.lao
  - Omar Ait-Aider
author_notes:
  - 'Corresponding'
  - 
date: '2020-03-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-03-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: 'IEEE transactions on pattern analysis and machine intelligence'
publication_short: 'T-PAMI'

abstract: In this article we study the adaptation of the concept of homography to Rolling Shutter (RS) images. This extension has never been clearly adressed despite the many roles played by the homography matrix in multi-view geometry. We first show that a direct point-to-point relationship on a RS pair can be expressed as a set of 3 to 8 atomic 3x3 matrices depending on the kinematic model used for the instantaneous-motion during image acquisition. We call this group of matrices the RS Homography. We then propose linear solvers for the computation of these matrices using point correspondences. Finally, we derive linear and closed form solutions for two famous problems, namely image stitching and plane-based relative pose computation, in computer vision in the case of RS images. Extensive experiments with both synthetic and real data from public benchmarks show that the proposed methods outperform state-of-art techniques.

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
