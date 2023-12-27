---
title: AI-Deep Learning Modeling for Forecasting Ozone Air Quality, Weather, and Remotely Sensed AOD. 

event: OpenNEX seminar at NASA Ames Research Center                
event_url: https://www.youtube.com/watch?v=7qqIaxQ8vyc

location: NASA Ames Research Center                               
address:
  street: 
  city: 'Moffett Field'                         
  region: CA
  postcode: 
  country: United States

summary: Deep Learning talk at NASA Ames Research Center in July 2019

abstract: 'A new computationally-efficient deep learning (DL)-based ozone forecasting model is proposed. The model uses the Community Multiscale Air Quality (CMAQ), called CMAQ-AI, to forecast surface ozone. We train a deep convolutional neural network (CNN) to perform bias correction with CMAQ outputs (used as DL inputs) with the corresponding observed hourly ozone concentration (as DL target). The CMAQ outputs are the meteorological parameters from the Meteorology-Chemistry Interface Processor (MCIP) and ozone precursors from CMAQ. The model was trained using three years of CMAQ forecasts of hourly ozone concentrations over the United States from April to October.
Similarly, another DL model was trained using three years of WRF forecast of weather variables over Korea. The forecasting results are evaluated for the following year of the training period. The CMAQ-AI and WRF-AI model significantly improved the CMAQ and WRF performance both in the Pearson correlation coefficient and index of agreement. The proposed approach can be applied to other air pollutants and weather variables.
Remote sensing data of Aerosol Optical Depth (AOD) faces the limitations of data occlusion due to cloud cover. Here, we utilized a deep learning technique, called partial convolution, as a generalized model for the reconstruction of the AOD images. For the evaluation purpose, the model receives full hourly AOD images, provided by Community Multi-scale Air Quality Model (CAMQ) as input to reconstruct the original image with the artificial randomized missing area(s). For training and testing process of the partial convolutional model, CMAQ data from 2014-2016 over East Asia were used. Results indicate that the partial convolutional model can predict missing data with a lower mean absolute error (MAE) and a higher Index of Agreement (IOA) and Pearson correlation coefficient (r) than kriging. The partial convolution model was achieving more stable results with less variance of predictions than kriging in all statistical evaluation methods. Moreover, deep learning models make predictions considerably faster, requiring only one-time training for predicting an entire year - saving considerable processing time. Once the reconstructed 2D AOD data are ready, forecasting AI model was trained to forecast the motion of the high-AOD air mass. This proposed approach can be applied to air masses of air pollutants and extreme weather such as hurricanes.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2019-07-18T00:00:00Z'
date_end: '2019-07-18T00:46:14Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2019-07-19T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: featured_new.png
  focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

<!-- Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://docs.hugoblox.com/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/writing-markdown-latex/).

Further event details, including page elements such as image galleries, can be added to the body of this page. -->
