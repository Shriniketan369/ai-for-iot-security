# AI-Based Intrusion Detection System for IoT Networks

This repository contains the code, data pipeline, and results for an AI-based Intrusion Detection System using the BoT-IoT dataset. The project compares Random Forest, Support Vector Machine, and Autoencoder models for real-time intrusion detection in resource-constrained IoT environments.

## 🔍 Overview
- Dataset: BoT-IoT Dataset (5% Sample)
- Models: Random Forest, SVM, Autoencoder
- Goal: High accuracy + real-world deployability

## 📁 Files Included
- `notebook.ipynb` – The complete training, evaluation, and plotting notebook
- `dataset_sample.csv` – A small balanced dataset used for model testing
- `results/` – Visualizations and evaluation graphs
- `src/` – Source code (optional separation if needed)

## 📊 Results Summary
| Model | Accuracy | Precision | Recall | F1 Score |
|-------|----------|-----------|--------|----------|
| Random Forest | 100% | 100% | 100% | 100% |
| SVM | 99% | 99.8% | 99.9% | 99% |
| Autoencoder | 55.5% | 100% | 10.53% | 19.05% |

## 📌 Requirements
- Python 3.10+
- Pandas, Numpy
- Scikit-learn
- TensorFlow/Keras
- Matplotlib

Install dependencies:
```bash
pip install -r requirements.txt