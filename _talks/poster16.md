---
name: "Stream-Based Monitoring of Algorithmic Fairness"
speakers: 
  - Frederik Scheerer
  - Jan Baumeister
  - Julian Siber
  - Bernd Finkbeiner 
categories:
  - Posters
  - Poster
---

### Abstract

Automatic decision and prediction systems are increasingly deployed in applications where they significantly impact the livelihood of people, such as for predicting the creditworthiness of loan applicants or the recidivism risk of defendants. These applications have given rise to a new class of algorithmic-fairness specifications that require the systems to decide and predict without bias against social groups. A successful technique for ensuring that systems satisfy specifications at runtime is stream-based monitoring. These monitors can handle real-time events over rich data types, which is essential to verify cyber-physical systems, such as autonomous drones. In our recent work, we show that the same techniques are also an excellent fit for the verification of algorithmic fairness properties at runtime. Concretely, we propose a principled way to formalize algorithmic fairness over temporal data streams in the specification language RTLola and demonstrate the efficacy of this approach on a number of benchmarks. Besides synthetic scenarios that particularly highlight its efficiency on streams with a scaling amount of data, we notably evaluate a monitor on real-world data from the recidivism prediction tool COMPAS - a system that exemplifies the societal impact and ethical challenges of AI-driven decision making. In the following, we give a short summary of this work to be published at TACAS 2025.