---
layout: page
title: GNAP Attacking and Defending Facial Detection on Edge Devices
description: Adversarial attack and defense framework for robust facial detection on edge devices.
img: assets/img/GNAP-arch.png
importance: 2
category: Research
---

<p align="justify"> In this project, we present <b>GNAP</b> (Guided inspired Noise Attack Pyramid) and <b>GNAG</b> (Guided Noise Attack Guard), a paired adversarial attack and defense framework for facial detection systems deployed on resource-constrained edge devices. The work was developed as part of the research paper titled <i>"GNAPing On the Job: Attacking and Defending Facial Detection on Edge Devices"</i>, published in <b>IEEE SoutheastCon 2025</b>. The main objective of this project is to study how facial detection models operating on edge hardware can be disrupted by carefully designed adversarial perturbations, and how lightweight defensive techniques can be used to recover model robustness without sacrificing real-time performance. </p>

<p align="justify"> The proposed <b>GNAP attack</b> is designed to reduce facial detection confidence in practical edge-device scenarios by injecting guided multi-scale noise that degrades the model’s ability to detect or classify faces accurately. The repository provides support for both still-image and real-time video attack pipelines, including experiments on the <b>Labeled Faces in the Wild (LFW)</b> dataset and YOLO-based confidence evaluation. Complementing the attack, the <b>GNAG defense</b> introduces a restoration strategy that mitigates the adversarial impact and improves the detector’s performance on corrupted inputs. This makes the framework useful not only for demonstrating model vulnerabilities, but also for evaluating defense effectiveness in security-sensitive facial analytics systems. </p>

<p align="justify"> Experimental results reported in the project show that the proposed attack significantly reduces the system’s mean highest confidence from <b>0.99</b> on original inputs to <b>0.82</b> under GNAP attack conditions. After applying the proposed <b>GNAG defense</b>, confidence is restored to <b>0.98</b>, demonstrating strong recovery of facial detection robustness. These results highlight the practical relevance of adversarial robustness research for edge AI systems, especially in scenarios where computational efficiency, accuracy, and security must all be maintained simultaneously. </p>

Implementation of entire project can be found here: <a href="https://github.com/ChiefAj23/GNAPing-On-the-Job/tree/main#gnap"> Code </a>