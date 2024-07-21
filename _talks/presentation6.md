---
name: Shield Synthesis Modulo Theories
speakers:
  - Andoni Rodriguez
  - Guy Amir
  - Davide Corsi
  - César Sánchez
  - Guy Katz
categories:
  - Presentation
  - "Chair: Yuval Shapira"
---

### Abstract

In recent years, MachineLearning (ML) models have achieved remarkable success in various domains. However, these models also tend to demonstrate unsafe behaviours, precluding their deployment in safety- critical systems. To cope with this issue, ample research focuses on developing methods that guarantee the safe behaviour of a given ML model. A prominent example is shielding which incorporates an external component (a “shield”) that blocks unwanted behaviour. Despite significant progress, shielding suffer from a main setback: it is currently only available for properties encoded in propositional logics (like LTL) and are unsuitable for richer logics, which limits its applicability. In this work, we address this gap, by extending shielding to LTL modulo theories, for which we leverage recently-developed techniques from reactive synthesis modulo theories to develop a novel approach for generating shields conforming to complex safety specifications. We extensively evaluate our shields and show that they can manage rich data with temporal dynamics. To the best of our knowledge, this is the first approach for synthesizing shields suitable for such expressive logics.
