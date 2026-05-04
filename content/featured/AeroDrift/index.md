---
date: '0'
title: 'AeroDrift: Predictive Maintenance API'
github: 'https://github.com/haytamelouarrat00/AeroDrift'
cover: './demo.png'
tech:
  - Polars
  - LightGBM
  - FastAPI
  - Python
showInProjects: true
---

A production-grade, end-to-end Machine Learning system designed to predict the Remaining Useful Life (RUL) of turbofan engines using high-frequency IoT telemetry data. The core of the system is a stateful FastAPI microservice that streams sensor data and computes rolling time-series features on the fly, providing real-time health alerts while heavily penalizing dangerous overestimations using a NASA-specific Asymmetric Loss Function.
