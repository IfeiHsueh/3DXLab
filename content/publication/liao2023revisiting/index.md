---
title: 'Revisiting Rolling Shutter Bundle Adjustment: Toward Accurate and Fast Solution'
authors:
  - by.liao
  - dl.qu
  - yf.xue
  - hq.zhang
  - yz.lao
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  -
  -
  - 'Corresponding'
date: '2023-06-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition'
publication_short: 'CVPR'

abstract: We propose a robust and fast bundle adjustment solution that estimates the 6-DoF pose of the camera and the geometry of the environment based on measurements from a rolling shutter (RS) camera. This tackles the challenges in the existing works, namely relying on additional sensors, high frame rate video as input, restrictive assumptions on camera motion, readout direction, and poor efficiency. To this end, we first investigate the influence of normalization to the image point on RSBA performance and show its better approximation in modelling the real 6-DoF camera motion. Then we present a novel analytical model for the visual residual covariance, which can be used to standardize the reprojection error during the optimization, consequently improving the overall accuracy. More importantly, the combination of normalization and covariance standardization weighting in RSBA (NW-RSBA) can avoid common planar degeneracy without needing to constrain the filming manner. Besides, we propose an acceleration strategy for NW-RSBA based on the sparsity of its Jacobian matrix and Schur complement. The extensive synthetic and real data experiments verify the effectiveness and efficiency of the proposed solution over the state-of-the-art works. We also demonstrate the proposed method can be easily implemented and plug-in famous GSSfM and GSSLAM systems as completed RSSfM and RSSLAM solutions.

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
