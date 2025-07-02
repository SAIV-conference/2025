---
name: "Bridging Neural ODE and ResNet: A Formal Error Bound for Safety Verification"
speakers:
  - Abdelrahman Sayed Sayed
  - Pierre-Jean Meyer
  - Mohamed Ghazel 
categories:
  - Presentation
  - Paper
  - "Chair: Mirco Giacobbe"
---

### Abstract

A neural ordinary differential equation (neural ODE) is a machine learning model that is commonly described as a continuous-depth generalization of a residual network (ResNet) with a single residual block, or conversely, the ResNet can be seen as the Euler discretization of the neural ODE. These two models are therefore strongly related in a way that the behaviors of either model are considered to be an approximation of the behaviors of the other. In this work, we establish a more formal relationship between these two models by bounding the approximation error between two such related models. The obtained error bound then allows us to use one of the models as a verification proxy for the other, without running the verification tools twice: if the reachable output set expanded by the error bound satisfies a safety property on one of the models, this safety property is then guaranteed to be also satisfied on the other model. This feature is fully reversible, and the initial safety verification can be run indifferently on either of the two models. This novel approach is illustrated on a numerical example of a fixed-point attractor system modeled as a neural ODE.
