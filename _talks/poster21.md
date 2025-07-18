---
name: "Qualitative and quantitative verification of DNN-CPS models"
speakers: 
  - Letian Fang
  - Jing Liu
  - Jiang Xiong
  - Rongbin Hou  
categories:
  - Posters
  - Poster
---

### Abstract

In safety-critical cyber-physical systems, using deep neural networks (DNNs) in deep reinforcement learning to assist control deci-
sions is becoming a hot topic, and formal verification of DNNs in CPS is crucial. In addition, some existing forms of modeling languages can model DNN-CPS, such as LUSTRE, MARTE, and AADL. However, they are synchronous languages based on data flow models and lack the ability to represent system control flow. Based on the data flow and control flow models of DNN-CPS, we propose a new synchronous modeling language SynLong. SynLong uses state machines to represent the control flow of the system. SynLong can formalize the transitions between different states between determinism and non-determinism. In addition, SynLong uses expressions and clock operators to capture various uncertainties and probabilities in the execution process, such as communication delays and computation time changes. For the randomness and adversarial behavior of DNN-CPS systems, traditional qualitative verification (such as reachability analysis) is difficult to fully cover the safety boundaries in dynamic environments.


