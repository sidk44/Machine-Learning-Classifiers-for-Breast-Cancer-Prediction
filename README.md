# Breast Cancer Prediction – Classifier Comparison

This repository contains code and analysis for a machine learning project that applies different classifiers to the **Breast Cancer Wisconsin (Diagnostic) dataset**.  
The aim is to predict whether a tumor is **malignant** or **benign** based on 30 diagnostic features derived from digitized medical images.  

## 📊 Project Overview
- Dataset: Breast Cancer (from `sklearn.datasets` / UCI ML Repository)  -> dataset_breast_cancer.zip
- Algorithms used:  
  - Logistic Regression  
  - K-Nearest Neighbors (KNN)  
  - Support Vector Machine (SVM, RBF kernel)  
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC
- Attached Project Video demo as well as documentation report.
  

## 📈 Results Summary
| Model                | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|----------------------|----------|-----------|--------|----------|---------|
| Logistic Regression  | 98.2%    | 98.6%     | 98.6%  | 98.6%    | 0.995   |
| KNN (k=5)            | 95.6%    | 95.9%     | 97.2%  | 96.5%    | 0.979   |
| SVM (RBF Kernel)     | 98.2%    | 98.6%     | 98.6%  | 98.6%    | 0.995   |

- Logistic Regression and SVM performed equally well (~98% accuracy).  
- KNN was slightly weaker but still effective (~96% accuracy).  

