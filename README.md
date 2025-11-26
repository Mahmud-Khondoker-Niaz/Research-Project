# A Hybrid Framework Combining Machine Learning and Deep Learning for Intelligent Loan Approval Prediction

This repository contains the working research paper, code, and dataset used to build a hybrid ML–DL model for intelligent loan approval prediction. 
The study evaluates 15 machine learning, deep learning, and ensemble models on a structured dataset of 5,000 customer profiles.


## 🔍 Overview
The goal of this research is to improve the accuracy, fairness, and interpretability of automated loan approval systems.  
A unified pipeline was developed with preprocessing (cleaning, outlier removal, normalization, log transformation, SMOTE) and evaluation of ML + DL + Ensemble models.


## 📄 Paper
[Download PDF](Paper/Loan_IEEE_ICCIT(2).pdf)


### Key Features
- Dataset: 5,000 rows, 13 selected attributes  
- Models tested: 15  
- Techniques: SMOTE, IQR outlier removal, Min–Max scaling  
- Explainability: SHAP & LIME  
- Best model accuracy: **99.30%**

---

## 📊 Model Performance (Top Results)
| Model | Accuracy |
|-------|----------|
| **XGBoost** | **99.30%** |
| CatBoost | 99.00% |
| LightGBM | 99.10% |
| Random Forest | 98.80% |
| MLP | 98.80% |
