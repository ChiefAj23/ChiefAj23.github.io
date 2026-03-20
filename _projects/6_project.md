---
layout: page
title: "ReAL: Reflective Attack Detection for LPLiDARometry"
description: Machine learning-based real-time detection of reflective attacks against LiDAR systems on edge devices.
img: assets/img/ReALArch.png
importance: 2
category: Research
---

<p align="justify"> In this project, we present <b>ReAL</b>, a machine learning-based detection framework for identifying reflective surface attacks against LiDAR sensing systems in real time. Developed as part of the paper <i>"ReAL: Machine Learning Detection of Reflective Attacks against Lidarometry"</i>, published in <b>IEEE SoutheastCon 2025</b>, this work addresses a critical security challenge in perception systems that rely on LiDAR measurements for environmental awareness. Reflective surfaces can distort LiDAR returns and introduce misleading sensor readings, which may compromise downstream perception and decision-making in autonomous and edge-based systems. </p>

<p align="justify"> Our approach focuses on building a lightweight and effective detection pipeline that can operate on <b>resource-constrained edge hardware</b>, including the <b>Jetson Orin</b> platform. Using data collected from an <b>RPLiDAR A1M8-R6</b> sensor, we constructed multiple experimental scenarios involving different object placements, reflective conditions, distances, and angular configurations to model a wide range of reflective interference behaviors. The resulting dataset was used to train and evaluate machine learning models capable of distinguishing normal LiDAR observations from reflective attack conditions with high confidence and low inference latency. </p>

<p align="justify"> The system was evaluated across three increasingly complex scenarios. In Scenario 1, the model achieved an inference accuracy of <b>92.71%</b> with an F1-score of <b>92.70</b> and latency of <b>2.763 ms</b>. In Scenario 2, performance improved to <b>95.53%</b> accuracy and <b>95.52</b> F1-score with <b>4.727 ms</b> latency. In Scenario 3, which simulated more realistic multi-object reflective conditions, the detector reached <b>99.97%</b> accuracy, <b>99.97</b> F1-score, and only <b>0.083 ms</b> latency. These results demonstrate that the proposed defense can detect reflective attacks both accurately and efficiently, making it practical for deployment in real-world edge AI perception systems. </p>

Implementation of entire project can be found here: <a href="https://github.com/ChiefAj23/ReAL-ReflectiveAttack-Detection-Lidar"> Code </a>
