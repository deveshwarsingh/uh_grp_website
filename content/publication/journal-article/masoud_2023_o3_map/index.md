---
title: 'Deep learning mapping of surface MDA8 ozone: The impact of predictor variables on ozone levels over the contiguous United States'
authors:
  - Masoud_Ghahremanloo
  - admin
  - Yannic Lops
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'
date: '2023-06-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.envpol.2023.121508'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Environmental Pollution, Volume 326, 121508'
publication_short: ''

abstract: The limited number of ozone monitoring stations imposes uncertainty in various applications, calling for accurate approaches to capturing ozone values in all regions, particularly those with no in-situ measurements. This study uses deep learning (DL) to accurately estimate daily maximum 8-hr average (MDA8) ozone and examines the spatial contribution of several factors on ozone levels over the contiguous U.S. (CONUS) in 2019. A comparison between in-situ observations and DL-estimated MDA8 ozone values shows a correlation coefficient (R) of 0.95, an index of agreement (IOA) of 0.97, and a mean absolute bias (MAB) of 2.79 ppb, highlighting the promising performance of the deep convolutional neural network (Deep-CNN) at estimating surface MDA8 ozone. Spatial cross-validation also confirms the high spatial accuracy of the model, which obtains an R of 0.91, and IOA of 0.96 and an MAB of 3.46 ppb when it is trained and tested on separate stations. To interpret the black-box nature of our DL model, we use Shapley additive explanations (SHAP) to generate a spatial feature contribution map (SFCM), the results of which confirm an advanced ability of Deep-CNN to capture the interactions between most predictor variables and ozone. For instance, the model shows that solar radiation (SRad) SFCM, with higher values, enhances the formation of ozone, particularly in the south and southwestern CONUS. As SRad triggers ozone precursors to produce ozone via photochemical reactions, it increases ozone concentrations. The model also shows that humidity, with its low values, increases ozone concentrations in the western mountainous regions. The negative correlation between humidity and ozone levels can be attributed to factors such as higher ozone decomposition resulting from increased levels of humidity and OH radicals. This study is the first to introduce the SFCM to investigate the spatial role of predictor variables on changes in estimated MDA8 ozone levels.

# Summary. An optional shortened abstract.
summary: 'This study uses deep learning (DL) to accurately estimate daily maximum 8-hr average (MDA8) ozone and examines the spatial contribution of several factors on ozone levels over the contiguous U.S. (CONUS) in 2019.'

#tags:
  #- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0269749123005109/pdfft?md5=d41c0e8f94ecb0e77a61734c101069fb&pid=1-s2.0-S0269749123005109-main.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: content/publication/journal-article/masoud_2023_o3_map/featured_masoud.jpeg
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
Click the _Cite_ button above to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be accessed [here](https://ars.els-cdn.com/content/image/1-s2.0-S0269749123005109-mmc1.docx).
