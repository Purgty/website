---
title: "CLAIMS: Clinical Labeling and Abnormality Inference from Multilead ECG using LLMs with Evidence Citation"
date: 2025-01-01
tags: ["ECG analysis", "clinical AI", "LLMs", "CNN", "explainability", "medical signal processing"]
author: [
  "Aswinkumar Varathakumaran",
  "Akshita Jawahar",
  "Pandiyaraju V",
  "Senthil Kumar A M"
]
description: "An interpretable ECG analysis pipeline that fuses CNN-based feature extraction with structured claim generation and LLM-driven report synthesis, producing clinically traceable diagnostic narratives."
summary: "CLAIMS is an explainable clinical ECG interpretation framework combining rule-based signal features, CNN embeddings, and LLM-guided narrative synthesis. Designed for the PTB-XL dataset, it generates transparent diagnostic reports that include evidence citations, improving trustworthiness and interpretability over traditional black-box deep learning models."
cover:
    image: "CLAIMS_Arch_Diag.png"
    alt: "Placeholder cover image for CLAIMS ECG paper"
    relative: true
editPost:
    URL: "https://github.com/pmichaillat/hugo-website"
    Text: "Source"
---

---

##### Download

+ [Paper](CLAIMS_Paper.pdf)
+ [Code](https://github.com/YOUR_GITHUB_REPO)
+ [Data](https://www.kaggle.com/datasets/khyeh0719/ptb-xl-dataset/data)

---

##### Abstract

ECG interpretation is vital in clinical cardiology for detecting cardiovascular conditions, yet manual waveform analysis is labor-intensive and prone to error. This paper introduces **CLAIMS**, an automated multi-lead ECG interpretation pipeline that integrates Convolutional Neural Networks (CNNs) and Large Language Models (LLMs) for accurate and explainable classification. The system extracts waveform-level features across all 12 leads, forms structured evidence-based claims, and generates clinical reports using an LLM fine-tuned for medical reasoning. Claims include explicit timestamp citations from raw ECG signals, improving interpretability and trust. Experiments on the PTB-XL dataset demonstrate that CLAIMS produces clinically meaningful, evidence-backed diagnostic narratives while achieving competitive performance in identifying key cardiac abnormalities.

---

##### Figure 1: System Architecture (placeholder)

![](CLAIMS_Arch_Diag.png)

---

##### Citation

Varathakumaran, A., Jawahar, A., Pandiyaraju, V., & Senthil Kumar, A. M. (2025). *CLAIMS: Clinical Labeling and Abnormality Inference from Multilead ECG using LLMs with Evidence Citation.* IEEE Conference Publication.

```latex
@inproceedings{Varathakumaran2025CLAIMS,
  author    = {Aswinkumar Varathakumaran and Akshita Jawahar and Pandiyaraju V and Senthil Kumar A M},
  title     = {CLAIMS: Clinical Labeling and Abnormality Inference from Multilead {ECG} using {LLMs} with Evidence Citation},
  booktitle = {IEEE Conference Proceedings},
  year      = {2025},
  url       = {https://YOUR_LINK_HERE}
}