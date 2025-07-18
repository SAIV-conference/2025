---
name: "False Positives in Robustness Checking of Neural Networks - An Experimental Study"
speakers: 
  - Mohammad Afzal
  - S Akshay
  - Ashutosh Gupta
  - Venkatesh R  
categories:
  - Posters
  - Poster
---

### Abstract

Neural networks are increasingly used in safety-critical systems, where trust is important. To ensure their trustworthy deployment, we need to verify that they are robust against minor perturbations. In recent times, a promising line of work has focused on developing algorithms and tools to verify local robustness. But in doing so, the counterexamples found by state-of-the-art neural network verifiers may not be really meaningful. In fact, a counterexample that is considered a robustness violation reported by a neural network may not be a violation in the view of domain expert.  We refer to such cases as false positives.  In this work, we propose a new approach to evaluate the robustness of neural networks by considering the view of domain expert. We start by recalling the notions of false positives(FP) and true positives (TP) to the context of robustness verification of neural networks. Our goal is to evaluate the presence or absence of such false positives in state of the art verifiers. However, doing this manually indeed may not scale. Thus, in our experiments, we evaluate the local robustness property based on the notions of FP and TP, while approximating the domain expert using an ensemble of state-of-the-art neural network classifiers.


