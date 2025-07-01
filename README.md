# Voice-Based Parkinson's Detection using CNN

This repository contains a master's degree project focused on the early detection of Parkinson’s Disease (PD) through voice signal analysis using Convolutional Neural Networks (CNNs). The study applies advanced preprocessing and deep learning techniques to achieve accurate and robust classification of PD cases based on speech patterns.

## 🧠 Project Overview

Parkinson’s Disease (PD) is a progressive neurodegenerative disorder caused by the depletion of dopamine-producing neurons in the substantia nigra, resulting in motor dysfunctions and alterations in speech. Temporal variations in speech signals have been identified as potential biomarkers for PD, which highlights the importance of early diagnosis.

This project presents an optimized CNN classifier capable of detecting PD with high accuracy. The approach leverages the **Parkinson’s Disease Voice Recording Data Set**, which contains speech samples from **147 PD patients** and **48 healthy controls**, to improve diagnostic precision using machine learning.

## 📊 Methodology

- **Preprocessing**:
  - Denoising of audio samples
  - Feature normalization
  - Label encoding
  - Dataset partitioning

- **Model**:
  - CNN architecture
  - Bayesian hyperparameter tuning for optimization
  - Evaluation using Accuracy, Precision, Sensitivity, and F1 Score

- **Results**:
  - Detection Accuracy: **96.85%**
  - High precision and F1 score
  - Stable performance even with noisy data

These results validate the model’s robustness and its potential for clinical integration as a decision-support tool for neurologists.

## 📁 Repository Structure

- `audio/` — Audio files used in experiments
- `data/` — Raw and preprocessed data files (.data, .names)
- `models/` — Trained models and checkpoints (optional)
- `notebooks/` — Jupyter notebooks with exploratory analysis and training
- `README.md` — This file





## 📌 Dataset Source

The dataset used in this project was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/174/parkinsons).

> Dataset citation:
> Little MA, McSharry PE, Hunter EJ, Spielman J, Ramig LO. Suitability of dysphonia measurements for telemonitoring of Parkinson’s disease. *Nature Precedings*. 2008:1–1.

## 🎓 Academic Context

This work is part of a **Master’s research project** developed at the **Programa de Pós-Graduação em Modelagem e Simulação de Biossistemas (PPGMSB)** – Universidade do Estado da Bahia (UNEB), under the supervision of Prof. Dr. Marcos Figueredo.

## 📚 BibTeX Citation

If you use this dataset, please cite:

```bibtex
@article{little2008suitability,
  title     = {Suitability of dysphonia measurements for telemonitoring of Parkinson’s disease},
  author    = {Max Little and Patrick McSharry and Eric Hunter and Jennifer Spielman and Lorraine Ramig},
  journal   = {Nature Precedings},
  pages     = {1--1},
  year      = {2008},
  publisher = {Nature Publishing Group},
}
