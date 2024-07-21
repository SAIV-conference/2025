---
name: A Preliminary Study to Examining Per-Class Performance Bias via Robustness Distributions
speakers:
  - Annelot Bosman
  - Anna Münz
  - Holger Hoos
  - Jan van Rijn
categories:
  - Presentation
  - Paper
  - "Chair: Andoni Rodriguez"
---

### Abstract

As neural networks are increasingly used in sensitive real-world applications, mitigating bias of classifiers is of crucial importance.
One often-used approach to controlling quality in classification tasks is to ensure that predictive performance is balanced between different classes;
however, it has been shown in previous work that even if class performance is balanced, instances of some classes are easier to perturb in such a way that they are misclassified, which indicates that per-class performance bias exists.

In this preliminary study, we found that even when class performance is balanced, class robustness can vary strongly when assessing the robustness of a given neural network classifier in a more nuanced fashion.
For this purpose, we use robustness distributions, i.e., empirical probability distributions of some robustness metric, such as the critical epsilon value,  over a set of instances.
We observed that the robustness of the same class over the same data can significantly differ from each other for different neural networks;
this means that even when a neural network appears to be unbiased, it might be easier to perturb instances of a given class so that they are misclassified.

Furthermore, we explored the robustness distributions when we have a predefined target class, i.e., a specific class into which an instance is misclassified after perturbation.
Our empirical results indicate that in most cases, there are significant differences in robustness distributions for different classes.

While our empirical results reported here are for MNIST classifiers,
we are currently performing experiments using the German Traffic Sign Recognition Benchmark.
Furthermore, we are running experiments with retrained networks for fairness, to see whether this has a significant effect on the per-class robustness distributions.
Lastly, we aim to create a robust class fairness metric based on our findings.
