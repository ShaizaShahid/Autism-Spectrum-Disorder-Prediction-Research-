# Autism-Spectrum-Disorder-Prediction-Research-

# 🧠 Autism Spectrum Disorder Detection using Machine Learning

## 📌 Overview

This project focuses on the early detection of Autism Spectrum Disorder (ASD) using machine learning and ensemble learning techniques. The system leverages behavioral and demographic data to accurately classify individuals as ASD or non-ASD.

The model integrates multiple algorithms including SVM, KNN, XGBoost, LightGBM, and advanced ensemble approaches such as Hybrid Kernel SVM and Stacking Classifier.

---

## 🎯 Objectives

* Detect Autism Spectrum Disorder using ML models
* Improve prediction accuracy using ensemble techniques
* Compare performance of multiple classifiers
* Build a robust and scalable diagnostic system

---

## 📊 Dataset

* Source: Kaggle ASD Dataset

* Total Instances: **1923**

* Features include:

  * Age, Gender, Ethnicity
  * ASD Screening Questions (A1–A10)
  * Behavioral traits
  * Family history
  * Medical conditions

* Target Variable:

  * `ASD_traits` → (Yes / No)

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Handling missing values
* Label encoding for categorical features
* Stratified train-test split (80/20)
* Handling class imbalance

### 2. Models Implemented

* Naïve Bayes (NB)
* AdaBoost
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* LightGBM
* XGBoost

### 3. Ensemble Techniques

* Hybrid Kernel SVM (RBF + Polynomial + Linear)
* Boosting Classifier
* **Stacking Classifier (Best Model)**

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Mean Squared Error (MSE)

These metrics help evaluate classification performance, especially for imbalanced datasets. 

---

## 🏆 Results

| Model                   | Accuracy   |
| ----------------------- | ---------- |
| Naïve Bayes             | 70%        |
| AdaBoost                | 81%        |
| SVM                     | 96%        |
| KNN                     | 97%        |
| LightGBM                | 99%        |
| XGBoost                 | 99%        |
| Hybrid SVM              | 95%        |
| **Stacking Classifier** | **99.74%** |

👉 The **Stacking Classifier** achieved the highest performance with minimal error.

---

## 🧪 System Requirements

* CPU: 5th Gen Processor (2.5 GHz)
* RAM: 8 GB
* OS: Windows 10 (64-bit)

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🚀 How to Run

```bash
# Clone repository
git clone https://github.com/your-username/asd-detection.git

# Navigate to project
cd asd-detection

# Install dependencies
pip install -r requirements.txt

# Run project
python main.py
```

---

## 📊 Visualizations

* Confusion Matrix
* ROC Curve
* Precision-Recall Curve
* Learning Curves
* Loss Graph

---

## 🔍 Key Insights

* Ensemble learning significantly improves accuracy
* Stacking combines strengths of multiple models
* Boosting reduces prediction errors
* Dataset imbalance handled effectively



[1]: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes?utm_source=chatgpt.com "About the repository README file - GitHub Docs"
