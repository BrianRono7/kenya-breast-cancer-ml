# Breast Cancer Classification Project

## Overview
This project builds and evaluates machine-learning models to classify breast tumors as **Malignant (M)** or **Benign (B)** using numerical clinical features. The workflow includes data exploration, feature analysis, modeling, and evaluation.

---

## Dataset
The dataset contains:

- **Diagnosis** (target)
- Numerical features describing tumor characteristics:
  - Radius
  - Texture
  - Perimeter
  - Area
  - Smoothness
  - Compactness
  - Concavity
  - Symmetry
  - Fractal Dimension

Each feature includes mean, standard error, and worst values.

---

## Workflow
1. Load and inspect the dataset  
2. Exploratory Data Analysis (EDA)  
3. Correlation and multicollinearity checks  
4. Preprocessing and feature engineering  
5. Train models:
   - Logistic Regression  
   - Random Forest  
   - K-Nearest Neighbors  
   - AdaBoost  
   - XGBoost  
6. Evaluate models using:
   - Accuracy  
   - Confusion Matrix  
   - Classification Report  

---

## How to Run

Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
