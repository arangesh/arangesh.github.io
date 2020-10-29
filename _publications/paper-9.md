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

A driver's gaze is critical for determining their attention, state, situational awareness, and readiness to take over control from partially automated vehicles. Estimating the gaze direction is the most obvious way to gauge a driver's state under ideal conditions when limited to using non-intrusive imaging sensors. Unfortunately, the vehicular environment introduces a variety of challenges that are usually unaccounted for - harsh illumination, nighttime conditions, and reflective eyeglasses. Relying on head pose alone under such conditions can prove to be unreliable and erroneous. In this study, we offer solutions to address these problems encountered in the real world. To solve issues with lighting, we demonstrate that using an infrared camera with suitable equalization and normalization suffices. To handle eyeglasses and their corresponding artifacts, we adopt image-to-image translation using generative adversarial networks to pre-process images prior to gaze estimation. Our proposed Gaze Preserving CycleGAN (GPCycleGAN) is trained to preserve the driver's gaze while removing potential eyeglasses from face images. GPCycleGAN is based on the well-known CycleGAN approach - with the addition of a gaze classifier and a gaze consistency loss for additional supervision. Our approach exhibits improved performance, interpretability, robustness and superior qualitative results on challenging real-world datasets.

[PDF link](http://cvrr.ucsd.edu/publications/2020/GPCycleGAN-extended.pdf)

[Video results](https://youtu.be/3_8U2TrrZVs)

[Code, dataset & trained model weights](https://github.com/arangesh/GPCycleGAN)
