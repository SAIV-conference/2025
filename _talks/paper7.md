---
name: "Clover: Closed-Loop Verifiable Code Generation"
speakers:
  - Chuyue Sun
  - Ying Sheng
  - Oded Padon
  - Clark Barrett
categories:
  - Presentation
  - Paper
---

### Abstract

The use of large language models for code generation is a rapidly growing trend in software development.
However, without effective methods for ensuring the correctness of generated code, this trend could lead to undesirable outcomes. In this paper, we introduce a new approach for addressing this challenge: the Clover paradigm, short for **Clo**sed-Loop **Ver**ifiable Code Generation, which uses consistency checking to provide a strong filter for incorrect code.
Clover performs consistency checks among code, docstrings, and formal annotations. The checker is implemented using a novel integration of formal verification tools and large language models.
We provide a theoretical analysis to support our thesis that Clover should be effective at consistency checking.
We also empirically investigate its performance on a hand-designed dataset (CloverBench) featuring annotated Dafny programs at a textbook level of difficulty. Experimental results show that for this dataset: (i) LLMs are reasonably successful at automatically generating formal specifications; and (ii) our consistency checker achieves a promising acceptance rate (up to 87%) for correct instances while maintaining zero tolerance for adversarial incorrect ones (no false positives).
Clover also discovered 6 incorrect programs in the existing human-written dataset MBPP-DFY-50.
