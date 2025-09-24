# 🧠 Breast Cancer Tumor Classification using SVM

![alt text](image.png)

This project classifies breast tumors as **malignant** or **benign** using a **Support Vector Machine (SVM)** model trained on the **Breast Cancer Wisconsin (Diagnostic) Dataset**. The primary evaluation metric is **recall**, with the goal of minimizing false negatives — a critical requirement in medical diagnosis.

---

## 📊 Dataset

- **Name:** Breast Cancer Wisconsin (Diagnostic) Dataset
- **Source:** UCI Machine Learning Repository
- **Features:** 30 numerical features derived from digitized images of breast tissue
- **Target Classes:**
  - `M` = Malignant
  - `B` = Benign

---

## 🎯 Project Objectives 

- Load and preprocess the dataset
- Train a Support Vector Machine (SVM) classifier
- Evaluate the model with a focus on **recall**
- Support early and accurate detection of breast cancer
## 📝 Blog Post

For a detailed walkthrough, check out the accompanying article:

[Breast Tumor Classification using SVM – Medium Article](https://medium.com/@murithidenisgitobu/breast-tumor-classification-using-svm-beating-breast-cancer-5a3570807247)

---

## 🧪 Model Evaluation

- **Primary Metric:** Recall
- **Why Recall?**  
  In cancer detection, it is crucial to identify all malignant cases, even at the cost of some false positives. Prioritizing recall helps reduce the chances of missing a dangerous diagnosis.

- **Other Metrics Used:**
  - Accuracy
  - Precision
  - F1-score
  - Confusion Matrix

---

## 🧰 Tools and Libraries

- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib / Seaborn (for visualization, if used)

---
