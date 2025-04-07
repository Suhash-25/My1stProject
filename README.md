# My1stMLProject
 Taxi-fare prediciton project.

 # 🚖 Taxi Fare Prediction using Machine Learning

Welcome to my very first Machine Learning project! 🎉  
In this project, I built a regression model that predicts taxi fares based on pickup and drop-off details, using the NYC Taxi Fare dataset. This project showcases the end-to-end ML pipeline from data preprocessing to model training and evaluation.

---

## 📌 Project Overview

This project aims to solve a real-world problem: **predicting the taxi fare amount** based on historical trip data including pickup/dropoff locations, date-time, and passenger count.

✅ Type: Regression  
✅ Dataset: NYC Taxi Fare Dataset  
✅ Tools Used: Python, Pandas, Scikit-learn, Matplotlib, Jupyter Notebook

---

## 🔍 Problem Statement

Given the pickup and dropoff locations, timestamp, and number of passengers, can we accurately predict how much a taxi ride should cost in New York City?

This is valuable for:

- Helping passengers avoid being overcharged
- Optimizing pricing models for taxi companies
- Real-time fare estimation in ride-hailing apps

---

## 🧠 Features Used

- Pickup datetime
- Pickup and dropoff latitude/longitude
- Passenger count
- Distance (calculated using Haversine formula)
- Time-based features: hour, day of week, month, etc.

---

## 🛠️ Tech Stack

- **Python** – Core programming language
- **Pandas & NumPy** – Data handling
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – ML model development and evaluation

---

## 📊 Models Tried

| Model                 | RMSE (Root Mean Squared Error) |
|----------------------|-------------------------------|
| Linear Regression     | ✅ Baseline model             |
| Random Forest Regressor | 🧠 Best performance        |
| Gradient Boosting     | 🔍 Close second               |

---

## 🧪 Results

The Random Forest model performed the best, showing robust predictions without overfitting. The features like distance and pickup hour had the highest impact on fare prediction.
