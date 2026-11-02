+++
featured = true
title = "What is CLIP looking at?"
date = "2022-08-01"
description = "Visual explanations for the objects behind CLIP\u2019s predictions."
cover = "featured.png"
coverAlt = "What is CLIP looking at? \u2014 research overview"
+++

[Read the paper ↗](https://openaccess.thecvf.com/content/ACCV2022/html/Chen_gScoreCAM_What_objects_is_CLIP_looking_at_ACCV_2022_paper.html) · [Source code ↗](https://github.com/anguyen8/gScoreCAM)

### Abstract
Large-scale, multimodal models trained on web data such as OpenAI's CLIP are becoming the foundation of many applications. Yet, they are also more complex to understand, test, and therefore align with human values. In this paper, we propose gScoreCAM--a state-of-the-art method for visualizing the main objects that CLIP is looking at in an image. On zero-shot object detection, gScoreCAM performs similarly to ScoreCAM, the best prior art on CLIP, yet 8 to 10 times faster. Our method outperforms other existing, well-known methods (HilaCAM, RISE, and the entire CAM family) by a large margin, especially in multi-object scenes. gScoreCAM sub-samples k = 300 channels (from 3,072 channels--i.e. reducing complexity by almost 10 times) of the highest gradients and linearly combines them into a final "attention" visualization. We demonstrate the utility and superiority of our method on three datasets: ImageNet, COCO, and PartImageNet. Our work opens up interesting future directions in understanding and de-biasing CLIP.
