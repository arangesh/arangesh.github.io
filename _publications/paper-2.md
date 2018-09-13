---
title: "Driver Gaze Zone Estimation using Convolutional Neural Networks: A General Framework and Ablative Analysis"
collection: publications
permalink: /publication/paper-2
excerpt: ''
date: 2018-01-01
venue: 'IEEE Transactions on Intelligent Vehicles'
---
<p align="center">
  <img src="https://arangesh.github.io/images/paper-2-im.png?raw=true" alt="Photo" style="width: 900px;"/> 
</p>

Driver gaze has been shown to be an excellent surrogate for driver attention in intelligent vehicles. With the recent surge of highly autonomous vehicles, driver gaze can be useful for determining the handoff time to a human driver. While there has been significant improvement in personalized driver gaze zone estimation systems, a generalized system which is invariant to different subjects, perspectives and scales is still lacking. We take a step towards this generalized system using Convolutional Neural Networks (CNNs). We finetune 4 popular CNN architectures for this task, and provide extensive comparisons of their outputs. We additionally experiment with different input image patches, and also examine how image size affects performance. For training and testing the networks, we collect a large naturalistic driving dataset comprising of 11 long drives, driven by 10 subjects in two different cars. Our best performing model achieves an accuracy of 95.18% during crosssubject testing, outperforming current state of the art techniques for this task. Finally, we evaluate our best performing model on the publicly available Columbia Gaze Dataset comprising of images from 56 subjects with varying head pose and gaze directions. Without any training, our model successfully encodes the different gaze directions on this diverse dataset, demonstrating good generalization capabilities.

[PDF link](http://cvrr.ucsd.edu/publications/2018/sourabh_gaze_zone.pdf)

[Video results](https://www.youtube.com/watch?v=ZjzoDL_2CbU&list=PLUebh5NWCQUaPmdZIGE508Bhh6AjwID8R&index=1&t=0s)
