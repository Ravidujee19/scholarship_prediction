# 🎓 Scholarship Exam Prediction using Student Test Scores

This project uses machine learning to predict whether a 4th-grade student will pass the 5th-grade scholarship exam based on their test scores. The dataset includes exam results for 30 students.

## 🔍 Overview

The notebook includes:
- Data loading from CSV files
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Model training and evaluation
- Making predictions on new students

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

## 📁 Files and Folders

- `scholarship.ipynb` — Main analysis notebook
- `README.md` — This documentation
- `data/` — Folder containing CSV files:
  - `training_data.csv` — Marks of 30 students used for training
  - `prediction_data.csv` — Data used for making predictions

## 📊 Model Performance

- **Accuracy:** 93.33%
- **Precision:**  
  - Fail: 0.95  
  - Maybe: 0.86  
  - Pass: 1.00
- **Recall:**  
  - Fail: 0.86  
  - Maybe: 0.95  
  - Pass: 1.00
- **F1-Score (average):** 0.93

## 📄 License
This project is licensed under the MIT License.
