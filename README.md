# Machine Learning Midterm Project: Classification and Clustering Benchmarks

**Course:** Machine Learning Midterm Assignment  
**Datasets:** Breast Cancer Wisconsin (Diagnostic) & Wine Recognition  
**Author:** Nursena Selman  

---

## 1. Project Overview

This repository contains an end-to-end, reproducible machine learning benchmark evaluating supervised classification and unsupervised clustering algorithms across two distinct tabular benchmark datasets:
1. **Breast Cancer Wisconsin (Diagnostic):** Binary classification (569 samples, 30 continuous real-valued features).
2. **Wine Recognition:** Multi-class classification (178 samples, 13 continuous chemical attributes, 3 cultivar classes).

The experimental setup strictly follows a protocol designed to prevent data leakage, evaluate feature scale sensitivity, analyze seed variation, and perform model selection based on validation performance before evaluating on an isolated test partition.

---

## 2. Repository Structure

```text
.
├── notebooks/
│   ├── breast_cancer.ipynb   # Complete 10-section analysis for Breast Cancer
│   └── wine.ipynb            # Complete 10-section analysis for Wine
├── src/
│   └── utils.py              # Modular data loading, partitioning, and scaling utilities
├── figures/                  # High-resolution (300 DPI) visual artifacts
├── results/                  # All standardized tabular CSV outputs
└── README.md                 # Project documentation and summary