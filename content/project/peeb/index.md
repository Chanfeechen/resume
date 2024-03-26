---
title: PEEB, Part-based Bird Classifier with an Explainable and Editable Language Bottleneck
summary: We proposed a part-based bird classifier that makes predictions based on part-wise descriptions. Our method directly utilizes human-provided descriptions (in this work, from GPT4). It outperforms CLIP and M&V by 10 points in CUB and 28 points in NABirds.
tags:
  - Deep Learning
date: '2024-03-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: arxiv
    icon_pack: fab
    name: pdf
    url: https://arxiv.org/abs/2403.05297
  - icon: github
    icon_pack: fab
    name: code
    url: https://github.com/anguyen8/peeb
#   - icon: youtube
#     icon_pack: fab
#     name: video
#     url: https://www.youtube.com/watch?v=YtDwwS94GlI
    label: Watch the video
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

# PEEB: Part-based Bird Classifier with an Explainable and Editable Language Bottleneck

### Abstract
CLIP-based classifiers rely on the prompt containing a {class name} that is known to the text encoder. That is, CLIP performs poorly on new classes or the classes whose names rarely appear on the Internet (e.g., scientific names of birds). For fine-grained classification, we propose PEEB - an explainable and editable classifier to (1) express the class name into a set of pre-defined text descriptors that describe the visual parts of that class; and (2) match the embeddings of the detected parts to their textual descriptors in each class to compute a logit score for classification. In a zero-shot setting where the class names are unknown, PEEB outperforms CLIP by a large margin (~10x in accuracy). Compared to part-based classifiers, PEEB is not only the state-of-the-art on the supervised-learning setting (88.80% accuracy) but also the first to enable users to edit the class definitions to form a new classifier without retraining. Compared to concept bottleneck models, PEEB is also the state-of-the-art in both zero-shot and supervised learning settings.