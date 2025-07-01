---
name: "On the Complexity of Formal Reasoning in State Space Models"
speakers:
  - Eric Alsmann
  - Martin Lange    
categories:
  - Presentation
  - Paper
  - "Chair: Anna Lukina"
links:
  - name: Paper
    file: paper13.pdf
---

### Abstract

We study the computational complexity of the satisfiability problem for state space models (ssmSAT), a recurrent architecture that has recently emerged as a promising alternative to the widely used transformer architecture in language modelling. We show that ssmSAT is undecidable in the general case. However, under certain practically motivated restrictions, the problem becomes decidable, and we establish complexity bounds for these cases. When the context length is bounded, ssmSAT is NP-complete. When the model is quantised, i.e. restricted to fixed-width arithmetic, satisfiability remains decidable. Nevertheless, the problem remains computationally hard: depending on the encoding, we identify instances where ssmSAT, when restricted to fixed-width arithmetic, is PSPACE-complete or lies between PSPACE and EXPSPACE, depending on the encoding of the bit-width. Given these results, we discuss possible implications for the verification of state-space models used in language modelling.