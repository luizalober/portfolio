---
title: "(Pre-print) Predictive Non-linear Dynamics via Neural Networks and Recurrence Plots"
authors:
- admin
- Francisco A. Rodrigues
- Matheus. S. Palmero
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-11-01T00:00:00Z"
doi: https://doi.org/10.1103/wz7j-lzvs

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Physical Review E*"
publication_short: ""

abstract: Predicting and characterizing diverse non-linear behaviors in dynamical systems is a complex challenge, especially due to the inherently presence of chaotic dynamics. Current forecasting methods are reliant on system-specific knowledge or heavily parameterized models, which can be associated with a variety of drawbacks including critical model assumptions, uncertainties in their estimated input hyperparameters, and also being computationally intensive. Moreover, even when combined with recurrence analyses, these approaches are typically constrained to chaos identification, rather than parameter inference. In this work, we address these challenges by proposing a methodology that uses recurrence plots to train convolutional neural networks with the task of estimating the defining control parameters of two distinct non-linear systems, those being (i) the Logistic map and (ii) the Standard map. By focusing on the neural networks' ability to recognize patterns within recurrence plots, we demonstrate accurate parameter recovery, achieving fairly confident levels of prediction for both systems. This method not only provides a robust approach to predicting diverse non-linear dynamics but also opens up new possibilities for the automated characterization of similar non-linear dynamical systems.
 
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

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
