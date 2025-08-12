---
title: "Token-Level Density-Based Uncertainty Quantification Methods for Eliciting Truthfulness of Large Language Models"
collection: talks
type: "Talk"
link: https://aclanthology.org/2025.naacl-long.113/
venue: "NAACL-2025, oral"
date: 2025-04-30
location: "Albuquerque, New Mexico"
---

Uncertainty quantification (UQ) is a prominent approach for eliciting truthful answers from large language models (LLMs). To date, information-based and consistency-based UQ have been the dominant UQ methods for text generation via LLMs. Density-based methods, despite being very effective for UQ in text classification with encoder-based models, have not been very successful with generative LLMs. In this work, we adapt Mahalanobis Distance (MD) – a well-established UQ technique in classification tasks – for text generation and introduce a new supervised UQ method. Our method extracts token embeddings from multiple layers of LLMs, computes MD scores for each token, and uses linear regression trained on these features to provide robust uncertainty scores. Through extensive experiments on eleven datasets, we demonstrate that our approach substantially improves over existing UQ methods, providing accurate and computationally efficient uncertainty scores for both sequence-level selective generation and claim-level fact-checking tasks. Our method also exhibits strong generalization to out-of-domain data, making it suitable for a wide range of LLM-based applications.
