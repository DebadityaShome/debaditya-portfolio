---
title: "Region-Disentangled Diffusion Model for High-Fidelity PPG-to-ECG Translation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Pritam Sarkar
- Ali Etemad

main:
  - name: Pre-print
    url: https://arxiv.org/abs/2308.13568
    weight: 10

publication: "Published at *Thirty-Eighth AAAI Conference on Artificial Intelligence (AAAI-24)*"
publication_short: ""

abstract: "The high prevalence of cardiovascular diseases (CVDs) calls for accessible and cost-effective continuous cardiac monitoring tools. Despite Electrocardiography (ECG) being the gold standard, continuous monitoring remains a challenge, leading to the exploration of Photoplethysmography (PPG), a promising but more basic alternative available in consumer wearables. This notion has recently spurred interest in translating PPG to ECG signals. In this work, we introduce Region-Disentangled Diffusion Model (RDDM), a novel diffusion model designed to capture the complex temporal dynamics of ECG. Traditional Diffusion models like Denoising Diffusion Probabilistic Models (DDPM) face challenges in capturing such nuances due to the indiscriminate noise addition process across the entire signal. Our proposed RDDM overcomes such limitations by incorporating a novel forward process that selectively adds noise to specific regions of interest (ROI) such as QRS complex in ECG signals, and a reverse process that disentangles the denoising of ROI and non-ROI regions. Quantitative experiments demonstrate that RDDM can generate high-fidelity ECG from PPG in as few as 10 diffusion steps, making it highly effective and computationally efficient. Additionally, to rigorously validate the usefulness of the generated ECG signals, we introduce CardioBench, a comprehensive evaluation benchmark for a variety of cardiac-related tasks including heart rate and blood pressure estimation, stress classification, and the detection of atrial fibrillation and diabetes. Our thorough experiments show that RDDM achieves state-of-the-art performance on CardioBench. To the best of our knowledge, RDDM is the first diffusion model for cross-modal signal-to-signal translation in the bio-signal domain."

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
