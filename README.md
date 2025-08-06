# STATUS:IN PROGRESS
# "45 days CODING challenge"

# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) project using the **Titanic dataset** from Kaggle. The goal is to understand patterns, trends, and key features that influenced passenger survival.

---

✅ Task 2: EDA Steps Followed

# Summary Statistics
- Used `.describe()` to calculate mean, std, min, max, percentiles.
- Used `.isnull().sum()` to check for missing values.

# Visual Analysis (Histograms and Boxplots)
- Created histograms to view distributions (e.g., Age).
- Used boxplots to identify outliers (e.g., Fare).

# Feature Relationships (Correlation)
- Generated a correlation matrix to see numeric relationships.
- Used Seaborn `pairplot` for visualizing interactions between features.

# Pattern & Trend Detection
- Found higher survival rates among:
  - Females
  - 1st Class passengers
  - Young children
- Passengers with higher fares tended to survive more.

# Feature-Level Inference
- `Sex`, `Pclass`, `Fare`, and `Age` were strong indicators of survival.
- `Embarked` value 'S' had the most passengers but lowest survival rate.

---

# libraries
- `pandas`
- `matplotlib`
- `seaborn`

---


1. Clone the repo  
2. Install dependencies (`pip install pandas matplotlib seaborn`)  
3. Run the EDA notebook or script

---



This EDA helps identify important features and potential preprocessing steps for building machine learning models to predict survival.

---

# source:
Dataset: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic)
