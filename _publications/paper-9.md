---
title: "Gaze Preserving CycleGANs for Eyeglass Removal & Persistent Gaze Estimation"
collection: publications
permalink: /publication/paper-9
excerpt: ''
date: 2020-02-05
venue: 'arXiv:2002.02077'
---
<p align="center">
  <img src="https://arangesh.github.io/images/paper-9-im.png?raw=true" alt="Photo" style="width: 650px;"/> 
</p>

A driver's gaze is critical for determining the driver's attention level, state, situational awareness, and readiness to take over control from partially and highly automated vehicles. Does so is imperative until level 5 (complete) automation is attained. Estimating the gaze direction and/or head pose is the most obvious way to gauge a driver's state under ideal conditions - preferably using non-intrusive imaging sensors. Unfortunately, ideal conditions are hard to sustain in the real world. In particular, the vehicular environment introduces a variety of challenges that are usually unaccounted for - harsh illumination, nighttime conditions, and reflective/dark eyeglasses. Relying on head pose alone under such conditions can prove to be unreliable owing to significant eye movements. In this study, we offer solutions to address these problems encountered in the real world. To solve issues with lighting, we demonstrate that using an infrared camera with suitable equalization and normalization usually suffices. To handle eyeglasses and their corresponding artifacts, we adopt the idea of image-to-image translation using generative adversarial networks (GANs) to pre-process images prior to gaze estimation. To this end, we propose the Gaze Preserving CycleGAN (GPCycleGAN). The model is trained to preserve the driver's gaze while removing potential eyeglasses from face images. GPCycleGAN is based on the well-known CycleGAN approach, with the addition of a gaze classifier and a gaze consistency loss for additional supervision. Our approach exhibits improved performance, interpretability, robustness and superior qualitative results on challenging real-world data spanning 13 subjects and a variety of driving conditions.

[PDF link](http://cvrr.ucsd.edu/publications/2020/GPCycleGAN-extended.pdf)

[Video results](https://youtu.be/3_8U2TrrZVs)

[Code, dataset & trained model weights](https://github.com/arangesh/GPCycleGAN)
