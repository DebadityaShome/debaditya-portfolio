---
title: "FedAffect: Few-Shot Federated Learning for Facial Expression Recognition"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- T. Kar

date: "2021-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops*
publication_short: In *ICCVW*

abstract: Annotation of large-scale facial expression datasets in the real world is a major challenge because of privacy concerns of the individuals due to which traditional supervised learning approaches won't scale. Moreover, training models on large curated datasets often leads to dataset bias which reduces generalizability for real world use. Federated learning is a recent paradigm for training models collaboratively with decentralized private data on user devices. **In this paper, we propose a few-shot federated learning framework which utilizes few samples of labeled private facial expression data to train local models in each training round and aggregates all the local model weights in the central server to get a globally optimal model. In addition, as the user devices are a large source of unlabeled data, we design a federated learning based self-supervised method to disjointly update the feature extractor network on unlabeled private facial data in order to learn robust and diverse face representations.** Experimental results by testing the globally trained model on benchmark datasets (FER-2013 and FERG) show comparable performance with state of the art centralized approaches. To the best of author's knowledge, this is the first work on few-shot federated learning for facial expression recognition.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/ICCV2021W/HTCV/papers/Shome_FedAffect_Few-Shot_Federated_Learning_for_Facial_Expression_Recognition_ICCVW_2021_paper.pdf'
url_code: ''
url_dataset: ''
url_poster: 'poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://drive.google.com/file/d/17YHCE74ppnvv6pFa3GvI5nKowtlyvMD3/view?usp=sharing'

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
