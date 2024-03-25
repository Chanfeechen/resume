---
title: "gScoreCAM: what is CLIP looking at?"

event: Oral presentation at Asian Conference on Computer Vision (ACCV 2022)
event_url: https://www.youtube.com/watch?v=YtDwwS94GlI&themeRefresh=1

location:
address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: An example talk using Hugo Blox Builder's Markdown slides feature.
abstract: 'This talk introduces gScoreCAM, a novel method to visualize the attention of CLIP. gScoreCAM is a gradient-based method that generates class activation maps for CLIP. We demonstrate that gScoreCAM can provide interpretable visualizations of CLIP's attention, which can help users understand what CLIP is looking at.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2030-06-01T13:00:00Z'
date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right
  preview_only: false
  url: 'image.png'

links: ''
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - gscorecam
---

# Abstract
Large-scale, multimodal models trained on web data such as OpenAI's CLIP are becoming the foundation of many applications. Yet, they are also more complex to understand, test, and therefore align with human values. In this paper, we propose gScoreCAM--a state-of-the-art method for visualizing the main objects that CLIP is looking at in an image. On zero-shot object detection, gScoreCAM performs similarly to ScoreCAM, the best prior art on CLIP, yet 8 to 10 times faster. Our method outperforms other existing, well-known methods (HilaCAM, RISE, and the entire CAM family) by a large margin, especially in multi-object scenes. gScoreCAM sub-samples k = 300 channels (from 3,072 channels--i.e. reducing complexity by almost 10 times) of the highest gradients and linearly combines them into a final "attention" visualization. We demonstrate the utility and superiority of our method on three datasets: ImageNet, COCO, and PartImageNet. Our work opens up interesting future directions in understanding and de-biasing CLIP.