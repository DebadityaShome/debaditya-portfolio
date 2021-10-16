---
title: "COVID-Transformer: Interpretable COVID-19 Detection using Vision Transformer for Healthcare"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

date: "2021-07-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Under minor revision at *MDPI International Journal of Environmental Research and Public Health (Digital health track)*
publication_short: ""

abstract: "In the recent pandemic, accurate and rapid testing of patients remained a critical task in the diagnosis and control of COVID-19 disease spread in the healthcare industry. Because of the sudden increase in cases, most countries have faced scarcity and a low rate of testing. Chest x-rays have been shown in the literature to be a potential source of testing for COVID-19 patients, but manually checking x-ray reports is time-consuming and error-prone. Considering these limitations and the advancements in data science, we proposed a Vision Transformer based deep learning pipeline for COVID-19 detection from chest x-ray based imaging. Due to the lack of large data sets, we collected data from three open-source data sets of chest x-ray images and aggregated them to form a 30K image data set, which is the largest publicly available collection of chest x-ray images in this domain to our knowledge. Our proposed transformer model effectively differentiates COVID-19 from normal chest x-rays with an accuracy of 98 % along with an AUC score of 99 % in the binary classification task. It distinguishes COVID-19, normal, and pneumonia patient's x-rays with an accuracy of 92 % and AUC score of 98 % in the Multi-class classification task. For evaluation on our data set, we fine-tuned some of the widely used models in literature namely EfficientNetB0, InceptionV3, Resnet50, MobileNetV3, Xception, and DenseNet-121 as baselines. Our proposed transformer model outperformed them in terms of all metrics. In addition, a Grad-CAM based visualization is created which makes our approach interpretable by radiologists and can be used to monitor the progression of the disease in the affected lungs, assisting healthcare."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: ''
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
