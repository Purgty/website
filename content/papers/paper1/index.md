---
title: "ProvRain: Rain-Adaptive Denoising and Vehicle Detection via MobileNet-UNet and Faster R-CNN"
date: 2025-01-01
tags: ["computer vision", "nighttime detection", "image restoration", "deep learning", "autonomous driving"]
author: ["Aswinkumar Varathakumaran","Nirmala Paramanandham"]
description: "A lightweight, curriculum-trained MobileNet-U-Net denoiser combined with a Faster R-CNN pipeline for robust nighttime vehicle detection under rainy conditions."
summary: "ProvRain introduces a rain-adaptive detection pipeline using a lightweight MobileNet-U-Net denoiser and Faster R-CNN classifier. Designed for nighttime driving under severe rain, the method improves recall, accuracy, and early-warning success while remaining efficient enough for real-time automotive hardware."
cover:
    image: "ProvRain_Arch_Diag.png"
    alt: "Placeholder cover image for ProvRain paper"
    relative: true
editPost:
    URL: "https://github.com/Purgty/ProvRain---Provident-Night-Time-Vehicle-Detection-with-Rain-Removal"
    Text: "Code"
---

---

##### Download

+ [Paper](ProvRain_IEEE.pdf)
+ [Code](https://github.com/Purgty/ProvRain---Provident-Night-Time-Vehicle-Detection-with-Rain-Removal)
+ [Data](https://www.kaggle.com/datasets/saralajew/provident-vehicle-detection-at-night-pvdn)

---

##### Abstract

Provident vehicle detection has significant potential for identifying vehicles during nighttime driving. Extracting features beyond headlamps allows earlier detection of oncoming vehicles before they appear directly in view. However, nighttime imagery suffers from severe noise caused by weather, sensor limitations, and motion. ProvRain addresses these challenges by introducing a lightweight MobileNet-U-Net denoising network trained via a weather-aware curriculum strategy using a mix of synthetic and PVDN dataset samples. This denoiser is then integrated into a Faster R-CNN pipeline to improve robustness in rain-degraded nighttime scenes. Experiments demonstrate an 8.94% improvement in detection accuracy, a 10.25% increase in recall, and substantial gains in image restoration metrics (10–15% PSNR improvement, 5–6% SSIM improvement, and up to 67% reduction in perceptual error).

---

##### Figure 1: Architecture Diagram (placeholder)

![](ProvRain_Arch_Diag.png)

---

##### Citation

Varathakumaran, A., & Paramanandham, N. (2025). *ProvRain: Rain-Adaptive Denoising and Vehicle Detection via MobileNet-UNet and Faster R-CNN*. IEEE Conference Publication.

```latex
@inproceedings{Varathakumaran2025ProvRain,
  author    = {Aswinkumar Varathakumaran and Nirmala Paramanandham},
  title     = {ProvRain: Rain-Adaptive Denoising and Vehicle Detection via {MobileNet{-}UNet} and {Faster R{-}CNN}},
  booktitle = {IEEE Conference Proceedings},
  year      = {2025},
  url       = {https://YOUR_LINK_HERE}
}