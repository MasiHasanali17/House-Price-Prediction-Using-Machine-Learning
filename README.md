# Gurgaon House Price Prediction (Machine Learning)

## 📌 Project Overview

This project predicts house prices using Machine Learning.
The dataset is processed using a Scikit-learn preprocessing pipeline and a Random Forest Regressor is trained to estimate the **median house value**.

---

## 📊 Dataset

The dataset used in this project is **housing.csv** which contains housing-related features such as:

* longitude
* latitude
* housing_median_age
* total_rooms
* total_bedrooms
* population
* households
* median_income
* ocean_proximity

The target variable predicted by the model is **median_house_value**.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib

---

## 🧠 Machine Learning Workflow

1. Load the dataset
2. Create a stratified train/test split based on income category
3. Build a preprocessing pipeline:

   * Handle missing values using **SimpleImputer**
   * Scale numeric features using **StandardScaler**
   * Encode categorical features using **OneHotEncoder**
4. Train the model using **RandomForestRegressor**
5. Save the trained model and preprocessing pipeline
6. Load the model to make predictions on new data

---

## 🚀 How to Run the Project

### Install dependencies

```
pip install -r requirements.txt
```

### Run the script

```
python main.py
```

### Output

Predicted house prices will be saved in **output.csv**.

---

## 📈 Models Tested

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

Random Forest provided the best performance for this dataset.

---

## 🎯 Project Goal

The goal of this project is to demonstrate an **end-to-end machine learning workflow**, including data preprocessing, model training, evaluation, and prediction using a machine learning pipeline.
