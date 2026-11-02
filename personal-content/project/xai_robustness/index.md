+++
featured = true
title = "Robust models, clearer explanations?"
date = "2022-07-01"
description = "Exploring the relationship between robustness and visual explanations."
cover = "featured.png"
coverAlt = "Robust models, clearer explanations? \u2014 research overview"
+++

[Read the paper ↗](https://arxiv.org/abs/2205.13042)

### Abstract
Three important criteria of existing convolutional neural networks (CNNs) are (1) test-set accuracy; (2) out-of-distribution accuracy; and (3) explainability. While these criteria have been studied independently, their relationship is unknown. For example, do CNNs that have a stronger out-of-distribution performance have also stronger explainability? Furthermore, most prior feature-importance studies only evaluate methods on 2-3 common vanilla ImageNet-trained CNNs, leaving it unknown how these methods generalize to CNNs of other architectures and training algorithms. Here, we perform the first, large-scale evaluation of the relations of the three criteria using 9 feature-importance methods and 12 ImageNet-trained CNNs that are of 3 training algorithms and 5 CNN architectures. We find several important insights and recommendations for ML practitioners. First, adversarially robust CNNs have a higher explainability score on gradient-based attribution methods (but not CAM-based or perturbation-based methods). Second, AdvProp models, despite being highly accurate more than both vanilla and robust models alone, are not superior in explainability. Third, among 9 feature attribution methods tested, GradCAM and RISE are consistently the best methods. Fourth, Insertion and Deletion are biased towards vanilla and robust models respectively, due to their strong correlation with the confidence score distributions of a CNN. Fifth, we did not find a single CNN to be the best in all three criteria, which interestingly suggests that CNNs are harder to interpret as they become more accurate.
