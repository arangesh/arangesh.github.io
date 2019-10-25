---
title: "Forced Spatial Attention for Driver Foot Activity Classification"
collection: publications
permalink: /publication/paper-8
excerpt: ''
date: 2019-10-23
venue: 'ICCV Workshop on Assistive Computer Vision and Robotics'
---
<p align="center">
  <img src="https://arangesh.github.io/images/paper-8-im.png?raw=true" alt="Photo" style="width: 700px;"/> 
</p>

This paper provides a simple solution for reliably solving image classification tasks tied to spatial locations of salient objects in the scene. Unlike conventional image classification approaches that are designed to be invariant to translations of objects in the scene, we focus on tasks where the output classes vary with respect to where an object of interest is situated within an image. To handle this variant of the image classification task, we propose augmenting the standard cross-entropy (classification) loss with a domain dependent Forced Spatial Attention (FSA) loss, which in essence compels the network to attend to specific regions in the image associated with the desired output class. To demonstrate the utility of this loss function, we consider the task of driver foot activity classification - where each activity is strongly correlated with where the driver’s foot is in the scene. Training with our proposed loss function results in significantly improved accuracies, better generalization, and robustness against noise, while obviating the need for very large datasets.

[PDF link](http://cvrr.ucsd.edu/publications/2019/FSAFAC.pdf)

[Video results](https://www.youtube.com/watch?v=0irynrv4_7U&list=PLUebh5NWCQUZ_JgaIonLNZF3zh1wDse-1&index=2&t=0s)

[Code](https://github.com/arangesh/Forced-Spatial-Attention)

