---
title: How explainable are adversarially-robust cnns?
summary: We perform the first, large-scale evaluation of the relations of the three criteria using 9 feature-importance methods and 12 ImageNet-trained CNNs that are of 3 training algorithms and 5 CNN architectures.
tags:
  - Deep Learning
date: '2022-08-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: arxiv
    icon_pack: fab
    name: pdf
    url: https://arxiv.org/abs/2205.13042
  # - icon: github
  #   icon_pack: fab
  #   name: code
  #   url: https://github.com/anguyen8/gScoreCAM
  # - icon: youtube
  #   icon_pack: fab
  #   name: video
  #   url: https://www.youtube.com/watch?v=YtDwwS94GlI
  #   label: Watch the video
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# How explainable are adversarially-robust cnns?

### Abstract
Three important criteria of existing convolutional neural networks (CNNs) are (1) test-set accuracy; (2) out-of-distribution accuracy; and (3) explainability. While these criteria have been studied independently, their relationship is unknown. For example, do CNNs that have a stronger out-of-distribution performance have also stronger explainability? Furthermore, most prior feature-importance studies only evaluate methods on 2-3 common vanilla ImageNet-trained CNNs, leaving it unknown how these methods generalize to CNNs of other architectures and training algorithms. Here, we perform the first, large-scale evaluation of the relations of the three criteria using 9 feature-importance methods and 12 ImageNet-trained CNNs that are of 3 training algorithms and 5 CNN architectures. We find several important insights and recommendations for ML practitioners. First, adversarially robust CNNs have a higher explainability score on gradient-based attribution methods (but not CAM-based or perturbation-based methods). Second, AdvProp models, despite being highly accurate more than both vanilla and robust models alone, are not superior in explainability. Third, among 9 feature attribution methods tested, GradCAM and RISE are consistently the best methods. Fourth, Insertion and Deletion are biased towards vanilla and robust models respectively, due to their strong correlation with the confidence score distributions of a CNN. Fifth, we did not find a single CNN to be the best in all three criteria, which interestingly suggests that CNNs are harder to interpret as they become more accurate.

