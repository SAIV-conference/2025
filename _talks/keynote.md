---
name: Verified Autonomy with Neural Lyapunov Barrier Certificates
speakers:
  - Clark Barrett
categories:
  - Invited Talk
  - Keynote
---
Deep reinforcement learning (DRL) is a powerful machine learning paradigm for generating agents that control autonomous systems. However, the “black box” nature of DRL agents limits their deployment in real-world safety-critical applications.  A promising approach for providing strong guarantees on an agent’s behavior is to use Neural Lyapunov Barrier (NLB) certificates, which are learned functions over the system whose properties indirectly imply that an agent behaves as desired.  However, NLB-based certificates are typically difficult to learn and even more difficult to verify, especially for complex systems.  I will present a novel method for training and verifying NLB-based certificates for discrete-time systems including a technique for certificate composition, which simplifies the verification of highly-complex systems by strategically designing a sequence of certificates. When jointly verified with neural network verification engines, these certificates provide a formal guarantee that a DRL agent both achieves its goals and avoids unsafe behavior.  I will also present a case study showing how these techniques can be used to provide safety and liveness guarantees for a DRL-controlled spacecraft.
