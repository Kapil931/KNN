# Effect of k and Feature Scaling on KNN Performance and Decision Boundaries

This repository contains a tutorial assignment exploring **how the choice of _k_ and feature scaling influence the performance and decision boundaries of the k-Nearest Neighbour (KNN) algorithm**. It combines a fully worked Jupyter notebook with a written report. :contentReference[oaicite:0]{index=0}

---

## Overview

K-Nearest Neighbours (KNN) is one of the simplest and most intuitive machine learning algorithms. This project uses a **custom synthetic dataset** to show:

- How the number of neighbours **k** affects:
  - Overfitting vs. underfitting  
  - The shape of decision boundaries
- Why **feature scaling** is essential for distance-based models
- How **distance metrics** (Euclidean, Manhattan, Minkowski) change neighbour relationships
- How to use **cross-validation** to select a good value of k
- How adding **noise features** illustrates the **curse of dimensionality**
- Practical **ethical considerations** of KNN (privacy, fairness, transparency)

The goal is to make KNN behaviour easy to **see, measure and understand**, not just describe in theory. :contentReference[oaicite:1]{index=1}

---

## Repository Contents

- `Custom Synthetic dataset using KNN.ipynb`  
  Interactive Jupyter notebook that:
  - Generates a custom 4D dataset (3 Gaussian classes, 2 core features, 1 large-scale feature, 1 noisy feature)
  - Visualises the dataset and KNN decision boundaries for different values of k
  - Compares KNN **with vs. without feature scaling**
  - Uses **cross-validation** to choose the best k
  - Runs an optional **curse of dimensionality** experiment by adding noise dimensions

- `Effect of k and Feature Scaling on KNN Performance and Decision Boundaries.pdf`  
  Full written report explaining the theory, experiments, plots and conclusions in detail. :contentReference[oaicite:2]{index=2}

*(Add more files here if you later include a `requirements.txt`, data folder, or images.)*

---

## Getting Started

### Requirements

You will need:

- Python 3.8+  
- Recommended packages:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `jupyter` (or JupyterLab / VS Code with Python extension)

You can install them with:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
