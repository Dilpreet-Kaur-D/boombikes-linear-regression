# 🚲 BoomBikes Bike Demand Prediction using Multiple Linear Regression

## 📖 Project Overview

BoomBikes, a US-based bike-sharing company, experienced a significant decline in revenue during the COVID-19 pandemic. As business operations begin to recover, the company wants to understand the key factors influencing daily bike rental demand so it can make informed business decisions and maximize future revenue.

This project develops a **Multiple Linear Regression** model to identify the variables that significantly affect bike demand and accurately predict the total number of bike rentals.

---

## 🎯 Business Objective

The primary objective of this project is to:

* Identify the significant factors affecting bike demand.
* Build a predictive Multiple Linear Regression model.
* Understand how different environmental and seasonal variables influence bike rentals.
* Provide actionable business recommendations to improve demand and profitability.

---

## 📂 Dataset

The dataset contains daily bike rental information along with weather, seasonal, and calendar-related variables.

Some important features include:

* Season
* Year
* Month
* Holiday
* Working Day
* Weather Situation
* Temperature
* Humidity
* Windspeed
* Casual Users
* Registered Users
* Total Bike Rentals (`cnt`)

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels

---

## 📊 Project Workflow

### 1. Data Understanding

* Dataset exploration
* Data types
* Missing value analysis
* Statistical summary

### 2. Data Cleaning & Preprocessing

* Removing unnecessary variables
* Encoding categorical variables
* Feature scaling
* Train-test split

### 3. Exploratory Data Analysis (EDA)

* Univariate Analysis
* Bivariate Analysis
* Correlation Analysis
* Visualization using Matplotlib & Seaborn

### 4. Feature Engineering

* Dummy Variable Creation
* Recursive Feature Elimination (RFE)
* Multicollinearity check using VIF

### 5. Model Building

* Multiple Linear Regression
* Model fitting using Statsmodels
* Feature selection
* Residual analysis

### 6. Model Evaluation

* R² Score
* Adjusted R² Score
* Residual diagnostics
* Prediction on test dataset

---

# 📈 Model Performance

### Training Performance

| Metric      |     Score |
| ----------- | --------: |
| R² Score    | **0.816** |
| Adjusted R² | **0.813** |

### Testing Performance

| Metric      |      Score |
| ----------- | ---------: |
| R² Score    |  **0.799** |
| Adjusted R² | **0.7885** |

### Generalization

* Difference in R²: **2.11%**
* Difference in Adjusted R²: **3.05%**

The small difference between the training and testing performance indicates that the model generalizes well and does not exhibit significant overfitting.

---

# 🔍 Key Findings

* **Temperature** is the most influential positive predictor of bike rentals.
* Bike demand increased in **2019** compared with **2018**.
* Variables such as **Spring**, **Summer**, **July**, **November**, **Holiday**, **Misty Weather**, and **Cloudy Weather** show a negative relationship with bike demand.
* The model explains approximately **80%** of the variation in daily bike rentals.

---

# 💼 Business Recommendations

Based on the model results, BoomBikes can:

* Increase bike availability during periods of favorable temperatures.
* Plan inventory and operations to meet higher demand trends.
* Launch promotional campaigns during **Spring**, **Summer**, **July**, **November**, and **holiday periods** to boost rentals.
* Offer weather-based discounts during misty or cloudy conditions to encourage customer engagement.
* Use demand forecasts for better fleet management and business planning.

---

## 📁 Repository Structure

```text
├── BOOMBIKR_LIN_MODEL_DK.ipynb
├──  day.csv
├── README.md

```

---

## 🎯 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Multiple Linear Regression
* Feature Selection (RFE)
* Multicollinearity Analysis (VIF)
* Residual Analysis
* Model Evaluation
* Business Insight Generation
* Data Visualization

---

## 🚀 How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Run the notebook sequentially to reproduce the analysis and model.

---

## 👩‍💻 Author

**Dilpreet Kaur**

This project is part of my Data Analytics and Machine Learning portfolio, demonstrating an end-to-end workflow for solving a real-world business problem using Multiple Linear Regression.

---

## ⭐ Acknowledgements

This project was completed for educational purposes to understand the complete machine learning workflow, from data preprocessing and exploratory analysis to predictive modeling and business recommendations.

If you found this project helpful, consider giving it a ⭐ on GitHub!
