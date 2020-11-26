---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Domain-Aware Unsupervised Hyperspectral Reconstruction for Aerial Image Dehazing"
authors: [Aditya Mehta, admin, Murari Mandal, Pratik Narang]
date: 2020-11-02T16:21:27+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-02T16:21:27+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/CVF Winter Conference on Applications of Computer Vision 2021"
publication_short: "WACV 2021"

abstract: "Haze removal in aerial images is a challenging problem due to considerable variation in spatial details and varying contrast. Changes in particulate matter density often lead to degradation in visibility. Therefore, several approaches utilize multi-spectral data as auxiliary information for haze removal. In this paper, we propose SkyGAN for haze removal in aerial images. SkyGAN comprises of 1) a domain-aware hazy-to-hyperspectral (H2H) module, and 2) a conditional GAN (cGAN) based multi-cue image-to-image translation module (I2I) for dehazing. The proposed H2H module reconstructs several visual bands from RGB images in an unsupervised manner, which overcomes the lack of hazy hyperspectral aerial image datasets. The module utilizes task supervision and domain adaptation in order to create a 'hyperspectral catalyst' for image dehazing. The I2I module uses the hyperspectral catalyst along with a 12-channel multi-cue input and performs effective image dehazing by utilizing the entire visual spectrum. In addition, this work introduces a new dataset, called Hazy Aerial-Image (HAI) dataset, that contains more than 65,000 pairs of hazy and ground truth aerial images with realistic, non-homogeneous haze of varying density. The performance of SkyGAN is evaluated on the recent SateHaze1k dataset as well as the HAI dataset. We also present a comprehensive evaluation of HAI dataset with a representative set of state-of-the-art techniques in terms of PSNR and SSIM."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
- name: arXiv
  url: https://arxiv.org/abs/2011.03677
  icon_pack: fab
#  icon: twitter


url_pdf: 
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
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
slides: ""
---
