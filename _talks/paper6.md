---
name: "(Hybrid) GRENA: GPU-aided Abstract Refinement for Neural Network Verification"
speakers:
  - Yuyi Zhong
  - Shaun Tan Zong Zhi
  - Hanping Xu
  - Siau-Cheng Khoo 
categories:
  - Presentation
  - Paper
  - "Chair: Elena Botoeva"

---

### Abstract

Since neural network verification problems can be formulated as optimization problems, linear programming (LP) solvers have been deployed as off-the-shelf tools in such processes. However, existing LP solvers running on CPU scale poorly on large networks. To expedite the process, we propose an LP-solving theorem tailored to neural network verification. In practice, we transform the constrained solving problem into an unconstrained problem that can be executed on GPUs, significantly speeding up the solving process. We explicitly include constraints on layers that take more than one predecessor instead of handling multiple predecessors by inefficient concatenation. Our theorem applies to widely used networks, such as fully connected, convolutional, and residual networks. From our evaluation, our GPU-aided solver achieves comparable precision to the state-of-the-art (SOTA) solver GUROBI with significant speed improvements and helps acquire competitive verification precision compared to advanced verification methods.