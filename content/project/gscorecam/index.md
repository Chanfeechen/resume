---
title: gScoreCAM, What objects is CLIP looking at?
summary: Based on the observations that CLIP ResNet-50 channels are very noisy compared to typical ImageNet-trained ResNet-50, and most saliency methods obtain pretty low object localization scores with CLIP. By visualizing the top 10% most sensitive (highest-gradient) channels, our gScoreCAM obtains the state of the art weakly supervised localization results using CLIP (in both ResNet and ViT versions).
tags:
  - Deep Learning
date: '2022-01-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: arxiv
    icon_pack: fab
    name: pdf
    url: https://openaccess.thecvf.com/content/ACCV2022/html/Chen_gScoreCAM_What_objects_is_CLIP_looking_at_ACCV_2022_paper.html
  - icon: github
    icon_pack: fab
    name: code
    url: https://github.com/anguyen8/gScoreCAM
  - icon: youtube
    icon_pack: fab
    name: video
    url: https://www.youtube.com/watch?v=YtDwwS94GlI
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
slides: ""
---

# gScoreCAM: What is CLIP looking at?

### Abstract
Large-scale, multimodal models trained on web data such as OpenAI's CLIP are becoming the foundation of many applications. Yet, they are also more complex to understand, test, and therefore align with human values. In this paper, we propose gScoreCAM--a state-of-the-art method for visualizing the main objects that CLIP is looking at in an image. On zero-shot object detection, gScoreCAM performs similarly to ScoreCAM, the best prior art on CLIP, yet 8 to 10 times faster. Our method outperforms other existing, well-known methods (HilaCAM, RISE, and the entire CAM family) by a large margin, especially in multi-object scenes. gScoreCAM sub-samples k = 300 channels (from 3,072 channels--i.e. reducing complexity by almost 10 times) of the highest gradients and linearly combines them into a final "attention" visualization. We demonstrate the utility and superiority of our method on three datasets: ImageNet, COCO, and PartImageNet. Our work opens up interesting future directions in understanding and de-biasing CLIP.

