 ---
title: "SSB: Simple but Strong Baseline for Boosting Performance of Open-Set Semi-Supervised Learning"
authors:
- Yue Fan
- "**Anna Kukleva**"
- Dengxin Dai
- Bernt Schiele
date: "2023-08-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF International Conference on Computer Vision 
publication_short: ICCV 2023

abstract: Semi-supervised learning (SSL) methods effectively leverage unlabeled data to improve model generalization. However, SSL models often underperform in open-set scenarios, where unlabeled data contain outliers from novel categories that do not appear in the labeled set. In this paper, we study the challenging and realistic open-set SSL setting, where the goal is to both correctly classify inliers and to detect outliers. Intuitively, the inlier classifier should be trained on inlier data only. However, we find that inlier classification performance can be largely improved by incorporating high-confidence pseudo-labeled data, regardless of whether they are inliers or outliers. Also, we propose to utilize non-linear transformations to separate the features used for inlier classification and outlier detection in the multi-task learning framework, preventing adverse effects between them. Additionally, we introduce pseudo-negative mining, which further boosts outlier detection performance. The three ingredients lead to what we call Simple but Strong Baseline (SSB) for open-set SSL. In experiments, SSB greatly improves both inlier classification and outlier detection performance, outperforming existing methods by a large margin.

# Summary. An optional shortened abstract.
summary: ICCV 2023 
# Unsupervised temporal segmentation of instruction videos
tags:
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'https://openaccess.thecvf.com/content/ICCV2023/papers/Fan_SSB_Simple_but_Strong_Baseline_for_Boosting_Performance_of_Open-Set_ICCV_2023_paper.pdf'
url_code: 'https://github.com/YUE-FAN/SSB'
# url_dataset: '#'
# url_poster: '#'
# url_project: 'https://annusha.github.io/LCwF/'
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
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


