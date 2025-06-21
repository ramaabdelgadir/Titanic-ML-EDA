# 🚢 Titanic Survival Prediction – Full ML Workflow with EDA

## 📌 Project Overview
This project explores and analyzes the Titanic dataset to uncover key patterns and build predictive models for passenger survival. It includes full exploratory data analysis (EDA), data cleaning, feature engineering, and evaluation of multiple machine learning models.

---

## 🧱 Project Structure

| File | Description |
|------|-------------|
| `1-EDA.ipynb` | Explores the dataset, performs cleaning, handles missing data, and visualizes key patterns |
| `2-ML.ipynb` | Applies and compares several ML models to predict survival |
| `data/train.csv` | Raw training data from Kaggle |
| `data/test.csv` | Raw test data from Kaggle |
| `data/train_cleaned.csv` | Cleaned version of training data |
| `data/test_cleaned.csv` | Cleaned version of test data |
| `data/submitted.csv` | Final predictions submitted to Kaggle |

---

## 📊 Models Applied

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- XGBoost

---

## ⚙️ Tools & Libraries

- Python (Jupyter Notebooks)  
- `pandas`, `numpy`, `matplotlib`, `seaborn` for EDA  
- `scikit-learn` for ML models & preprocessing  
- `xgboost` for gradient boosting  
- `RandomizedSearchCV` for hyperparameter tuning

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- ROC AUC Score  
- Model comparison in a summary DataFrame

> ✅ Best Models: **XGBoost** and **Random Forest** (~83% accuracy)
