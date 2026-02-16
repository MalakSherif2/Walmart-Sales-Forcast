# Walmart Sales Forecast 📊

## 📌 Project Overview
This project focuses on forecasting future sales using historical sales data from Walmart.
The goal is to analyze sales trends, create time-based features, and apply regression models
to predict future sales accurately.

---

## 📂 Dataset
- **Source:** Walmart Sales Forecast Dataset (Kaggle)
- **Main Features:**
  - Date
  - Weekly_Sales
  - Store
  - Department (if available)

---

## 🔍 Exploratory Data Analysis (EDA)
The following insights were discovered during data exploration:

- Sales showed an **increase between 2010 and 2012**, followed by a **decline in 2013**.
- Strong **seasonality effect** was observed.
- Sales tend to **increase significantly during Spring**.
- Time series plots revealed clear trends and seasonal patterns.

Visualizations used:
- Line plots for sales over time
- Trend analysis by year and season

---

## 🛠️ Data Preprocessing
- Converted `Date` column to datetime format
- Extracted time-based features:
  - Year
  - Month
  - Day
  - Season
- Handled missing values
- Created lag features and rolling averages (Bonus)

---

## ⚙️ Feature Engineering
- Lag features (previous sales values)
- Rolling mean features to capture trends
- Seasonal feature derived from date

---

## 🤖 Models Used
The following regression models were applied:
- **Linear Regression**
- **Decision Tree Regression**

After evaluation, **Decision Tree Regression performed better** than Linear Regression
in capturing non-linear patterns in sales data.

---

## 📈 Model Evaluation
- Compared actual vs predicted sales using line plots
- Evaluated performance using regression metrics such as:
  - MAE
  - RMSE
  - R² Score

---

## 📊 Results
- The model successfully captured seasonal trends.
- Predictions followed the overall sales pattern with reasonable accuracy.
- Decision Tree showed better performance in handling fluctuations.

---

## 🚀 Future Improvements
- Apply advanced models like **XGBoost** or **LightGBM**
- Use **time-aware validation** instead of random train-test split
- Perform **seasonal decomposition** for deeper analysis
- Hyperparameter tuning for better performance

---

## 🧰 Tools & Libraries
- Python
- Pandas
- XGBoost
- LightGBM
- Matplotlib
- Scikit-learn

---

## 👩‍💻 Author
**Malak Sherif**
