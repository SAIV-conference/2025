---
name: Verification of Neural Network Control Systems in Continuous Time
speakers:
  - Ali ArjomandBigdeli
  - Andrew Mata
  - Stanley Bak
categories:
  - Presentation
  - Paper
  - "Chair: Christopher Brix"
---

### Abstract

Neural network controllers are currently being proposed for use in many safety-critical tasks.
Most analysis methods for neural network control systems assume a fixed control period.
In control theory, higher frequency usually improves performance.
However, for current analysis methods, increasing the frequency complicates verification.
In the limit, when actuation is performed continuously, no existing neural network control systems verification methods are able to analyze the system.

In this work, we develop the first verification method for continuously-actuated neural network control systems.
We accomplish this by adding a level of abstraction to model the neural network controller.
The abstraction is a piecewise linear model with added noise to account for local linearization error.
The soundness of the abstraction can be checked using open-loop neural network verification tools, although we demonstrate bottlenecks in existing tools when handling the required specifications.
We demonstrate the approach's efficacy by applying it to a vision-based autonomous airplane taxiing system and compare with a fixed frequency analysis baseline.
