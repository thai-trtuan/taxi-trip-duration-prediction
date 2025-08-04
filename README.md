# 🚕 NYC Taxi Trip Duration Prediction

This project aims to predict the duration of taxi trips in New York City using real-world pickup and dropoff data. The dataset was sourced from Kaggle and contains features such as passenger count, trip distance, pickup datetime, and geolocation coordinates.

## 📊 Objective

- Understand how various factors affect trip duration
- Perform exploratory data analysis (EDA)
- Train and evaluate regression models

## 🗃️ Dataset

- 📍 Source: [Kaggle - NYC Taxi Trip Duration](https://www.kaggle.com/competitions/nyc-taxi-trip-duration)
- 📦 145,864 rows and 11 features
- 🧾 Key features:
  - `pickup_datetime`
  - `passenger_count`
  - `pickup_longitude`, `pickup_latitude`
  - `dropoff_longitude`, `dropoff_latitude`
  - `store_and_fwd_flag`

## ⚙️ Technologies Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 🤖 Models Implemented

| Model            | RMSE       | R² Score   |
|------------------|------------|------------|
| Linear Regression| 492.78     | 0.1474     |
| Decision Tree    | 444.65     | 0.2739     |
| Random Forest    | **429.35** | **0.3133** ✅ |

📌 **Random Forest** performed best among the three models.

## 📈 Evaluation Metrics

- RMSE (Root Mean Squared Error)
- R² Score
- Visual comparison of predicted vs actual trip duration

## ▶️ Run the Project

```bash
python train_model.py
