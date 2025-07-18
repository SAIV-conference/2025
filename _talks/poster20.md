---
name: "Glitches in Tree Ensemble model"
speakers: 
  - Namrita Varshney
  - Ashutosh Gupta
  - Shankaranarayanan Krishna
  - Kaushik Mallik
  - Satyankar Chandra 
categories:
  - Posters
  - Poster
---

### Abstract

Many critical decision-making tasks are now delegated to machine-learned models, and it is imperative that their decisions are trustworthy and reliable, and their outputs are consistent across similar inputs. We identify a new source of unreliable behaviors—called glitches—which may significantly impair the reliability of AI models having steep decision boundaries. Roughly speaking, glitches are small neighbourhoods in the input space where the model’s output abruptly fluctuates with respect to small changes in the input. We provide a formal definition of glitches and use well-known models and data sets from the literature to demonstrate that they have widespread existence and usually indicate potential model inconsistencies in the neighbourhood where they are found. We argue that glitches exist near decision boundaries—typically the ones that are poorly trained due to limited training data. We proceed to the algorithmic search for glitches in the widely used gradient boosted decision tree(GBDT) models. We prove that the problem of detecting glitches is NP-complete even for tree ensembles with constant depths. Our algorithm, for GBDT models, uses an MILP encoding of the problem to detect glitches. Our experiments demonstrate the effectiveness and computational feasibility of our algorithm on a suite of GBDT benchmarks from the literature.


