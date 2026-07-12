# Enhanced Intrusion Detection System (IDS) using EBBA

![IDS Banner](images/ids_banner.jpg)

This repository contains the implementation and evaluation of an Enhanced Intrusion Detection System (IDS) using a proposed **EBBA** model. The approach is evaluated and validated against two major cybersecurity benchmark datasets: **NSL-KDD** and **UNSW-NB15**.

## 📂 Project Structure
- `EBBA NSL (2).ipynb`: Data preprocessing, exploratory analysis, and model training/evaluation on the NSL-KDD dataset.
- `EBBA UNSW (2).ipynb`: Data preprocessing, exploratory analysis, and model training/evaluation on the UNSW-NB15 dataset.

## ⚙️ Methodology
This project addresses cybersecurity threat detection by comparing the performance of the proposed EBBA model against traditional machine learning algorithms, including:
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- XGBoost
- LightGBM

To ensure robustness and prevent model bias, **SMOTE** (Synthetic Minority Over-sampling Technique) is utilized to balance the normal and anomalous traffic data before training.

## 📊 Results & Visualizations

### Model Performance Comparison
The proposed EBBA model demonstrates highly competitive Accuracy, Precision, Recall, and F1 Scores across the datasets when compared to existing state-of-the-art algorithms.
*(Save your bar chart screenshot here as `images/model_comparison.jpg`)*
![Model Comparison](images/model_comparison.jpg)

### Data Balancing (Before & After SMOTE)
**Before SMOTE:**
*(Save your Before SMOTE screenshot here as `images/before_smote.jpg`)*
![Before SMOTE](images/before_smote.jpg)

**After SMOTE:**
*(Save your After SMOTE screenshot here as `images/after_smote.jpg`)*
![After SMOTE](images/after_smote.jpg)

### Confusion Matrices
The confusion matrices highlight the model's accuracy in distinguishing between Normal (0) and Attack/Anomaly (1) instances.

**UNSW Dataset:**
*(Save your UNSW Confusion Matrix here as `images/confusion_matrix_unsw.jpg`)*
![UNSW Confusion Matrix](images/confusion_matrix_unsw.jpg)

**NSL Dataset:**
*(Save your NSL Confusion Matrix here as `images/confusion_matrix_nsl.jpg`)*
![NSL Confusion Matrix](images/confusion_matrix_nsl.jpg)
