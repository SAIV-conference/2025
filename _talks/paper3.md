---
name: Concept-based Analysis of Neural Networks via Vision-Language Models
speakers:
  - Ravi Mangal
  - Nina Narodytska
  - Divya Gopinath
  - Boyue Caroline Hu
  - Anirban Roy
  - Susmit Jha
  - Corina Păsăreanu
categories:
  - Presentation
  - Paper
---

### Abstract

The analysis of vision-based deep neural networks (DNNs) is highly desirable but it is very challenging due to the difficulty of expressing formal specifications for vision tasks and the lack of efficient verification procedures. In this paper, we propose to leverage emerging multimodal, vision-language, foundation models (VLMs) as a lens through which we can reason about vision models. VLMs have been trained on a large body of images accompanied by their textual description, and are thus implicitly aware of high-level, human-understandable concepts describing the images. We describe a logical specification language Con_spec designed to facilitate writing specifications in terms of these concepts. To define and formally check Con_spec specifications, we build a map between the internal representations of a given vision model and a VLM,  leading to an efficient verification procedure of natural-language properties for vision models.
We demonstrate our techniques on a ResNet-based  classifier trained on the RIVAL-10 dataset using CLIP as the multimodal model.
