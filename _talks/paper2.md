---
name: "Error Analysis of Shapley Value-Based Model Explanations: An Informative Perspective"
speakers:
  - Ningsheng Zhao
  - Jia Yuan Yu
  - Krzysztof Dzieciolowski
  - Trang Bui
categories:
  - Presentation
  - Paper
  - "Chair: Ravi Mangal"
---

### Abstract

Shapley value attribution (SVA) is an increasingly popular explainable AI (XAI) method, which quantifies the contribution of each feature to the model’s output. However, recent work has shown that most existing methods to implement SVAs have some drawbacks, resulting in biased or unreliable explanations that fail to correctly capture the true intrinsic relationships between features and model outputs. Moreover, the mechanism and consequences of these drawbacks have not been discussed systematically. In this paper, we propose a novel error theoretical analysis framework, in which the explanation errors of SVAs are decomposed into two components: observation bias and structural bias. We further clarify the underlying causes of these two biases and demonstrate that there is a trade-off between them. Based on this error analysis framework, we develop two novel concepts: over-informative and under-informative explanations. We demonstrate how these concepts can be effectively used to understand potential errors of existing SVA methods. In particular, for the widely deployed assumption-based SVAs, we find that they can easily be under-informative due to the distribution drift caused by distributional assumptions. We propose a measurement tool to quantify such a distribution drift. Finally, our experiments illustrate how different existing SVA methods can be over- or under-informative. Our work sheds light on how errors incur in the estimation of SVAs and encourages new less error-prone methods.
