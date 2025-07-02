---
name: "Certified Error Analysis of Homomorphically Encrypted Neural Networks"
speakers:
  - Philipp Daniel Kern
  - Edoardo Manino
  - Carsten Sinz  
categories:
  - Presentation
  - Paper
  - "Chair: Anna Lukina"

---

### Abstract

Fully-Homomorphic Encryption (FHE) has been touted as the ultimate solution for preserving user data privacy in Machine Learning as a Service (MLaaS) applications. Under this scheme, the server never sees the user data in clear, but executes the ML model on encrypted data instead. Unfortunately, efficient FHE schemes only support addition and multiplication operations, which cannot exactly represent common activation functions in neural networks. Substituting activation functions with polynomial approximations may cause significant output deviations. In this paper, we propose ZonoPoly, an efficient algorithm to compute guaranteed bounds on the maximum output deviation of FHE neural networks. We implement our algorithm in the VeryDiff framework by extending its zonotope-based reachability analysis primitives to support high-degree polynomials. Experimental results show that ZonoPoly produces approximately 3x tighter bounds than existing methods in most cases.