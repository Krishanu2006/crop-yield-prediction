# 🌾 Crop Yield Prediction using Machine Learning

## 📌 Project Overview

Crop yield prediction plays a crucial role in modern agriculture by helping farmers, policymakers, and agricultural organizations make data-driven decisions. This project leverages Machine Learning techniques to predict crop yield based on various environmental, geographical, and agricultural factors.

The objective is to build an accurate predictive model that can estimate crop yield and identify the most influential factors affecting agricultural productivity.

---

## 🎯 Objectives

* Predict crop yield using historical agricultural data.
* Compare multiple machine learning algorithms.
* Identify the most influential factors affecting crop production.
* Provide insights that can support agricultural planning and resource management.

---

## 📊 Dataset Features

The dataset contains a combination of numerical and categorical features related to agricultural production.

### Numerical Features

* Annual Rainfall
* Fertilizer Usage
* Pesticide Usage
* Cultivated Area

### Categorical Features

* Crop Type
* State/Region

### Target Variable

* Yield

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

1. Data Cleaning

   * Checked for missing values.
   * Removed inconsistencies and duplicate records.

2. Feature Engineering

   * Separated numerical and categorical features.
   * Identified the target variable (`Yield`).

3. Encoding

   * Applied One-Hot Encoding to categorical variables.

4. Train-Test Split

   * Divided data into training and testing sets for unbiased evaluation.

---

## 🔍 Exploratory Data Analysis (EDA)

Several exploratory analyses were conducted to understand the dataset:

* Distribution of crop yields.
* Relationship between rainfall and yield.
* Impact of fertilizer and pesticide usage.
* Crop-wise and state-wise yield comparisons.
* Correlation analysis among numerical features.

### Key Findings

* Yield exhibits complex non-linear relationships with rainfall and other environmental variables.
* Crop type and geographical location significantly influence production.
* Fertilizer and pesticide usage contribute substantially to yield variations.

---

## 🤖 Machine Learning Models Evaluated

Three regression models were trained and compared:

### 1. Linear Regression

A baseline model used to evaluate linear relationships between features and crop yield.

### 2. Decision Tree Regressor

A tree-based model capable of capturing non-linear patterns in the dataset.

### 3. Random Forest Regressor

An ensemble learning algorithm that combines multiple decision trees to improve predictive performance and reduce overfitting.

---

## 📈 Model Evaluation Metrics

The models were evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

## 🏆 Best Performing Model

### Random Forest Regressor

The Random Forest Regressor achieved:

* Highest R² Score
* Lowest MAE
* Lowest MSE
* Lowest RMSE

This indicates superior predictive performance and better generalization compared to Linear Regression and Decision Tree Regressor.

---

## 💡 Why Random Forest Performed Better

The Random Forest Regressor outperformed the other models due to several advantages:

### Ensemble Learning

Random Forest combines predictions from multiple decision trees, reducing overfitting and improving robustness.

### Reduced Variance

By averaging the outputs of numerous trees, the model minimizes prediction variance while maintaining accuracy.

### Capturing Non-Linear Relationships

The algorithm effectively models complex interactions between environmental and agricultural variables.

### Robustness to Outliers

Individual outliers have less influence on the overall prediction because the model aggregates multiple trees.

### High-Dimensional Data Handling

After One-Hot Encoding, the dataset contained many features. Random Forest handles such high-dimensional datasets efficiently.

---

## 🔑 Feature Importance Analysis

Feature importance analysis was performed using the Random Forest model to identify the variables contributing most to crop yield prediction.

Important features include:

* Crop Type
* State/Region
* Fertilizer Usage
* Pesticide Usage
* Cultivated Area
* Annual Rainfall

Understanding these factors can help optimize agricultural practices and improve productivity.

---

## 📋 Results Summary

| Model                   | Performance |
| ----------------------- | ----------- |
| Linear Regression       | Moderate    |
| Decision Tree Regressor | Good        |
| Random Forest Regressor | Best        |

### Major Findings

* Random Forest achieved the highest predictive accuracy.
* Agricultural productivity depends on a combination of environmental and management factors.
* Ensemble methods are highly effective for crop yield prediction problems.

---

## 🌍 Real-World Applications

This system can be used by:

### Farmers

* Estimate expected crop production.
* Plan fertilizer and pesticide usage.

### Agricultural Agencies

* Develop region-specific agricultural strategies.
* Improve food security planning.

### Policymakers

* Make informed decisions regarding agricultural resource allocation.

### Researchers

* Study factors influencing agricultural productivity.

---

## 🚀 Future Improvements

* Integrate real-time weather data.
* Incorporate soil quality information.
* Deploy the model as a web application.
* Use advanced ensemble methods such as XGBoost and LightGBM.
* Explore deep learning approaches for time-series agricultural forecasting.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📌 Conclusion

This project demonstrates the effectiveness of Machine Learning in agricultural analytics. Among the evaluated models, the Random Forest Regressor delivered the best performance, providing accurate crop yield predictions and valuable insights into the factors affecting agricultural productivity.

The findings highlight the potential of data-driven agriculture in improving decision-making, optimizing resource utilization, and supporting sustainable food production.
