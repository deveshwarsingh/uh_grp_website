---
title: 'Deep learning based emulator for simulating CMAQ surface NO2 levels over the CONUS'
authors:
  - Ahmed_Salman
  - admin
  - Jincheol_Park
  - Mahsa_Payami
  - Semko_Mahmoudreza
  - Masoud_Ghahremanloo
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'
date: '2024-01-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.atmosenv.2023.120192'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Atmospheric Environment, Volume 316, 120192'
publication_short: ''

abstract: This study details the development and evaluation of an emulator model of the Community Multiscale Air Quality (CMAQ) model, utilizing a U-Net deep learning architecture to accelerate the simulation of surface NO2 concentrations across the Contiguous United States (CONUS). The emulator employs a subset of meteorological, land cover, and emission input variables identical to those in CMAQ. An initial assessment of the model based on 3-fold monthly cross-validation during the summer (JJA) demonstrates excellent accuracy for 1-h NO2 concentration, with a correlation coefficient (R) of 0.979 and an Index of Agreement (IOA) of 0.989. Subsequently, the model's robustness is examined by training it with NEI 2011 and 2014 data and then evaluating it using NEI 2017 data. This yields an R of 0.949 and an IOA of 0.974. We utilize the emulator to investigate the semi-normalized sensitivity of NO2 concentrations to NOx emissions, which exhibits a satisfactory alignment with CMAQ Decoupled Direct Method (DDM) sensitivities, with an MAE of 0.271 ppb for 1-h sensitivity coefficients. Diurnal cycle analysis of NOx sensitivity coefficients spatially averaged in 15 major urban environments indicates slight over- and underestimations of the morning and evening peaks, respectively, with the MAE varying from 0.27 (Dallas) to 0.92 ppb (Los Angeles). Remarkably, the emulator's computational efficiency significantly surpasses CMAQ's, providing more than 400 times the simulation speed on a single CPU and over 600 times when utilizing both CPU and GPU. As such, the emulator represents a promising tool for efficient CMAQ modeling, with potential applications in health impact assessments, emission reduction strategies, and emission inventory optimization.

# Summary. An optional shortened abstract.
summary: Developed a high-accuracy emulator of CMAQ to perform surface NO2 simulations, while ensuring its robustness. Sensitivity of NO2 concentrations to NOx emissions from the emulator showed a strong agreement with CMAQ DDM. The emulator surpassed CMAQ in computational speed, suggesting a potential for further accelerating CMAQ simulations.

#tags:
  #- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S1352231023006180/pdfft?md5=ce6340fe2440b8befdfc2d5b5ae97c80&pid=1-s2.0-S1352231023006180-main.pdf
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
  caption: content/publication/journal-article/asalman_2023_digital_twin/featured_asalman.jpeg
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

Supplementary notes can be accessed [here](https://doi.org/10.1016/j.atmosenv.2023.120192).
