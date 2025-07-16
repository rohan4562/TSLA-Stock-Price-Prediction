# 📈 TSLA Stock Price Prediction using Machine Learning

This project focuses on predicting Tesla (TSLA) stock closing prices using machine learning regression models and historical stock data. The project includes data cleaning, feature engineering (technical indicators), multiple model training, and performance evaluation.

---

## 🔍 Problem Statement

**Can we accurately predict the closing price of TSLA stock using historical price trends and technical indicators like moving averages?**

---

## 📂 Project Structure

- `Data Collection`: Historical TSLA stock prices  
- `Data Preprocessing`: Handling missing values, feature generation  
- `Feature Engineering`: MA7, MA21, Lag values, Volume, etc.  
- `Model Building`: Linear Regression, Decision Tree, Random Forest  
- `Model Evaluation`: MAE, MSE, RMSE, R² Score  
- `Visualization`: Actual vs Predicted comparison, Feature Importance

---

## 📊 Models Used

| Model                  | Tuning Method     | Accuracy Technique        |
|------------------------|------------------|---------------------------|
| Linear Regression       | -                | Train-Test Split          |
| Decision Tree Regressor| GridSearchCV      | Cross-Validation (cv=3)   |
| Random Forest Regressor| GridSearchCV      | Cross-Validation (cv=3)   |

---

## ⚙️ Technologies & Tools

- **Language**: Python  
- **Libraries**:  
  - `Pandas`, `NumPy` – Data manipulation  
  - `Matplotlib`, `Seaborn` – Visualization  
  - `Scikit-learn` – Machine Learning models and metrics

---

## 📈 Evaluation Metrics

- **MAE** (Mean Absolute Error)  
- **MSE** (Mean Squared Error)  
- **RMSE** (Root Mean Squared Error)  
- **R² Score** (Coefficient of Determination)

---

## 🌲 Best Performing Model

> ✅ **Random Forest Regressor** gave the most reliable predictions after hyperparameter tuning with `GridSearchCV`.

---

## 📌 Key Learnings

- Difference between Linear and Tree-based regressors  
- How to apply moving averages (MA7, MA21) as features  
- Importance of cross-validation (cv=3)  
- Model evaluation and avoiding overfitting

---

## 🚀 How to Run the Project

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/tsla-stock-prediction.git
   cd tsla-stock-prediction
