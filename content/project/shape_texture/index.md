---
title: The shape and simplicity biases of adversarially robust imagenet-trained cnns
summary: We perform the first, large-scale evaluation of the relations of the three criteria using 9 feature-importance methods and 12 ImageNet-trained CNNs that are of 3 training algorithms and 5 CNN architectures.
tags:
  - Deep Learning
date: '2020-08-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: arxiv
    icon_pack: fab
    name: pdf
    url: https://arxiv.org/abs/2006.09373
  - icon: github
    icon_pack: fab
    name: code
    url: https://github.com/anguyen8/shape-bias
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

# The shape and simplicity biases of adversarially robust imagenet-trained cnns

### Abstract
Increasingly more similarities between human vision and convolutional neural networks (CNNs) have been revealed in the past few years. Yet, vanilla CNNs often fall short in generalizing to adversarial or out-of-distribution (OOD) examples which humans demonstrate superior performance. Adversarial training is a leading learning algorithm for improving the robustness of CNNs on adversarial and OOD data; however, little is known about the properties, specifically the shape bias and internal features learned inside adversarially-robust CNNs. In this paper, we perform a thorough, systematic study to understand the shape bias and some internal mechanisms that enable the generalizability of AlexNet, GoogLeNet, and ResNet-50 models trained via adversarial training. We find that while standard ImageNet classifiers have a strong texture bias, their R counterparts rely heavily on shapes. Remarkably, adversarial training induces three simplicity biases into hidden neurons in the process of "robustifying" CNNs. That is, each convolutional neuron in R networks often changes to detecting (1) pixel-wise smoother patterns, i.e., a mechanism that blocks high-frequency noise from passing through the network; (2) more lower-level features i.e. textures and colors (instead of objects);and (3) fewer types of inputs. Our findings reveal the interesting mechanisms that made networks more adversarially robust and also explain some recent findings e.g., why R networks benefit from a much larger capacity (Xie et al. 2020) and can act as a strong image prior in image synthesis (Santurkar et al. 2019).


