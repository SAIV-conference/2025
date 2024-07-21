---
name: Provably Safe Neural Network Controllers via Differential Dynamic Logic
speakers:
  - Samuel Teuber
  - Stefan Mitsch
  - André Platzer
categories:
  - Presentation
  - "Chair: Yuval Shapira"
---

### Abstract

While neural networks (NNs) have a large potential as goal-oriented controllers for Cyber-Physical Systems, verifying the safety of neural network based control systems (NNCSs) poses significant challenges for the practical use of NNs – especially when safety is needed for unbounded time horizons. One reason for this is the intractability of NN and hybrid system analysis. We introduce VerSAILLE (Verifiably Safe AI via Logically Linked Envelopes): The first approach for the combination of differential dynamic logic (dL) and NN verification. By joining forces, we can exploit the efficiency of NN verification tools while retaining the rigor of dL. We reflect a safety proof for a controller envelope in an NN to prove the safety of concrete NNCS on an infinite-time horizon. The NN verification properties resulting from VerSAILLE typically require nonlinear arithmetic while efficient NN verification tools merely support linear arithmetic. To overcome this divide, we present Mosaic: The first sound and complete verification approach for polynomial real arithmetic properties on piece-wise linear NNs. Mosaic lifts off-the-shelf tools for linear properties to the nonlinear setting. An evaluation on case studies, including adaptive cruise control and airborne collision avoidance, demonstrates the versatility of VerSAILLE and Mosaic: It supports the certification of infinite-time horizon safety and the exhaustive enumeration of counterexample regions while significantly outperforming State-of-the-Art tools in closed-loop NNV.
