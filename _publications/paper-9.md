---
title: "Driver Gaze Estimation in the Real World: Overcoming the Eyeglass Challenge"
collection: publications
permalink: /publication/paper-9
excerpt: ''
date: 2020-02-05
venue: 'IEEE Intelligent Vehicles Symposium'
---
<p align="center">
  <img src="https://arangesh.github.io/images/paper-9-im.png?raw=true" alt="Photo" style="width: 650px;"/> 
</p>

A driver's gaze is critical for determining the driver's attention level, state, situational awareness, and readiness to take over control from partially and fully automated vehicles. Tracking both the head and eyes (pupils) can provide reliable estimation of a driver's gaze using face images under ideal conditions. However, the vehicular environment introduces a variety of challenges that are usually unaccounted for - harsh illumination, nighttime conditions, and reflective/dark eyeglasses. Unfortunately, relying on head pose alone under such conditions can prove to be unreliable owing to significant eye movements. In this study, we offer solutions to address these problems encountered in the real world. To solve issues with lighting, we demonstrate that using an infrared camera with suitable equalization and normalization usually suffices. To handle eyeglasses and their corresponding artifacts, we adopt the idea of image-to-image translation using generative adversarial networks (GANs) to pre-process images prior to gaze estimation. To this end, we propose the *Gaze Preserving CycleGAN (GPCycleGAN)*. As the name suggests, this network preserves the driver's gaze while removing potential eyeglasses from infrared face images. GPCycleGAN is based on the well-known CycleGAN approach, with the addition of a gaze classifier and a gaze consistency loss for additional supervision. Our approach exhibits improved performance and robustness on challenging real-world data spanning 13 subjects and a variety of driving conditions.

[PDF link](http://cvrr.ucsd.edu/publications/2020/GPCycleGAN.pdf)

[Code](https://github.com/arangesh/GPCycleGAN)
