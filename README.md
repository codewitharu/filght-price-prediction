# ✈️ Flight Booking Price Prediction

## 📌 Overview
This project predicts **flight ticket prices** using machine learning models. It combines **Exploratory Data Analysis (EDA)**, **feature engineering**, and **model comparison** to understand the factors influencing flight prices and identify the best-performing algorithm.  

The project explores how variables like **airline, travel class, source city, flight duration, and days left before departure** affect ticket prices. Multiple regression models are implemented and compared to determine the most effective approach for prediction.

---

## 🚀 Features
- Data preprocessing (handling missing values, feature encoding, outlier treatment)
- Exploratory Data Analysis (EDA) with insightful visualizations
- Implementation of multiple regression algorithms:
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
  - XGBoost Regressor  
- Model evaluation using **R² Score, MAE, and RMSE**
- Visualization of **actual vs. predicted price distributions**
- Final comparison of models to select the best one

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Statsmodels  
- **Environment:** Jupyter Notebook  

---

## 📊 Dataset
The dataset contains flight booking details such as:  
1 airline 
2 flight 
3 source_city 
4 departure_time 
5 stops 
6 arrival_time 
7 destination_city 
t 8 class 
9 duration 
10 days_left 
11 price 

➡️ Data preprocessing included feature extraction (day, month, duration hours), encoding categorical variables, and handling outliers.

---

## 🔍 Exploratory Data Analysis
Some insights uncovered during EDA:
- Ticket prices increase as the departure date approaches.  
- Business class fares are significantly higher than economy.  
- Duration and distance strongly influence ticket prices.  
- Airlines have different pricing strategies, visible in average price comparisons.  

---

## 🤖 Machine Learning Models
The following models were implemented and compared:
1. **Linear Regression** – baseline model, interpretable but limited in capturing non-linearity.  
2. **Decision Tree Regressor** – captures non-linear patterns but prone to overfitting.  
3. **Random Forest Regressor** – ensemble of trees, more robust and accurate.  
4. **XGBoost Regressor** – gradient boosting model, efficient and highly accurate.  

📈 **Results:**  
- Linear Regression underperformed compared to tree-based models.  
- Decision Tree, Random Forest, and XGBoost achieved **R² ≈ 0.96**, with better prediction alignment to actual values.  

---

## ⚡ How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/codewitharu/flight-price-prediction.git
   cd flight-price-prediction

