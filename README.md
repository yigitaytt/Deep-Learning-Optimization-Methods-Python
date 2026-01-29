# 📉 Deep Learning Optimization Methods in Python

![Project Status](https://img.shields.io/badge/Status-Completed-success) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

This project is a comprehensive analysis suite designed to benchmark **optimization algorithms** (GD, SGD, Adam, etc.) and evaluate **semantic representation models** in Deep Learning. It combines mathematical optimization theory with practical NLP applications using PyTorch.

## 🚀 Features & Modules

### 🔹 Part A: Optimization Benchmarking
* **Algorithms Compared:** Gradient Descent (GD), Stochastic Gradient Descent (SGD), and Adam.
* **Metrics:** Convergence speed, Loss landscape navigation, and Accuracy.
* **Robustness:** Tests are conducted across **5 random seeds** to ensure reliability.

### 🔹 Part B: Visualizing Trajectories (t-SNE)
* Uses **t-SNE** to project high-dimensional weight updates into 2D space.
* Visualizes the "path" taken by each optimizer (Adam vs. SGD) from initialization to convergence.

### 🔹 Part C: Advanced Analysis (Noise & MLP)
* **Architecture:** Tests performance on a **2-Layer MLP** (non-linear) vs. Simple Linear Models.
* **Extended Optimizers:** Includes **Adagrad** and **RMSProp** in the comparison.
* **Data Sensitivity:** Analyzes model performance under varying dataset sizes and **Gaussian Noise** injection.

### 🔹 Part D: Semantic Analysis (NLP) with COSMOS & E5
A comparative study of text embeddings for Turkish QA classification.
* **Models:** TF-IDF vs. BERT vs. **E5**.
* **Methodology:** The dataset creation (Question-Answer pairs) and embedding processes were specifically powered by **COSMOS T1** and **E5** models to ensure state-of-the-art semantic understanding in Turkish.

## 🛠️ Technology Stack

* **Language:** Python
* **Core Framework:** PyTorch
* **Data & Math:** NumPy, Pandas, Scikit-Learn (t-SNE)
* **NLP Models:** Hugging Face Transformers, Sentence-Transformers (E5)

## 📊 Key Findings

| Metric | Best Performer | Insight |
| :--- | :--- | :--- |
| **Speed** | **Adam** | Converges significantly faster on complex landscapes. |
| **Stability** | **GD / RMSProp** | Shows smoother trajectories but slower updates. |
| **NLP Accuracy** | **E5** | Outperformed BERT and TF-IDF in semantic similarity tasks. |

## 👤 Author

**Yiğit Aytürk**
