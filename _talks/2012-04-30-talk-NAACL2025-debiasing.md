---
title: "Inference-Time Selective Debiasing to Enhance Fairness in Text Classification Models"
collection: talks
type: "Talk"
link: https://aclanthology.org/2025.naacl-short.9/
venue: "NAACL-2025, oral"
date: 2025-04-30
location: "Albuquerque, New Mexico"
---

We propose selective debiasing – an inference-time safety mechanism designed to enhance the overall model quality in terms of prediction performance and fairness, especially in scenarios where retraining the model is impractical. The method draws inspiration from selective classification, where at inference time, predictions with low quality, as indicated by their uncertainty scores, are discarded. In our approach, we identify the potentially biased model predictions and, instead of discarding them, we remove bias from these predictions using LEACE – a post-processing debiasing method. To select problematic predictions, we propose a bias quantification approach based on KL divergence, which achieves better results than standard uncertainty quantification methods. Experiments on text classification datasets with encoder-based classification models demonstrate that selective debiasing helps to reduce the performance gap between post-processing methods and debiasing techniques from the at-training and pre-processing categories.
