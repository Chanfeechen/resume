+++
featured = true
title = "PEEB: explaining a bird, part by part"
date = "2024-03-01"
description = "An editable bird classifier that connects visual parts with language descriptions."
cover = "featured.png"
coverAlt = "PEEB: explaining a bird, part by part \u2014 research overview"
+++

[Read the paper ↗](https://arxiv.org/abs/2403.05297) · [Source code ↗](https://github.com/anguyen8/peeb)

### Abstract
CLIP-based classifiers rely on the prompt containing a {class name} that is known to the text encoder. That is, CLIP performs poorly on new classes or the classes whose names rarely appear on the Internet (e.g., scientific names of birds). For fine-grained classification, we propose PEEB - an explainable and editable classifier to (1) express the class name into a set of pre-defined text descriptors that describe the visual parts of that class; and (2) match the embeddings of the detected parts to their textual descriptors in each class to compute a logit score for classification. In a zero-shot setting where the class names are unknown, PEEB outperforms CLIP by a large margin (~10x in accuracy). Compared to part-based classifiers, PEEB is not only the state-of-the-art on the supervised-learning setting (88.80% accuracy) but also the first to enable users to edit the class definitions to form a new classifier without retraining. Compared to concept bottleneck models, PEEB is also the state-of-the-art in both zero-shot and supervised learning settings.
