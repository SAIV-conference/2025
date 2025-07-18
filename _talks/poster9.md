---
name: "Control Barrier Functions with Lookahead"
speakers: 
  - Thomas A Henzinger
  - Kaushik Mallik
  - Emily Yu
  - Đorđe Žikelić 
categories:
  - Posters
  - Poster
---

### Abstract

Modern embedded systems need to meet stringent safety requirements, often in the presence of dynamic environments. Control barrier functions (CBFs) have emerged as a tool for proving the safety of controllers for dynamical systems. Traditionally, CBFs are generated statically before system deployment, with a given model of the set of all possible environment behaviors, under the assumption that the environment may behave adversarially during deployment. However, the reliance on environment models makes the approach sensitive towards modeling errors, while the adversarial assumption on the environment causes excessively conservative results in many situations. In practice, embedded systems have access to real-time information of observed environment behaviors, which can be used to predict their future behaviors with reasonable accuracies. In this paper, we present CBFs with lookahead (CBFLs), which extend traditional CBFs with the ability to adapt to bounded-horizon environment lookaheads available dynamically at runtime. When the lookahead horizon is zero, CBFLs coincide with CBFs (without lookahead). When the lookahead horizon is nonzero, CBFLs offer greater resilience to environment model violations and offer increased permissiveness in enabling safe behaviors. We propose a learning framework to automatically synthesize neural CBFLs and the associated neural safety controllers from sampled system trajectories. We demonstrate that CBFLs can significantly outperform traditional CBFs in ensuring safety in the automotive domain in the presence of other (uncontrollable) agents in the environment.


