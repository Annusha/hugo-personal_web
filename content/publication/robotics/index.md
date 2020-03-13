 ---
title: "Utilizing Temporal Information in Deep Convolutional Network for Efficient Soccer Ball Detection and Tracking"
authors:
- Anna Kukleva*
- Mohammad Asif Khan*
- Hafez Farazi
- Sven Behnke
date: "2019-12-01T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-030-35699-6_9"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: In RoboCup 2019, Springer
# publication_short: In *STC*

abstract: Soccer ball detection is identified as one of the critical challenges in the RoboCup competition. It requires an efficient vision system capable of handling the task of detection with high precision and recalland providing robust and low inference time. In this work, we present a novel convolutional neural network (CNN) approach to detect the soccerball  in  an  image  sequence.  In  contrast  to  the  existing  methods  where only the current frame or an image is used for the detection, we make use of the history of frames. Using history allows efficiently track the ball in situations where it disappears or gets partially occluded in some of the frames. Our approach exploits spatio-temporal correlation and detects the ball based on the trajectory of its movements. We present our results with three convolutional methods, namely temporal convolutional networks (TCN), ConvLSTM, and ConvGRU. We first solve the detection  task  for  an  image  using  fully  convolutional  encoder-decoder architecture,  and  later,  we  use  it  as  an  input  to  our  temporal  models and jointly learn the detection task in sequences of images. We evaluate all our experiments on a novel dataset prepared as a part of this work. Furthermore, we present empirical results to support the effectiveness of using the history of the ball in challenging scenarios.

# Summary. An optional shortened abstract.
summary: RoboCup 2019, Springer (Oral)
tags:
featured: true
# Exploiting traking history for improving the detection of the ball for the robotics competition

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://2019.robocup.org/downloads/program/KuklevaEtAl2019.pdf
url_code: 'https://github.com/AIS-Bonn/TemporalBallDetection'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
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


