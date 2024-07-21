---
name: Parallel Verification for δ-Equivalence of Neural Network Quantization
speakers:
  - Pei Huang
  - Yuting Yang
  - Haoze Wu
  - Ieva Daukantas
  - Min Wu
  - Fuqi Jia
  - Clark Barrett
categories:
  - Presentation
  - Paper
  - "Chair: Christopher Brix"
---

### Abstract

*Quantization* replaces floating point arithmetic with integer arithmetic in deep neural networks, enabling more efficient on-device inference with less power and memory. However, it also brings in loss of generalization and even potential errors to the models. In this work, we propose a parallelization technique for formally *verifying* the *equivalence* between quantized models and their original real-valued counterparts. In order to guarantee both *soundness* and *completeness*, mixed integer linear programming (MILP) is deployed as the baseline technique. Nevertheless, the incorporation of two networks as well as the mixture of integer and real number arithmetic make the problem much more challenging than verifying a single network, and thus using MILP alone is inadequate for the non-trivial cases. To tackle this, we design a distributed verification technique that can leverage hundreds of CPUs on high-performance computing clusters. We develop a two-tier parallel framework and propose property- and output-based partition strategies. Evaluated on perception networks quantized with PyTorch, our approach outperforms existing methods in successfully verifying many cases that are otherwise considered infeasible.
