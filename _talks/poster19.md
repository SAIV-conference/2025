---
name: "On the efficiency of training robust decision trees"
speakers: 
  - Benedict Gerlach
  - Marie Anastacio
  - Holger Hoos 
categories:
  - Posters
  - Poster
---

### Abstract

As machine learning gets adopted into the industry quickly,
trustworthiness is increasingly in focus. Yet, efficiency and sustainability
of robust training pipelines still have to be established. In this work, we
consider a simple pipeline for training adversarially robust decision trees
and investigate the efficiency of each step. Our pipeline consists of three
stages. Firstly, we choose the perturbation size automatically for each
dataset. For that, we introduce a simple algorithm, instead of relying on
intuition or prior work. Moreover, we show that the perturbation size can
be estimated from smaller models than the one intended for full training,
and thus significant gains in efficiency can be achieved. Secondly, we
train state-of-the-art adversarial training methods and evaluate them
regarding both their training time and adversarial accuracy. Thirdly, we
certify the robustness of each of the models thus obtained and investigate
the time required for this. We find that verification time, which is critical
to the efficiency of the full pipeline, is not correlated with training time.


