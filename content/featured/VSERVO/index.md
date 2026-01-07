---
date: '1'
title: 'Feature Based Visual Servoing Framework'
cover: './demo.png'
github: 'https://github.com/haytamelouarrat00/SERVO3D'
external: ''
cta: ''
tech:
  - OpenCV
  - Open3D
  - Numpy
  - Python
showInProjects: true
---

Python framework for simulating image-based visual servoing (IBVS) of a camera inside 3D scenes. It renders views from a 3D scene with Open3D, detects and matches visual features between a desired and current view, backprojects matched points with depth, and computes a camera velocity command via the interaction matrix (image Jacobian), A control loop updates the camera pose until the pixel error converges.
