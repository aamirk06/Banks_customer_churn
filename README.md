# Bank Customer Churn Analysis

## Overview

This project focuses on analyzing bank customer churn data using Python. The objective is to identify patterns and factors that influence customer attrition, helping banks improve customer retention strategies through data-driven insights.

## Project Objectives

* Understand customer demographics and banking behavior.
* Perform data cleaning and preprocessing.
* Analyze customer churn trends and patterns.
* Identify relationships between features using correlation analysis.
* Create visualizations to support business insights.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset Information

The dataset contains customer information such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary
* Exited (Customer Churn Status)

## Data Analysis Process

### 1. Data Loading

* Imported dataset using Pandas.
* Created a working copy of the dataset.

### 2. Data Cleaning

* Removed unnecessary columns:

  * RowNumber
  * CustomerId
  * Surname
* Checked for missing values.
* Verified data types.

### 3. Exploratory Data Analysis (EDA)

* Examined dataset structure and dimensions.
* Generated descriptive statistics.
* Analyzed categorical and numerical features.
* Explored customer churn distribution.

### 4. Visualization

* Correlation Heatmap
* Distribution Analysis
* Feature Relationship Analysis
* Customer Demographics Insights

## Key Insights

* Customer age has a significant impact on churn behavior.
* Active members are less likely to leave the bank.
* Geography influences customer retention patterns.
* Customers with higher product engagement tend to stay longer.

## Project Structure

```text
Bank_Customer_Churn_Analysis/
│
├── Churn_Modelling.csv
├── Bank_Customer_Churn_Analysis.ipynb
├── README.md
└── images/
```

## Sample Code

```python
import pandas as pd

data = pd.read_csv("Churn_Modelling.csv")
df = data.copy()

df.head()
```

## Future Improvements

* Build machine learning models for churn prediction.
* Compare multiple classification algorithms.
* Develop an interactive dashboard using Power BI.
* Deploy the project as a web application.

## Conclusion

This project demonstrates practical data analysis techniques using Python and highlights the factors that contribute to customer churn in the banking industry. The findings can help organizations make informed decisions to improve customer retention and business performance.

## Author

Aamir Khan

B.Tech Graduate | Aspiring Data Analyst

Skills: Python, SQL, Power BI, Data Analysis, Pandas, NumPy, Matplotlib, Seaborn
