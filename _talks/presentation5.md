---
name: Scalable relational verification and training for deep neural networks
speakers:
  - Debangshu Banerjee
  - Changming Xu
  - Gagandeep Singh
categories:
  - Presentation
  - "Chair: Yuval Shapira"
---

### Abstract

We consider verifying relational properties defined over deep neural networks (DNNs) such as robustness against universal adversarial perturbations (UAP), monotonicity, certified worst-case hamming distance for binary string classifications, etc. Precise verification of these properties necessitates reasoning about multiple executions of the same DNN. However, most existing works in DNN verification only handle properties defined over single executions and as a result, are imprecise for relational properties. Though few recent works for relational DNN verification, capture linear dependencies between the inputs of multiple executions, they do not leverage dependencies between the outputs of hidden layers producing imprecise results. We develop a scalable relational verification framework that utilizes cross-execution dependencies at all layers of the DNN gaining substantial precision over SOTA baselines on a wide range of datasets, networks, and relational properties. Orthogonally, we propose certifiable training methods for relational properties to learn network parameters for facilitating relational verification on the trained network.
