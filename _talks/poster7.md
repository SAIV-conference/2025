---
name: "Semantic Robustness Verification for Neural Networks using Image Similarity Measures"
speakers: 
  - Jannick Strobel
  - David Boetius
  - Paolo Arcaini
  - Fuyuki Ishikawa
  - Stefan Leue 
categories:
  - Posters
  - Poster
---

### Abstract

This work investigates the semantic robustness of neural networks to adversarial examples by utilising image similarity measures. Traditional robustness properties rely heavily on $L^p$ norms, which do not always manage to capture perceptual and structural similarities, so that valid adversarial examples are often not recognized. To address this limitation, we propose to incorporate image similarity metrics such as the Structural Similarity Index Measure (SSIM) into the robustness specification, allowing for a broader and more semantically meaningful definition of adversarial perturbations.
In our work, we fomulate neural networks as Mixed Integer Non-Linear Programming problems. We use the SSIM as a distance measure to define robustness properties. This formulation extends existing verification techniques to support the verification of these non-linear and semantically meaningful robustness specifications.
We validate the proposed method on classifiers trained on the MNIST and German Traffic Sign Recognition Benchmark datasets. The results demonstrate the feasibility of verifying semantic robustness in small networks, thereby
advancing robustness verification by enabling the detection of adversarial examples using perceptually meaningful measures. The code is available at https://github.com/sen-uni-kn/semantic-robustness-verification.


