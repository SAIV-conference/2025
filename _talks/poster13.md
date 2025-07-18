---
name: "Automated VNN Solver Configuration Selection via Deep Reinforcement Learning"
speakers: 
  - Salil Kamath
  - Matthew Davis
  - Jonathan Andreasen
  - Yatis Dodia
  - Vijay Ganesh  
categories:
  - Posters
  - Poster
---

### Abstract

We present REGENT, an automated selection tool for verification of neural network (VNN) solver configurations trained via a novel deep reinforcement learning (RL) approach using solver feedback. Our automated selection tool is a deep neural network (DNN) that takes as input a feature set of a VNN instance and outputs a distribution over solver configurations. We train the DNN as follows: for each instance, we query the DNN for a configuration, run the solver using that configuration, and compute a reward based on the runtime. During inference, we query the DNN and run the solver using the configuration with the highest probability.

We perform extensive empirical evaluations that show that the configurations selected by REGENT significantly outperform default configurations of the currently best performing VNN solver ($\alpha,\beta$-CROWN) on a large set of test instances. In particular, we are close to the virtual best solver, as measured by PAR-2 scores. We also note that our deep RL training approach is significantly more efficient in terms of training time and the ability to handle large configuration spaces than previous supervised machine learning algorithm selection tools such as MachSMT and Goose.