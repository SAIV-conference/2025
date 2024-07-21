---
name: Provable Repair of Vision Transformers
speakers:
  - Stephanie Nawas
  - Zhe Tao
  - Aditya Thakur
categories:
  - Presentation
  - Paper
  - "Chair: Yuval Shapira"
---

### Abstract

Vision Transformers have emerged as state-of-the-art image recognition tools, but may still exhibit incorrect behavior.
Incorrect image recognition can have disastrous consequences in safety-critical real-world applications such as self-driving
automobiles.  In this paper, we present Provable Repair of Vision Transformers (PRoViT), a provable repair approach that
guarantees the correct classification of images in a repair set for a given Vision Transformer without modifying its
architecture. PRoViT avoids negatively affecting correctly classified images (drawdown) by minimizing the changes made to
the Vision Transformer's parameters and original output. We observe that for Vision Transformers, unlike for other
architectures such as ResNet or VGG, editing just the parameters in the last layer achieves correctness guarantees and
very low drawdown. We introduce a novel method for editing these last-layer parameters that enables PRoViT to efficiently
repair state-of-the-art Vision Transformers for thousands of images, far exceeding the capabilities of prior
provable repair approaches.
