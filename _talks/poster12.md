---
name: "Monitoring Robustness and Individual Fairness"
speakers: 
  - Konstantin Kueffner
  - Kaushik Mallik
  - Ashutosh Gupta
  - Thomas A Henzinger
  - David Pape 
categories:
  - Posters
  - Poster
---

### Abstract

In automated decision-making, it is desirable that outputs of decision-makers be robust to slight perturbations in their inputs, a property that may be called input-output robustness. Input-output robustness appears in various different forms in the literature, such as robustness of AI models to adversarial or semantic perturbations and individual fairness of AI models that make decisions about humans. We propose runtime monitoring of input-output robustness of deployed, black-box AI models, where the goal is to design monitors that would observe one long execution sequence of the model, and would raise an alarm whenever it is detected that two similar inputs from the past led to dissimilar outputs. This way, monitoring will complement existing offline ``robustification'' approaches to increase the trustworthiness of AI decision-makers. We show that the monitoring problem can be cast as the fixed-radius nearest neighbor (FRNN) search problem, which, despite being well-studied, lacks suitable online solutions. We present our tool CLEMONT (CLassifiEr MONitoring Tool), which offers a number of lightweight monitors, some of which use upgraded online variants of existing FRNN algorithms, and one uses a novel algorithm based on binary decision diagrams---a data-structure commonly used in software and hardware verification. We have also developed an efficient parallelization technique that can substantially cut down the computation time of monitors for which the distance between input-output pairs is measured using the infinity norm. Using standard benchmarks from the literature of adversarial and semantic robustness and individual fairness, we perform a comparative study of different monitors in CLEMONT, and demonstrate their effectiveness in correctly detecting robustness violations at runtime.