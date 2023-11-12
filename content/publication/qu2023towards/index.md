---
title: 'Towards Nonlinear-Motion-Aware and Occlusion-Robust Rolling Shutter Correction'
authors:
  - dl.qu
  - yz.lao
  - Zhigang Wang
  - Dong Wang
  - Bin Zhao
  - Xuelong Li
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  -
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
publication: 'IEEE Transactions on Pattern Analysis and Machine Intelligence ( Volume: 45, Issue: 10, October 2023) '
publication_short: 'T-PAMI'

abstract: This paper addresses the problem of rolling shutter correction in complex nonlinear and dynamic scenes with extreme occlusion. Existing methods suffer from two main drawbacks. Firstly, they face challenges in estimating the accurate correction field due to the uniform velocity assumption, leading to significant image correction errors under complex motion. Secondly, the drastic occlusion in dynamic scenes prevents current solutions from achieving better image quality because of the inherent difficulties in aligning and aggregating multiple frames. To tackle these challenges, we model the curvilinear trajectory of pixels analytically and propose a geometry-based Quadratic Rolling Shutter (QRS) motion solver, which precisely estimates the high-order correction field of individual pixels. Besides, to reconstruct high-quality occlusion frames in dynamic scenes, we present a 3D video architecture that effectively Aligns and Aggregates multi-frame context, namely, RSA2-Net. We evaluate our method across a broad range of cameras and video sequences, demonstrating its significant superiority. Specifically, our method surpasses the state-of-the-art by +4.98, +0.77, and +4.33 of PSNR on Carla-RS, Fastec-RS, and BS-RSC datasets, respectively. Code is available at [https://github.com/DelinQu/qrsc](https://github.com/DelinQu/qrsc/).

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
