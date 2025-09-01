---
title: "Parameter inference in nonlinear dynamical systems via recurrence plots and convolutional neural networks"
authors:
- admin
- Francisco A. Rodrigues
- Matheus. S. Palmero
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-07-09T00:00:00Z"
doi: 10.1103/wz7j-lzvs

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Physical Review E*"
publication_short: ""

abstract: Inferring control parameters in nonlinear dynamical systems is an important task in analyzing general dynamical behaviors, particularly in the presence of inherently deterministic chaos. Traditional approaches often rely on system-specific models and involve heavily parametrized formulations, which can limit their general applicability. In this study, we present a methodology that employs recurrence plots as structured representations of nonlinear trajectories, which are then used to train convolutional neural networks to infer the values of the control parameter associated with the analyzed trajectories. We focus on two representative nonlinear systems, namely, the logistic map and the standard map, and show that our approach enables accurate estimation of the parameters governing their dynamics. When compared to regression models trained directly on raw time-series data, the use of recurrence plots yields significantly more robust results. Although the methodology does not aim to predict future states explicitly, we argue that accurate parameter inference, when combined with predetermined initial conditions, enables the reconstruction of a system's evolution due to its deterministic nature. These findings highlight the potential of recurrence-based learning frameworks for the automated identification and characterization of nonlinear dynamical behaviors.



tags:
- Articles
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2410.23408
url_code: 'https://github.com/luizalober/chaotic_systems_NN'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

image:
  caption: 'General architecture of the CNN implemented. Layers indicated in solid colors were used for both dynamics, with
the hatched blocks employed solely for the dynamics of the Standard map, and dropout used only for the Logistic map.'
  focal_point: ""
  preview_only: false
---
