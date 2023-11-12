---
title: 'Rolling Shutter Pose and Ego-Motion Estimation Using Shape-from-Template'
authors:
  - yz.lao
  - Omar Ait-Aider
  - Adrien Bartoli
author_notes:
  - 'Corresponding'
  - 
date: '2018-10-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-10-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'Proceedings of the European Conference on Computer Vision'
publication_short: 'ECCV'

abstract: We propose a new method for the absolute camera pose problem (PnP) which handles Rolling Shutter (RS) effects. Unlike all existing methods which perform 3D-2D registration after augmenting the Global Shutter (GS) projection model with the velocity parameters under various kinematic models, we propose to use local differential constraints. These are established by drawing an analogy with Shape-from-Template (SfT). The main idea consists in considering that RS distortions due to camera ego-motion during image acquisition can be interpreted as virtual deformations of a template captured by a GS camera. Once the virtual deformations have been recovered using SfT, the camera pose and ego-motion are computed by registering the deformed scene on the original template. This 3D-3D registration involves a 3D cost function based on the Euclidean point distance, more physically meaningful than the re-projection error or the algebraic distance based cost functions used in previous work. Results on both synthetic and real data show that the proposed method outperforms existing RS pose estimation techniques in terms of accuracy and stability of performance in various configurations.

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
