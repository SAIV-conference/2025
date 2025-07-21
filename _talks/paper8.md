---
name: "CTRAIN - A Training Library for Certifiably Robust Neural Networks"
speakers:
  - Konstantin Kaulen
  - Holger Hoos  
categories:
  - Presentation
  - Paper
  - "Chair: Kaushik Mallik"

---

### Abstract

Despite their widespread success, neural networks are susceptible to adversarial examples, severely limiting their responsible deployment in safety-critical scenarios. To address this, neural network verification techniques have been proposed that rigorously prove the robustness of a given network against specific threats. However, the scalability of these methods remains a major challenge, with networks trained for empirical robustness still proving difficult to verify. Thus, certified training has been proposed to produce networks more amenable to formal robustness verification. However, there is currently no comprehensive framework allowing easy access to these training methods. To address this, we introduce CTRAIN, a new Python library built upon the auto_LiRPA package, which reimplements state-of-the-art certified training methods in a unified, modular and comprehensive manner, while offering user-friendly interfaces, enhancing accessibility for both researchers and practitioners. Additionally, CTRAIN integrates SMAC3 for hyperparameter optimisation and αβ-CROWN for complete verification, empowering users to exploit these systems to achieve state-of-the-art certified robustness. We provide code, documentation, examples and usage instructions at github.com/ada-research/CTRAIN.