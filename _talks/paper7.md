---
name: "Robustness Margin: A new measure for the robustness of neural networks"
speakers:
  - Lionel Kielhofer
  - Annelot Willemijn Bosman
  - Jan N. van Rijn
  - Holger Hoos 
categories:
  - Presentation
  - Paper
  - "Chair: Anna Lukina"
---

### Abstract

Neural networks are vulnerable to small input perturbations, which can cause misclassifications to instances that would be correctly classified otherwise. Therefore, assessing the robustness of a neural network is essential in safety-critical applications. Existing robustness measures, such as local robustness, fail to capture the robustness of individual inputs to the network and are not easy to interpret, making them unsuitable for comparing different networks. This work introduces a novel robustness measure that addresses these issues by using a probabilistic model of robustness and evaluating its quantiles. Furthermore, we propose both a parametric and a non-parametric estimator to compute confidence bounds for this measure. We evaluate both estimators based on their accuracy and precision over the amount of data used. Both perform reliably given sufficient data; however, the parametric estimator achieves comparable performance with about half as much data, rendering it computationally more efficient.