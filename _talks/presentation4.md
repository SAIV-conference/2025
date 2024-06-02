---
name: Boosting Few-Pixel Robustness Verification via Covering Verification Designs
speakers:
  - Yuval Shapira
  - Naor Wiesel
  - Shahar Shabelman
  - Dana Drachsler-Cohen
categories:
  - Presentation
---

### Abstract

Proving local robustness is crucial to increase the reliability of neural networks. While many verifiers prove robustness in L<sub>∞</sub> ϵ-balls, very little work deals with robustness verification in L<sub>0</sub> ϵ-balls, capturing robustness to few pixel attacks. This verification introduces a combinatorial challenge, because the space of perturbations is discrete and of exponential size. A previous work relies on covering designs to identify sets for defining L<sub>∞</sub> neighborhoods, which if proven robust imply that the L<sub>0</sub> ϵ-ball is robust. However, the number of neighborhoods to verify remains very high, leading to a high analysis time. We propose covering verification designs, a combinatorial design that tailors effective but analysis-incompatible coverings to L<sub>0</sub> robustness verification. The challenge is that computing a covering verification design introduces a high time and memory overhead, which is intensified in our setting, where multiple candidate coverings are required to identify how to reduce the overall analysis time. We introduce CoVerD, an L<sub>0</sub> robustness verifier that selects between different candidate coverings without constructing them, but by predicting their set sizes' distribution. This prediction relies on a theorem providing closed-form expressions for the mean and variance of this distribution. For the chosen covering, CoVerD constructs the covering verification design on-the-fly, while keeping the memory consumption minimal and enabling to parallelize the analysis. The experimental results show that CoVerD reduces the verification time on average by up to 5.1x compared to prior work, as well as scales to larger L<sub>0</sub> ϵ-balls.
