---
name: "How to Verify Generalization Capability of a Neural Network with Formal Methods"
speakers:
  - Arthur Clavière
  - Dmitrii Kirov
  - Darren Cofer   
categories:
  - Presentation
  - Paper
  - "Chair: Taylor Johnson"

---

### Abstract

Generalization of a machine learning (ML) model is its capability to maintain desired performance on input data to which it was not exposed during training. A bound on the model generalization error can provide important evidence of the absence of unintended behavior of the model, which is the key requirement for safety-critical systems and software. Such bounds are typically estimated statistically and provide a level of confidence that the bound holds. In this paper, we show how ML model generalization capability and bound can be assessed using formal methods providing a rigorous mathematical guarantee. We focus on applications that use neural networks to approximate a function with a low-dimensional, well-defined and bounded input space. We propose an iterative procedure that starts with partitioning the neural network input space into regions using one or multiple resolutions. Within each region, we formalize a property that the error made by the neural network on any data point inside the region is below a given tolerance. Proving such property provides a formal generalization guarantee for a given region. We employ an abstract interpretation solver to verify these properties over the entire input space partition. We iteratively refine the regions in which the proof could not be achieved by sampling or generating new data, forming a new local partition with higher granularity. This refinement follows a heuristic that aims to minimize the amount of new data to be produced. We demonstrate our methodology by proving generalization capability of a neural network-based avionics function.