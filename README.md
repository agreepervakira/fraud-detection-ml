Fraud Detection Using Random Forest and SMOTE
📌 Project Overview

This project implements a machine learning model to detect fraudulent credit card transactions using the Random Forest algorithm and SMOTE (Synthetic Minority Oversampling Technique) to address class imbalance.

 📁 Dataset

Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
Shape: 284,807 transactions with 30 features
Target variable: `Class` (0 = Legitimate, 1 = Fraudulent)

🔧 Libraries Used
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- 
  🔁 Workflow

1. Import Libraries
2. Load and Prepare Dataset
   - Drop target column from features
   - Normalize using `StandardScaler`
3. Train-Test Split (80/20)
4. Handle Imbalanced Data with SMOTE
5. Train Random Forest Classifier
6. Model Evaluation
   - Classification Report
   - Confusion Matrix
   - ROC-AUC Score
