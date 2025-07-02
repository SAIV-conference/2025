---
name: "Probabilistic verification of neural networks with sampling-based Probability Box propagation"
speakers:
  - Marcel Chwiałkowski
  - Sylvie Putot
  - Eric Goubault  
categories:
  - Presentation
  - Paper
  - "Chair: Anna Lukina"

---

### Abstract

In probabilistic neural network verification, a well-chosen representation of input uncertainty ensures that theoretical analyses accurately reflect real input perturbations. A recent approach based on probability boxes (p-boxes) [1] is introduced in [2] and unifies set-based and probabilistic information on the inputs. The method allows for obtaining guaranteed probabilistic bounds for property satisfaction on feedforward ReLU networks. However, it suffers from conservativeness due to employing set-based propagation methods.In this work we investigate how to sample from p-boxes without loss of information. Based on that, we develop a sampling-based approach for propagating p-boxes through feedforward ReLU networks. We prove that with dense enough coverings of the input p-boxes, the propagated samples accurately represent the output uncertainty and provide error bounds. Additionally, we show how to create coverings for arbitrary p-boxes with various distributions. On the ACASXu benchmark we demonstrate that our approach is applicable in practice, both as a standalone verifier and as a way to assess the conservativeness of the much faster algorithm in [2].

[1] S. Ferson, V. Kreinovich, L. Ginzburg, D. Myers, and K. Sentz. Constructing probability boxes and dempster-shafer structures. 04 2003.[2] E. Goubault and S. Putot. A zonotopic dempster-shafer approach to the quantitative verification of neural networks. pages 324–342, 2024.
