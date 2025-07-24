# Calories_burnt_PredictionModel
🔍 Calories Burnt Prediction using XGBoost  This project builds a machine learning model to predict the number of calories burnt based on personal and exercise-related features using the XGBoost algorithm.



# 🔥 Calories Burnt Prediction using XGBoost

This project focuses on building a machine learning model to **predict the number of calories burnt** during physical activities based on personal and activity features using the **XGBoost algorithm**. The model was trained on a merged dataset containing individual characteristics and exercise details.

---

## 📂 Dataset

The project uses two datasets:

* `exercise.csv` – Contains details about activity performed (e.g., duration, heart rate).
* `calories.csv` – Contains the corresponding calories burnt.

These datasets were merged based on a common column to form the final input for model training.

---

## 🎯 Objective

To build a **regression model** that accurately predicts the number of calories burnt based on input features such as:

* Gender
* Age
* Height
* Weight
* Duration of activity
* Heart rate
* Body temperature

---

## ⚙️ Model Used

* **XGBoost Regressor**
* Hyperparameter tuning with `RandomizedSearchCV` for optimal performance.

---

## 📊 Performance

* Achieved an accuracy (R² Score) of **\~99%**
* Explored several model improvement techniques like:

  * Feature engineering
  * Outlier removal using boxplots
  * Correlation analysis
  * Hyperparameter optimization

---

## 📈 Exploratory Data Analysis

* Used `seaborn` and `matplotlib` for visualization
* Visuals included:

  * Boxplots for outlier detection
  * Correlation heatmaps
  * Distribution plots (`histplot`, `displot`) for feature analysis

