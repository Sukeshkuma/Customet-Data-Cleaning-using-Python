# Customer Data Cleaning and Preprocessing using Python

## 📌 Project Overview

This project demonstrates the complete data cleaning and preprocessing workflow using **Python** and **Jupyter Notebook**. The objective is to transform raw customer data into a clean and reliable dataset that is ready for analysis or machine learning.

The project covers essential data preprocessing techniques, including handling missing values, correcting data types, removing duplicates, detecting and eliminating outliers, and performing statistical analysis using Z-Score.

---

## 🎯 Project Objectives

- Load and analyze customer dataset
- Handle missing values using the median
- Correct data types for accurate analysis
- Remove duplicate records
- Detect and remove outliers
- Visualize data distribution using box plots
- Calculate Z-Scores for outlier detection

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- SciPy

---

## 📂 Project Workflow

### 1. Import Dataset
- Loaded the customer dataset into a Pandas DataFrame.
- Performed initial data exploration.

### 2. Handle Missing Values
- Identified null values.
- Replaced missing numerical values with the **median** of the respective columns.

### 3. Data Type Conversion
- Corrected incorrect data types.
- Converted columns into appropriate formats (integer, float, datetime, etc.).

### 4. Remove Duplicate Records
- Identified duplicate rows.
- Removed duplicate entries to improve data quality.

### 5. Outlier Detection and Removal
- Detected outliers using statistical methods.
- Removed extreme values to improve dataset consistency.

### 6. Data Visualization
- Generated **Box Plots** to visualize the distribution of numerical features and identify outliers.

### 7. Z-Score Analysis
- Calculated Z-Scores using SciPy.
- Used Z-Score values to identify abnormal observations.

---

## 📊 Key Features

- Data Cleaning
- Missing Value Treatment
- Duplicate Removal
- Outlier Detection
- Statistical Analysis
- Data Visualization
- Z-Score Calculation

---

## 📁 Project Structure

```
Customer-Data-Cleaning/
│
├── Data_Cleaning_Process.ipynb
├── Raw_Customer_Data.csv
├── Cleaned_Customer_Dataset.csv
├── README.md
└── boxplot.png

---

## 🚀 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from scipy.stats import zscore
```

---

## 📈 Output

After completing the preprocessing steps:

- Clean dataset generated
- Missing values handled
- Duplicate records removed
- Outliers detected and removed
- Box plots created
- Z-Score calculated for numerical columns

---

## 💡 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Cleaning Techniques
- Exploratory Data Analysis (EDA)
- Statistical Methods
- Data Visualization
- Python Programming
- Pandas Data Manipulation
- NumPy Operations
- SciPy Statistical Functions

---

## 🔮 Future Enhancements

- Automate the data cleaning pipeline
- Implement advanced outlier detection methods
- Build an interactive dashboard using Plotly or Power BI
- Apply machine learning models on the cleaned dataset

---

## 👨‍💻 Author

**Sukesh Kumar Sahoo**

Production Support Analyst | Python | SQL | Data Analytics | Data Science Enthusiast

LinkedIn: **https://www.linkedin.com/in/sukeshkumar1994/**

---

## ⭐ If you found this project helpful

Please consider giving this repository a **⭐ Star**.
