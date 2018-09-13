---
title: "No Blind Spots: Full-Surround Multi-Object Tracking for Autonomous Vehicles using Cameras & LiDARs"
collection: publications
permalink: /publication/paper-4
excerpt: ''
date: 2018-01-01
venue: 'IEEE Transactions on Intelligent Vehicles'
---
<p align="center">
  <img src="https://arangesh.github.io/images/paper-4-im.png?raw=true" alt="Photo" style="width: 900px;"/> 
</p>

Online multi-object tracking (MOT) is extremely
important for high-level spatial reasoning and path planning
for autonomous and highly-automated vehicles. In this paper,
we present a modular framework for tracking multiple objects
(vehicles), capable of accepting object proposals from different
sensor modalities (vision and range) and a variable number
of sensors, to produce continuous object tracks. This work
is inspired by traditional tracking-by-detection approaches in
computer vision, with some key differences - First, we track
objects across multiple cameras and across different sensor
modalities. This is done by fusing object proposals across sensors
accurately and efficiently. Second, the objects of interest (targets)
are tracked directly in the real world. This is a departure from
traditional techniques where objects are simply tracked in the
image plane. Doing so allows the tracks to be readily used by an
autonomous agent for navigation and related tasks.
To verify the effectiveness of our approach, we test it on real
world highway data collected from a heavily sensorized testbed
capable of capturing full-surround information. We demonstrate
that our framework is well-suited to track objects through entire
maneuvers around the ego-vehicle, some of which take more than
a few minutes to complete. We also leverage the modularity of
our approach by comparing the effects of including/excluding
different sensors, changing the total number of sensors, and the
quality of object proposals on the final tracking result.

[PDF link](http://cvrr.ucsd.edu/publications/2018/M3OT.pdf)

[Video results](https://www.youtube.com/watch?v=UowMiGXoWbc&t=2s&index=1&list=PLUebh5NWCQUbP9LXdV8E_b-6y7C9hIEHT)
