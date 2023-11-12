---
title: 'Towards Nonlinear-Motion-Aware and Occlusion-Robust Rolling Shutter Correction'
authors:
  - yz.lao
  - Omar Ait-Aider
author_notes:
  - 'Corresponding'
  - 
date: '2018-06-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-6-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: '2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition'
publication_short: 'CVPR'

abstract: We present a robust method which compensates RS distortions in a single image using a set of image curves, basing on the knowledge that they correspond to 3D straight lines. Unlike in existing work, no a priori knowledge about the line directions (e.g. Manhattan World assumption) is required. We first formulate a parametric equation for the projection of a 3D straight line viewed by a moving rolling shutter camera under a uniform motion model. Then we propose a method which efficiently estimates ego angular velocity separately from pose parameters, using at least 4 image curves. Moreover, we propose for the first time a RANSAC-like strategy to select image curves which really correspond to 3D straight lines and reject those corresponding to actual curves in 3D world. A comparative experimental study with both synthetic and real data from famous benchmarks shows that the proposed method outperforms all the existing techniques from the state-of-the-art.

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
