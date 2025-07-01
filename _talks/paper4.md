---
name: "ClassInvGen: Class Invariant Synthesis using Large Language Models"
speakers:
  - Chuyue Sun
  - Saikat Chakraborty
  - Jubi Taneja
  - Viraj Agashe
  - Xiaokang Qiu
  - David L. Dill
  - Clark Barrett
  - Shuvendu K Lahiri 
categories:
  - Presentation
  - Paper
  - "Chair: Mirco Giacobbe"
links:
  - name: Paper
    file: paper4.pdf
---

### Abstract

Formal program specifications in the form of preconditions, postconditions, and class invariants offer several benefits for program construction and maintenance. These specifications aid program understanding due to their clear, unambiguous semantics and can be enforced dynamically or statically, provided the language supports formal verification. However, synthesizing high-quality specifications within a programming language faces challenges, including limitations in expressivity and the need to articulate specifications declaratively.

Previous work has shown the promise of large language models (LLMs) for generating high-quality method preconditions and postconditions for languages such as Python and Java. However, these methods have not addressed class invariants.

In this paper, we introduce ClassInvGen, a novel approach for simultaneously generating executable class invariants and corresponding test inputs for C++. Our method leverages LLMs' proficiency in synthesizing pure functions, significantly improving the quality of generated class invariants compared to both pure LLM-based specification generation and traditional data-driven invariant inference methods like Daikon.

We contribute:

A benchmark suite featuring standard C++ data structures along with an evaluation harness designed to measure the correctness and completeness of generated specifications through testing and mutation analysis.

A demonstration of ClassInvGen’s practical applicability via a case study on multiple classes from a widely used, high-integrity C++ codebase.

Our results highlight the effectiveness of ClassInvGen in producing robust, high-quality class invariants suitable for mainstream programming languages and practical software development scenarios.

