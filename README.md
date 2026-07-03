# 🚢 Titanic - Machine Learning from Disaster

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-Scikit--Learn-orange.svg)](https://scikit-learn.org/)
[![Competition](https://img.shields.io/badge/Kaggle-Competition-blueviolet.svg)](https://www.kaggle.com/c/titanic)

## 📌 Overview

This repository contains a structured, end-to-end Machine Learning pipeline developed for the classic **Titanic: Machine Learning from Disaster** competition on Kaggle. The objective is to analyze historical passenger data and accurately predict survival outcomes using robust data pre-processing and diverse classification algorithms.

## 🎨 System Architecture Flow

The code is designed with crisp segregation following data science development standard practices:

[Raw Dataset] ➡️ [EDA & Missing Value Imputation] ➡️ [Feature Scaling & Encoding] ➡️ [Multi-Model Evaluation] ➡️ [Cross-Validation Optimization]

---

## 📊 Model Performance & Results

We trained and evaluated multiple classification paradigms on the scaled Titanic features. To maintain generalization and prevent data leakage or overfitting, cross-validation scoring was implemented on the top-performing architecture.

| Rank | Machine Learning Classifier         | Evaluation Metric  | Accuracy Score |
| :--: | :---------------------------------- | :----------------- | :------------: |
|  1   | 🏆 **Support Vector Machine (SVM)** | **Cross-Val Mean** |   **82.79%**   |
|  2   | 📈 Logistic Regression              | Test Accuracy      |     80.33%     |
|  3   | 🔍 KNN (K-Neighbors Classifier)     | Test Accuracy      |     79.21%     |
|  4   | 🌲 Decision Tree                    | Test Accuracy      |     75.28%     |

> 💡 **UI/UX & Developer Insight:** While standard linear boundaries like _Logistic Regression_ provided a highly reliable baseline (~80.33%), the non-linear high-dimensional hyperplane of the _Support Vector Machine (SVM)_ optimally captured the variance in features like class, age, and fare—resulting in our most stable performance metric (~82.79%).

---

## 🚀 Getting Started

### 1. Installation & Environment Setup

Clone this specific repository setup directly to your machine:

```bash
git clone [https://github.com/amirsohail100/Titanic---Machine-Learning-from-Disaster.git](https://github.com/amirsohail100/Titanic---Machine-Learning-from-Disaster.git)
cd Titanic---Machine-Learning-from-Disaster
pip install -r requirements.txt

Senior Developer aur UI/UX Designer ke taur par, maine aapke repository ke table ko aur zyada structural aur visually rich bana diya hai. Saath hi aapka Description Message bhi strictly 350-character limit ke andar update kar diya hai.
```
