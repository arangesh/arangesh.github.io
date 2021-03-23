---
title: "LaneAF: Robust Multi-Lane Detection with Affinity Fields"
collection: publications
permalink: /publication/paper-11
excerpt: ''
date: 2021-03-21
venue: 'arXiv:2103.12040'
---
<p align="center">
  <img src="https://arangesh.github.io/images/paper-11-im.png?raw=true" alt="Photo" style="width: 650px;"/> 
</p>

This study presents an approach to lane detection involving the prediction of binary segmentation masks and per-pixel affinity fields. These affinity fields, along with the binary masks, can then be used to cluster lane pixels horizontally and vertically into corresponding lane instances in a post-processing step. This clustering is achieved through a simple row-by-row decoding process with little overhead; such an approach allows LaneAF to detect a variable number of lanes without assuming a fixed or maximum number of lanes. Moreover, this form of clustering is more interpretable in comparison to previous visual clustering approaches, and can be analyzed to identify and correct sources of error. Qualitative and quantitative results obtained on  popular lane detection datasets demonstrate the model's ability to detect and cluster lanes effectively and robustly. Our proposed approach performs on par with state-of-the-art approaches on the limited TuSimple benchmark, and sets a new state-of-the-art on the challenging CULane dataset.

[PDF link](http://cvrr.ucsd.edu/publications/2021/LaneAF.pdf)

[Video results](https://youtube.com/playlist?list=PLUebh5NWCQUZv8IXYOVNM5SuRYQzScW5P)

[Code & trained model weights](https://github.com/sel118/LaneAF)
