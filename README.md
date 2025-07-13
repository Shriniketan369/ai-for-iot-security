# 🔐 AI-Based Intrusion Detection System for Securing IoT Networks (BoT-IoT Dataset)

This repository contains the full code, research paper, and visual assets for a project that uses **AI-based models** to build an **Intrusion Detection System (IDS)** for IoT environments. It compares the performance of **Random Forest**, **Support Vector Machine (SVM)**, and an **Autoencoder** using the **BoT-IoT dataset**.

---

## 📌 Abstract

The increasing number of IoT devices has introduced serious security vulnerabilities. This project builds and evaluates an AI-driven IDS to protect such networks. We used the BoT-IoT dataset and compared three models:

- Random Forest
- Support Vector Machine (SVM)
- Autoencoder (Unsupervised)

Each was assessed on accuracy, precision, recall, training time, and feasibility for real-world IoT deployment.

---

## 📁 Dataset

- **Dataset:** BoT-IoT (5% sample)
- **Source:** [UNSW Canberra Cyber Range Lab](https://research.unsw.edu.au/projects/bot-iot-dataset)
- **Balanced Samples:** 477 benign & 477 malicious
- **Preprocessing:** Dropped non-numeric columns, handled NaNs, normalized features, encoded labels.

---

## 🛠️ Tools & Libraries

| Tool / Library        | Purpose                                      |
|------------------------|----------------------------------------------|
| Python 3.10+           | Core language                               |
| Pandas, NumPy          | Data processing                             |
| Scikit-learn           | RF & SVM models, metrics, preprocessing     |
| TensorFlow / Keras     | Autoencoder training                        |
| Matplotlib             | Graphs and visuals                          |
| Google Colab           | Development platform                        |
| Canva                  | Diagrams and illustrations                  |

---

## 🧪 Experiments

| Model         | Accuracy | Precision | Recall | F1 Score | Training Time |
|---------------|----------|-----------|--------|----------|----------------|
| Random Forest | 100%     | 100%      | 100%   | 100%     | 0.18 sec       |
| SVM           | 99%      | 99.8%     | 99.9%  | 99%      | 0.09 sec       |
| Autoencoder   | 55.5%    | 100%      | 10.5%  | 19.05%   | 2.07 sec       |

> ⚠️ The Autoencoder’s recall was limited due to fewer “normal” samples in training. Future work aims to improve this with richer data.

---

## 📊 Illustrations & Visual Assets

- 📌 *Figure 1:* IDS Build Flowchart  
- 📌 *Figure 2:* Preprocessing Pipeline  
- 📌 *Figure 3:* Class Imbalance Bar Chart  
- 📌 *Figure 4:* AI-Based IDS System Architecture  
- 📌 *Figure 5:* Deployment Architecture  
- 📌 *Figure 6:* Performance Table  
- 📌 *Figure 7:* Metrics Comparison (Bar Chart)  
- 📌 *Figure 8:* Tradeoff Diagram (Interpretability vs Accuracy)

All illustrations are stored in the `/images/` folder.

---

## 📓 Research Paper

The full research paper (with 8 illustrations, glossary, and references) is available here:

📄 [`AI-Based Intrusion Detection System for IoT`](https://github.com/Shriniketan369/ai-for-iot-security/blob/main/paper/AI-Based%20Intrusion%20Detection%20System%20for%20Securing%20IoT%20Networks%20using%20the%20BoT-IoT%20Dataset.pdf)

---

## ▶️ How to Run

Use [Google Colab](https://colab.research.google.com/) to run the notebook:

1. Open the notebook file: [`AI_IDS_BoT-IoT.ipynb`](https://github.com/Shriniketan369/ai-for-iot-security/blob/main/AI_IDS_BoT-IoT.ipynb)
2. Upload or link your BoT-IoT `sample_data.csv`
3. Run all cells to train and evaluate the models

---

## 🧩 Repository Structure