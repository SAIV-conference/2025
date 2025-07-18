---
name: "Formally Verifying Stock Classifiers: A Case Study"
speakers:
categories:
  - Posters
  - Poster
---

### Abstract

In the past decade, Artificial Intelligence (AI) agents, and specifically Deep Neural Networks (DNNs), have been increasingly incorporated into various fields and domains. One such domain is *stock trading*, in which DNN classifiers are used to predict the future price of a given stock based on its performance history. However, despite significant progress in devising such stock predictors, most DNN training techniques are heuristic in nature and lack formal guarantees. Furthermore, the various DNN verification tools developed by the formal methods community are mostly geared toward validating the robustness of image classifiers with regard to input perturbations. These verification tools, although impressive, have barely been demonstrated in real-world domains in general and in stock prediction in particular. In this short paper, we begin bridging this gap and present the first case study for formally verifying DNN-driven stock predictors.     Specifically, we show how to encode various real-world properties as first-order logic queries and how to leverage off-the-shelf DNN verifiers to validate them. As part of this case study, we trained a novel classifier on actual stock performance data, based on which we demonstrated our approach. We see this work as a step toward the incorporation of DNN verification in real-world domains, and specifically in the important field of DNN-based stock price forecasting.