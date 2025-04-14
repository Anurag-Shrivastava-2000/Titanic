# 🛳️ Titanic Survival Prediction using XGBoost

This project tackles the classic **Titanic - Machine Learning from Disaster** Kaggle competition. The goal is to predict whether a passenger survived the Titanic shipwreck using various features such as age, gender, class, and more. The model is built using the powerful **XGBoost** algorithm.

---

## 📌 Project Objective

Predict survival on the Titanic using structured data with a focus on:
- Data cleaning and preprocessing
- Feature engineering
- Model training and evaluation using XGBoost

---

## 🔧 Tools & Libraries Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn (for EDA)
- Scikit-learn (preprocessing, evaluation)
- XGBoost (modeling)

---

## 📊 Dataset

The dataset is provided by Kaggle and includes:
- `train.csv` – labeled data for model training
- `test.csv` – data to generate final predictions

You can find the dataset [here](https://www.kaggle.com/competitions/titanic/data).

---

## 🔍 Key Steps

1. **Exploratory Data Analysis (EDA)**  
   - Understanding missing values, distributions, and feature correlations
2. **Data Preprocessing**  
   - Handling nulls, encoding categorical variables, feature scaling
3. **Feature Engineering**  
   - Creating new features like `FamilySize`, `IsAlone`, and `Title` from names
4. **Modeling with XGBoost**  
   - Used GridSearchCV for hyperparameter tuning  
   - Evaluated using accuracy and cross-validation
5. **Prediction & Submission**  
   - Predictions generated on the test set in Kaggle submission format

---

## 🧠 Why XGBoost?

- Fast, efficient gradient boosting algorithm
- Handles missing values internally
- Regularization support to reduce overfitting
- Strong performance on structured/tabular datasets

---


## 📁 Project Structure

```bash
titanic-xgboost/
│
├── data/                   # train.csv & test.csv
├── notebooks/              # Jupyter notebooks for EDA & modeling
├── titanic_xgboost.py      # Final Python script for training & prediction
├── submission.csv          # Kaggle-ready output
└── README.md               # Project documentation

