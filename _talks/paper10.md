---
name: "Abstraction-Based Proof Production in Formal Verification of Neural Networks"
speakers:
  - Yizhak Yisrael Elboher
  - Omri Isac
  - Guy Katz
  - Tobias Ladner
  - Haoze Wu  
categories:
  - Presentation
  - Paper
  - "Chair: Anna Lukina"
links:
  - name: Paper
    file: paper10.pdf
---

### Abstract

Modern verification tools for deep neural networks (DNNs) increasingly rely on abstraction to scale to realistic architectures. In parallel, proof production is becoming a critical requirement for increasing the reliability of DNN verification results. However, current proof-producing verifiers do not support abstraction-based reasoning, creating a gap between scalability and provable guarantees. We address this gap by introducing a novel framework for proof-producing abstraction-based DNN verification. Our approach modularly separates the verification task into two components: proving the property on an abstract network, and proving the soundness of the abstraction with respect to the original DNN. The former can be handled by existing proof-producing verifiers, whereas we propose the first method for generating formal proofs for the latter. This preliminary work aims to enable scalable and trustworthy verification by supporting common abstraction techniques within a formal proof framework.