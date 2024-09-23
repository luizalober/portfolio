---
title: "Forecasting infectious diseases in Brazilian cities: Integrating socio-economic
and geographic data from related cities through a machine learning approach"
authors:
- admin
- Francisco A. Rodrigues
- Kirstin O. Roster
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-09-23T00:00:00Z"
doi: 10.1016/j.chaos.2024.115417

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Chaos, Solitons and Fractals*"
publication_short: ""

abstract: Supervised machine learning models and public surveillance data has been employed for infectious disease forecasting in many settings. These models leverage various data sources capturing drivers of disease spread, such as climate conditions or human behavior. However, few models have incorporated the organizational structure of different geographic locations for forecasting. Traveling waves of seasonal outbreaks have been reported for dengue, influenza, and other infectious diseases, and many of the drivers of infectious disease dynamics may be shared across different cities, either due to their geographic or socioeconomic proximity. In this study, we developed a machine learning model to predict case counts of four infectious diseases across Brazilian cities one week ahead by incorporating information from related cities. We compared selecting related cities using both geographic distance and GDP per capita. Incorporating information from geographically proximate cities improved predictive performance for two of the four diseases, specifically COVID-19 and Zika. We also discuss the impact on forecasts in the presence of anomalous contagion patterns and the limitations of the proposed methodology. 

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Articles
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2405.01422
url_code: 'https://github.com/luizalober/epidemics-using-features'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Visual representation of the feature engineering method presented in Section 2.3. (A) exemplifies how cities are selected according to spatial distance or similarities between
time series representing the GDP or outbreak size evolution. (B) The prediction is performed by combining the time series of the selected cities. The forecasting on the target city
is shown in red.'
  focal_point: ""
  preview_only: false
---
