---
name: "Analyzing Adversarial Inputs in Deep Reinforcement Learning"
speakers: Davide Corsi, Guy Amir, Guy Katz, Alessandro Farinelli
categories:
  - Posters
  - Poster
---

### Abstract

In recent years, Deep Reinforcement Learning (DRL) has become a popular paradigm in machine learning due to its successful applications to real-world and complex systems. However, even the state-of-the-art DRL models have been shown to suffer from reliability concerns --- for example, their susceptibility to adversarial inputs, i.e., small and abundant input perturbations that can fool the models into making unpredictable and potentially dangerous decisions. This drawback limits the deployment of DRL systems in safety-critical contexts, where even a small error cannot be tolerated. In this work, we present a comprehensive analysis of the characterization of adversarial inputs, through the lens of formal verification. Specifically, we introduce a novel metric, the Adversarial Rate, to classify models based on their susceptibility to such perturbations, and present a set of tools and algorithms for its computation. Our analysis empirically demonstrates how adversarial inputs can affect the safety of a given DRL system with respect to such perturbations. Moreover, we analyze the behavior of these configurations to suggest several useful practices and guidelines to help mitigate the vulnerability of trained DRL networks.