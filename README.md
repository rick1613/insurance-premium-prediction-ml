# insurance-premium-prediction-ml
Machine learning project predicting medical insurance charges using feature engineering and Random Forest (R² = 0.885).


# 🏥 Insurance Premium Prediction (Machine Learning)

## 📌 Project Overview
This project predicts medical insurance charges using demographic and health-related features.  
The goal is to build a regression model capable of accurately estimating insurance costs.

---

## 📊 Dataset
- Kaggle Medical Insurance Dataset  
- 1337 samples  
- Features include:
  - Age
  - Sex
  - BMI
  - Number of children
  - Smoking status
  - Region

---

## ⚙️ Workflow

1. Data Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Encoding  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  

---

## 🧠 Models Used

- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

---

## 🚀 Feature Engineering

The following engineered features significantly improved performance:

- BMI Categories
- Age Groups
- Age × BMI interaction
- Family Risk Feature (Children × Age)

---

## 📈 Final Model Performance

| Model               | R² Score |
|--------------------|----------|
| Linear Regression  | 0.751    |
| Random Forest      | **0.885** |
| XGBoost            | 0.799    |

Random Forest achieved the best performance with an R² score of **0.885**.

---

## 📊 Key Insights

- Smoking status is the strongest predictor of insurance charges.
- Age and BMI interaction significantly impacts cost.
- Feature engineering improved model accuracy substantially.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

## 📂 How to Run

1. Clone the repository
2. Install dependencies:
--- pip install -r requirements.txt
3. Run the Jupyter notebook

---

## 📬 Author

Built as an end-to-end machine learning regression project.



