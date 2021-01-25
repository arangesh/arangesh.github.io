---
title: "TrackMPNN: A Message Passing Graph Neural Architecture for Multi-Object Tracking"
collection: publications
permalink: /publication/paper-10
excerpt: ''
date: 2021-01-11
venue: 'arXiv:2101.04206'
---
<p align="center">
  <img src="https://arangesh.github.io/images/paper-10-im.png?raw=true" alt="Photo" style="width: 650px;"/> 
</p>

This study follows many previous approaches to multi-object tracking (MOT) that model the problem using graph-based data structures, and adapts this formulation to make it amenable to modern neural networks. Our main contributions in this work are the creation of a framework based on dynamic undirected graphs that represent the data association problem over multiple timesteps, and a message passing graph neural network (GNN) that operates on these graphs to produce the desired likelihood for every association therein. We further provide solutions and propositions for the computational problems that need to be addressed to create a memory-efficient, real-time, online algorithm that can reason over multiple timesteps, correct previous mistakes, update beliefs, possess long-term memory, and handle missed/false detections. In addition to this, our framework provides flexibility in the choice of temporal window sizes to operate on and the losses used for training. In essence, this study provides a framework for any kind of graph based neural network to be trained using conventional techniques from supervised learning, and then use these trained models to infer on new sequences in an online, real-time, computationally tractable manner. To demonstrate the efficacy and robustness of our approach, we only use the 2D box location and object category to construct the descriptor for each object instance. Despite this, our model performs on par with state-of-the-art approaches that make use of multiple hand-crafted and/or learned features. Experiments, qualitative examples and competitive results on popular MOT benchmarks for autonomous driving demonstrate the promise and uniqueness of the proposed approach.


[PDF link](http://cvrr.ucsd.edu/publications/2021/TrackMPNN.pdf)

[Code & trained model weights](https://github.com/arangesh/TrackMPNN)
