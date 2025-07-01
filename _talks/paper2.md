---
name: "Neural Network Verification for Gliding Drone Control: A Case Study"
speakers:
  - Colin Kessler
  - Ekaterina Komendantskaya
  - Marco Casadio
  - Ignazio Maria Viola
  - Albaraa Ammar Othman
  - Alistair Malhotra
  - Robbie McPherson 
categories:
  - Presentation
  - Paper
  - "Chair: Mirco Giacobbe"
links:
  - name: Paper
    file: paper2.pdf
---

### Abstract

As machine learning is increasingly deployed in autonomous systems, verification of neural network controllers is becoming an active research domain. Existing tools and annual verification competitions suggest that soon this technology will become effective for real-world applications. Our application comes from the emerging field of microflyers that are passively transported by the wind, which may have various uses in weather or pollution monitoring. Specifically, we investigate centimetre-scale bio-inspired gliding drones that resemble Alsomitra macrocarpa diaspores. In this paper, we propose a new case study on verifying Alsomitra-inspired drones with neural network controllers, with the aim of adhering closely to a target trajectory. We show that our system differs substantially from existing VNN and ARCH competition benchmarks, and show that a combination of tools holds promise for verifying such systems in the future, if certain shortcomings can be overcome. We propose a novel method for robust training of regression networks, and investigate formalisations of this case study in Vehicle and CORA. Our verification results suggest that the investigated training methods do improve performance and robustness of neural network controllers in this application, but are limited in scope and usefulness. This is due to systematic limitations of both Vehicle and CORA, and the complexity of our system reducing the scale of reachability, which we investigate in detail. If these limitations can be overcome, it will enable engineers to develop safe and robust technologies that improve people’s lives and reduce our impact on the environment.
