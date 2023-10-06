---
title: "A Transfer Learning and Explainable Solution to Detect mpox from Smartphones images"
authors:
- Mattia Giovanni Campana
- admin
- Franca Delmastro
- Sergio Mascetti
- Elena Pagani
date: "2023-05-29T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2305.18489"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In recent months, the monkeypox (mpox) virus -- previously endemic in a limited area of the world -- has started spreading in multiple countries until being declared a ``public health emergency of international concern'' by the World Health Organization. The alert was renewed in February 2023 due to a persisting sustained incidence of the virus in several countries and worries about possible new outbreaks. Low-income countries with inadequate infrastructures for vaccine and testing administration are particularly at risk. 
A symptom of mpox infection is the appearance of skin rashes and eruptions, which can drive people to seek medical advice. A technology that might help perform a preliminary screening based on the aspect of skin lesions is the use of Machine Learning for image classification. However, to make this technology suitable on a large scale, it should be usable directly on mobile devices of people, with a possible notification to a remote medical expert. 
In this work, we investigate the adoption of Deep Learning to detect mpox from skin lesion images. The proposal leverages Transfer Learning to cope with the scarce availability of mpox image datasets. As a first step, a homogenous, unpolluted, dataset is produced by manual selection and preprocessing of available image data. It will also be released publicly to researchers in the field. Then, a thorough comparison is conducted amongst several Convolutional Neural Networks, based on a 10-fold stratified cross-validation. The best models are then optimized through quantization for use on mobile devices; measures of classification quality, memory footprint, and processing times validate the feasibility of our proposal. Additionally, the use of eXplainable AI is investigated as a suitable instrument to both technically and clinically validate classification outcomes."

# Summary. An optional shortened abstract.
summary: 'arXiv'

tags:
- Machine Learning
- Audio and Speech Processing
- XAI
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2305.18489.pdf'
url_code: 'https://github.com/mattiacampana/Monkeypox-Detection'
url_dataset: 'https://air.unimi.it/handle/2434/974731'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
