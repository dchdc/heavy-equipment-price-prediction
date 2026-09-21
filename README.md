# Heavy Equipment Selling Price Prediction

##  Project Overview

This project develops a machine learning solution to predict the selling price of heavy equipment using historical transaction data.

The project focuses on applying an end-to-end data science workflow, from data exploration and preprocessing to feature engineering, model development, hyperparameter tuning, and model evaluation.

The target variable is **TargetValue**, and model performance is evaluated using **Root Mean Squared Logarithmic Error (RMSLE)**.

---

##  Objective

The objective is to build a machine learning model that can accurately estimate the selling price of heavy equipment based on characteristics such as:

* Equipment specifications
* Manufacture year
* Operational hours
* Product configuration
* Vendor information
* Region
* Equipment category
* Transaction date
* Utilization characteristics

---

##  Project Workflow

### 1. Data Exploration

* Examined dataset structure and dimensions
* Analysed numerical and categorical variables
* Investigated missing values
* Identified duplicate records
* Analysed relationships between features and the target variable

### 2. Data Preprocessing

* Handled missing values
* Removed features with excessive missing data
* Processed numerical and categorical variables
* Cleaned inconsistent values
* Prepared training and test datasets

### 3. Feature Engineering

Created additional features to improve the predictive capability of the models, including:

* Equipment age
* Manufacture year transformations
* Operational usage indicators
* Date-based features
* Encoded categorical variables
* Indicators for missing or available equipment information

### 4. Machine Learning Models

The project explored gradient-boosting based machine learning models, including:

* **XGBoost**
* **LightGBM**
* **CatBoost**

Hyperparameter tuning and cross-validation were used to evaluate different model configurations.

---

##  Evaluation Metric

The competition uses **Root Mean Squared Logarithmic Error (RMSLE)**.

RMSLE is particularly useful for price prediction because it evaluates the relative difference between predicted and actual values and reduces the impact of very large price values.

Lower RMSLE indicates better predictive performance.

##  Results

* Best validation RMSLE: **0.19838**
---

##  Technologies & Skills

### Programming & Data Analysis

* Python
* Pandas
* NumPy

### Machine Learning

* XGBoost
* LightGBM
* Feature Engineering
* Hyperparameter Tuning
* Cross-Validation
* Model Evaluation

### Data Science

* Data Cleaning
* Exploratory Data Analysis
* Missing Value Analysis
* Numerical & Categorical Feature Processing
* Predictive Modelling

---

##  Repository Structure

```text
heavy-equipment-price-prediction/
│
├── README.md
├── heavy_equipment_price_prediction.ipynb
└── data/
    └── README.md
```

> The original competition dataset is not included in this repository. Please refer to the Kaggle datasets from [https://www.kaggle.com/datasets/somyatambi6/heavy-equipment-selling-price-prediction-challenge](https://www.kaggle.com/datasets/somyatambi6/heavy-equipment-selling-price-prediction-challenge/data)

---

##  Key Learning Outcomes

This project provided practical experience in working with a real-world machine learning dataset containing missing values, categorical variables, high-cardinality features, and inconsistencies.

It strengthened my understanding of:

* Preparing real-world data for machine learning
* Designing meaningful features
* Comparing machine learning algorithms
* Tuning model hyperparameters
* Using cross-validation for model evaluation
* Optimising models against a competition metric
* Building an end-to-end machine learning workflow

---

##  Author

**Chitra Madhavan**

Interested in applying Data science and AI techniques to solve real-world problems.
