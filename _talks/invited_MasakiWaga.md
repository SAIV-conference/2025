---
name: "Soft Pattern Matching: Toward Runtime Verification of NLP Systems"
speakers:
  - Masaki Waga
categories:
  - Invited Talk
  - Table Host
  - "Chair: Anna Lukina"
---

### Abstract

When developing and maintaining complex ML-based systems, it is useful to analyze various related data, including the training data and execution logs. Pattern matching is one of the approaches to analyzing such data by identifying the part of the data that matches the given pattern of interest. When applying pattern matching to NLP systems, such as LLM-based agent systems, it is useful to use patterns that capture the semantics of natural language texts. In our latest work, we proposed soft pattern matching, where the comparison in the pattern is relaxed by a comparison based on the word embedding and cosine similarity. We also presented an algorithm based on inverted indices. Our tool, SoftMatcha, for soft pattern matching is efficient enough to handle billion-scale inputs. I will discuss open problems toward runtime verification of these systems.
