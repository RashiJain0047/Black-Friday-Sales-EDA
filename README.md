# 🛍️ Black Friday Sales Analysis & Feature Engineering

## 📌 Project Overview

This project analyzes the **Black Friday Sales Dataset** to understand customer purchasing behavior and prepare the data for machine learning. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, handling missing values, encoding categorical variables, and feature scaling.

The objective is to identify key factors influencing customer purchase amounts and build a clean dataset suitable for predictive modeling.

---

## 🎯 Objectives

* Perform data cleaning and preprocessing.
* Handle missing values effectively.
* Encode categorical features for machine learning.
* Explore customer purchasing behavior through visualizations.
* Engineer features for model readiness.
* Prepare the dataset for purchase prediction.

---

## 📂 Dataset Information

The dataset contains customer demographic details, product information, and purchase amounts during Black Friday sales.

### Features

| Feature                    | Description                         |
| -------------------------- | ----------------------------------- |
| User_ID                    | Unique identifier for each customer |
| Product_ID                 | Unique identifier for each product  |
| Gender                     | Customer gender                     |
| Age                        | Customer age group                  |
| Occupation                 | Occupation code                     |
| City_Category              | Category of customer's city         |
| Stay_In_Current_City_Years | Years stayed in current city        |
| Marital_Status             | Marital status                      |
| Product_Category_1         | Primary product category            |
| Product_Category_2         | Secondary product category          |
| Product_Category_3         | Tertiary product category           |
| Purchase                   | Purchase amount (Target Variable)   |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset overview
* Data type inspection
* Missing value analysis
* Statistical summary
* Customer demographics analysis
* Purchase amount distribution
* Age vs Purchase
* Gender vs Purchase
* Occupation vs Purchase
* Product Category vs Purchase
* City Category analysis

---

## ⚙️ Feature Engineering

The preprocessing pipeline includes:

* Removed unnecessary identifier columns
* Gender Encoding
* Age Encoding
* One-Hot Encoding for City Category
* Handling missing values using Mode
* Converting data types
* Feature Scaling using StandardScaler
* Train-Test Split for model preparation

---

## 📈 Visualizations

The project includes visualizations such as:

* Purchase Distribution
* Age vs Purchase
* Occupation vs Purchase
* Product Category Analysis
* Gender-wise Purchase Analysis

---

## 🔍 Key Insights

* Customers aged **26–35 years** contribute significantly to total purchases.
* Purchasing behavior varies across occupations.
* Product Category 1 has the highest contribution to overall sales.
* Gender and city category influence purchasing patterns.
* Feature engineering significantly improves data quality for machine learning.

---

## 🤖 Machine Learning Preparation

The dataset was prepared for predictive modeling by:

* Separating features (`X`) and target (`y`)
* Performing train-test split
* Applying feature scaling using `StandardScaler`

This processed dataset can be used with regression algorithms such as:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor


---

## 🚀 Future Improvements

* Build multiple regression models
* Hyperparameter tuning
* Feature importance analysis
* Model evaluation using RMSE, MAE, and R² Score
* Interactive dashboard using Power BI or Tableau

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Missing Value Treatment
* Categorical Encoding
* Feature Scaling
* Data Preparation for Machine Learning
* Business Insight Generation

---

## ⭐ If you found this project useful, consider giving it a star!
