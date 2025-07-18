---
name: "Neural Approximation of Vision-Controlled Systems for Reachability Analysis"
speakers: 
  - Yuang Geng
  - Sukanth Sundaran
  - Chao Huang
  - Steven Drager
  - Ivan Ruchkin  
categories:
  - Posters
  - Poster
---

### Abstract

Autonomous cyber-physical systems increasingly use end-to-end vision-based controllers, with deep neural networks processing rich sensory inputs to make real-world decisions. However, existing safety verification tools do not scale to high-dimensional controllers whose inputs are thousands of dimensions, such as pixel-based images. This article addresses this limitation by approximating high-dimensional vision-based neural controllers with multiple low-dimensional neural controllers by leveraging verification-aware knowledge distillation. We then inflate the low-dimensional reachability and statistical approximation analyses, providing the high-confidence reachability guarantees for the original high-dimensional controller. Three reachable tube inflation techniques are investigated based on the state and action discrepancies between trajectories and individual time steps. All of them show promising performance in three OpenAI gym benchmarks.