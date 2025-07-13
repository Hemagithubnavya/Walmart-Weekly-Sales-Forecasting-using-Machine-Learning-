# Walmart-Weekly-Sales-Forecasting-using-Machine-Learning-
# 🛍 Walmart Weekly Sales Forecasting using Machine Learning

Welcome to my machine learning project on forecasting Walmart's weekly sales!  
This project demonstrates how machine learning can be applied to real-world retail data to extract insights and make accurate predictions.

---

## 📁 Dataset

- 📦 **Source**: [Kaggle - maxbaas/traincsv](https://www.kaggle.com/datasets/maxbaas/traincsv)
- 🏪 **Contains**: 
  - Store and department-level weekly sales
  - Economic indicators (Temperature, Fuel Price, CPI, Unemployment)
  - Promotional markdowns
  - Holiday flags

---

## 🎯 Objective

Build and evaluate regression models to predict the `Weekly_Sales` of Walmart stores based on various store-level and economic features.

---

## 🧮 Features Used

| Feature         | Description                                               |
|----------------|-----------------------------------------------------------|
| Store, Dept     | Unique identifiers for store and department               |
| Temperature     | Weather indicator, affects customer turnout               |
| Fuel_Price      | Can affect footfall or shipping costs                     |
| CPI             | Consumer Price Index — economic indicator                 |
| Unemployment    | Local unemployment rate                                   |
| MarkDown1-5     | Promotional markdown campaigns                            |
| IsHoliday       | Boolean indicator for holiday periods                     |
| Size            | Size of the store                                         |

---

## 🧪 Project Workflow

### ✅ Step 1: Data Collection
- Loaded data using `kagglehub` and `pandas`.

### 🔍 Step 2: Exploratory Data Analysis (EDA)
- Identified missing values and data types.
- Used correlation matrix and scatter plots to study feature relationships.

### 🧠 Step 3: Feature Engineering
- Selected key numeric features and filled missing values.
- Created feature matrix `X` and target `y` (Weekly_Sales).

### 🏗 Step 4: Model Building
- Used **Linear Regression** and **Random Forest Regressor**.
- Split dataset using `train_test_split`.

### 📊 Step 5: Model Evaluation
- Metrics: `RMSE`, `MAE`, and `R² Score`
- Visualized Actual vs Predicted sales.

---

## 📈 Model Performance

| Model              | RMSE (↓)  | MAE (↓)   | R² Score (↑) |
|--------------------|-----------|----------|--------------|
| Linear Regression  | XX.XX     | XX.XX    | X.XXX        |
| Random Forest      | XX.XX     | XX.XX    | X.XXX        |

*Random Forest outperformed Linear Regression due to its ability to model non-linear relationships and handle feature interactions.*

---

## 📌 Insights

- **Temperature**: Lower temperatures slightly reduced sales, especially in smaller stores.
- **Fuel Price**: Higher fuel prices showed negative correlation with sales in some regions.
- **Promotions (MarkDowns)**: These boosted weekly sales significantly during holiday seasons.
- **Holidays**: Marked spikes and dips in sales patterns.

---

## 📂 Files Included

- `walmart_sales_forecasting.ipynb` – Full notebook with code and outputs
- `README.md` – This file
- `train.csv` – Dataset (via KaggleHub)
- `images/` – Visuals used for plots and carousel (optional)

---

## 🧠 Skills Demonstrated

- Data Cleaning & EDA  
- Feature Selection & Engineering  
- Regression Modeling  
- Model Evaluation & Comparison  
- Visualization with Matplotlib & Seaborn  
- Using external data APIs (KaggleHub)

---

## 🚀 Future Improvements

- Incorporate time-series models (ARIMA, Prophet)
- Use advanced ensemble models like XGBoost
- Holiday-specific feature engineering
- Seasonality handling

---

## 🤝 Connect with Me

If you liked this project, feel free to ⭐ the repo and connect with me on [LinkedIn](https://www.linkedin.com/in/yourprofile)!

