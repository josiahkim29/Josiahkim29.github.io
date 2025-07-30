---
title: "PiggyCast: Improving Weather Prediction Accuracy through a Stacking-Based Ensemble AI Approach"

authors:
  - admin
  - Josiah K. Kimani
date: "2025-07-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Recently, AI Weather Prediction (AIWP) models have outperformed classical Numerical Weather Prediction (NWP) Models in various weather prediction benchmarking criteria. Given the paradigm shift from numerical to machine learning models, such forecasts can be generated in seconds to minutes on a standard laptop. Forecast datasets from frontier AIWP models for the year 2020 have been made publicly available on the WeatherBench 2 website, facilitating independent analysis, evaluation, and further research. In this study, we introduce a traditional machine learning model trained on top of these forecast datasets (a method known as “stacking”) to predict ERA5 variables, thereby exploiting the strengths of each base model and aiming to outperform forecasts from any base model alone. We coin our model 'PiggyCast', as we effectively piggyback off the work done by leading AI research teams with expertise and compute budgets for model training that are hard to match in an MSc thesis.  The improvement in PiggyCast's Root Mean Squared Error on Geopotential Height at 500 hPa pressure, relative to the base models, was notable, with an increase in performance as forecast lead time increased. Given the low compute cost of making forecasts, and that each frontier AIWP model has its strengths and limitations (depending on the weather variable, region of the globe, and forecast lead time), we argue that the future of the most skilful weather forecasts will likely come from machine learning stacking, by the very nature that stacking typically yields performance better than any base model alone.

# Summary. An optional shortened abstract.
summary: In this study, we propose a supervised machine learning ensemble strategy, known as 'PiggyCast', trained on top of these forecast datasets (a method known as “stacking”) to predict ERA5 variables.

tags:
- Artificial Intelligence in Climate Science

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: https://github.com/josiahkim29/AIMS_Masters_Thesis/blob/main/Report/Josiah_Kimani_AIMS_Masters_Thesis.pdf
url_code: 'https://github.com/josiahkim29/AIMS_Masters_Thesis'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Gemini**]()'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
