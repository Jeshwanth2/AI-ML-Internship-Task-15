# AI-ML-Internship-Task-15
---

# End-to-End Machine Learning Pipeline  

## Overview  
This project implements a complete machine learning pipeline using Python and scikit-learn. The pipeline integrates preprocessing, model training, and evaluation in a structured workflow to ensure reproducibility and prevent data leakage.  

## Dataset  
- **Primary:** Breast Cancer dataset (`sklearn.datasets.load_breast_cancer`)  
- **Alternative:** Titanic dataset (CSV from Kaggle)  

## Steps Implemented  
1. **Data Loading** – Import dataset and separate features (X) and target (y).  
2. **Feature Identification** – Distinguish numerical and categorical features.  
3. **Preprocessing** –  
   - Scale numerical features with `StandardScaler`.  
   - Encode categorical features with `OneHotEncoder`.  
   - Combine using `ColumnTransformer`.  
4. **Pipeline Creation** – Build a pipeline integrating preprocessing and classifier (Logistic Regression / RandomForest).  
5. **Train-Test Split** – Split dataset (80/20).  
6. **Model Training & Prediction** – Train pipeline and generate predictions.  
7. **Evaluation** – Compute accuracy, precision, recall, and F1-score.  

## Deliverables  
- Jupyter Notebook/Colab file with code and explanations.  
- Evaluation metrics summary.  
- Saved pipeline model (`.pkl`).  
- README file (this document).  

## Key Concepts  
- **ML Pipeline:** Automates preprocessing + training steps.  
- **ColumnTransformer:** Applies different preprocessing to different feature types.  
- **Advantages:** Prevents data leakage, simplifies deployment, ensures reproducibility.  
