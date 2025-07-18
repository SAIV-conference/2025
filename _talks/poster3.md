---
name: "Revisiting Differential Verification: Equivalence Verification with Confidence"
speakers: Samuel Teuber, Philipp Daniel Kern, Marvin Janzen, Bernhard Beckert  
categories:
  - Posters
  - Poster
---

### Abstract

When validated neural networks (NNs) are pruned (and retrained) before deployment, it is desirable to prove that the new NN behaves equivalently to the (original) reference NN. To this end, our paper revisits the idea of differential verification which performs reasoning on differences between NNs: On the one hand, our paper proposes a novel abstract domain for differential verification admitting more efficient reasoning about equivalence. On the other hand, we investigate empirically and theoretically which equivalence properties are (not) efficiently solved using differential reasoning. Based on the gained insights, and following a recent line of work on confidence-based verification, we propose a novel equivalence property that is amenable to Differential Verification while providing guarantees for large parts of the input space instead of small-scale guarantees constructed w.r.t. predetermined input points. To this end, we propose an improved approach for (approximately) constraining an NN's softmax confidence. We implement our approach in a new tool called VeryDiff and perform an extensive evaluation on numerous old and new benchmark families, including new pruned NNs for particle jet classification in the context of CERN's LHC where we observe median speedups >300x over the State-of-the-Art verifier alpha,beta-CROWN.