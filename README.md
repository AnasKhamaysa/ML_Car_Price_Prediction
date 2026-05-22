# 🚗 Car Price Prediction System

## 📌 Overview

This project is a Machine Learning-based system developed to predict car prices using different vehicle features such as mileage, engine specifications, fuel type, transmission type, accident history, and more.

The project demonstrates a complete machine learning workflow starting from data preprocessing and feature engineering to model training, evaluation, and visualization.

---

# 📊 Dataset Features

The dataset includes multiple car-related attributes, including:

* Brand
* Model Year
* Mileage
* Fuel Type
* Engine Information
* Transmission
* Accident History
* Clean Title
* Price

---

# ⚙️ Project Workflow

1. Import Libraries
2. Load Data
3. Data Cleaning
4. Feature Engineering
5. Preprocessing (Encoding & Scaling)
6. Train/Test Split
7. Model Training
8. Evaluation
9. Visualization

---

# 🛠️ Data Preprocessing

Several preprocessing steps were applied, including:

* Removing missing values
* Converting price and mileage to numerical values
* Handling outliers
* Encoding categorical variables
* Scaling numerical features
* Log transformation for the target variable

---

# 🔥 Feature Engineering

Additional features were extracted and created to improve model performance, such as:

* Car Age
* Engine Size
* Horsepower
* Electric/Hybrid Features
* Simplified Transmission Categories

---

# 🤖 Models Used

The following machine learning models were trained and evaluated:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

---

# 📈 Evaluation Metrics

The models were evaluated using:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

# 🏆 Final Results

| Model             | Performance        |
| ----------------- | ------------------ |
| Linear Regression | Baseline Model     |
| Random Forest     | Strong Performance |
| XGBoost           | Best Performance   |

XGBoost achieved the best results with the highest R² score and the lowest prediction error.

---

# 📊 Visualizations

The project includes several visualizations, such as:

* Actual vs Predicted Prices
* Model Comparison Charts
* Feature Relationships
* Data Distribution Plots

---

# 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* Google Colab

---

# 🎯 Conclusion

This project highlights the importance of data preprocessing, feature engineering, and model selection in building accurate machine learning systems. Among all tested models, XGBoost delivered the best overall performance for car price prediction.

---

# 👥 Team Project

This project was developed collaboratively as part of a Machine Learning project.
