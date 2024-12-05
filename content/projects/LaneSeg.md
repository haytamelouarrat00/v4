---
date: '01-12-2024'
title: 'Lane Segmentation '
github: 'https://github.com/haytamelouarrat00/LaneSeg.git'
tech:
  - Pytorch
  - K-Means
  - DBSCAN
  - Python
  - OpenCV
showInProjects: true
---

This project focuses on clustering cones using computer vision for autonomous vehicle navigation. Once detected, DBSCAN
is applied to group cones based on their relative positions, effectively
classifying cones on either side of the track. This clustering step helps organize cones spatially, ensuring the
autonomous vehicle can easily distinguish track boundaries and plan a navigable path accordingly.
