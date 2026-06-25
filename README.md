# 🚢 Titanic Data Cleaning & Visualization Project

## 📌 Project Overview

This project focuses on cleaning, preprocessing, analyzing, and visualizing the Titanic dataset using Python. The goal is to transform raw data into meaningful insights through Data Cleaning, Exploratory Data Analysis (EDA), and Data Visualization techniques.

---

## 🎯 Objectives

* Handle missing values
* Remove duplicate records
* Detect and remove outliers
* Perform Exploratory Data Analysis (EDA)
* Generate visual insights using charts and graphs
* Create a cleaned dataset for further analysis

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Kaggle Notebook

---

## 📊 Dataset

**Titanic - Machine Learning from Disaster**

Dataset Source:
https://www.kaggle.com/competitions/titanic/data

---

## 🧹 Data Cleaning Steps

### Missing Value Treatment

* Filled missing values in Age using Median.
* Filled missing values in Embarked using Mode.
* Removed Cabin column due to excessive missing values.

### Duplicate Removal

* Checked and removed duplicate records.

### Outlier Detection

* Applied IQR (Interquartile Range) method on Fare column.

---

## 📈 Visualizations

* Survival Distribution
* Gender Distribution
* Age Distribution
* Passenger Class Distribution
* Survival by Gender
* Fare Boxplot
* Correlation Heatmap

---

## 🔍 Key Insights

* Female passengers had a significantly higher survival rate.
* Most passengers belonged to Passenger Class 3.
* Adults constituted the majority of passengers.
* Passenger Class had a strong influence on survival chances.
* Fare distribution contained outliers that were handled during preprocessing.

---

## 📂 Project Structure

Titanic-Data-Cleaning-Visualization/

├── dataset/

│ └── cleaned_titanic.csv

├── notebook/

│ └── Titanic_Data_Cleaning.ipynb

├── README.md

└── requirements.txt

---

## ▶️ How to Run

1. Clone the repository.
2. Install dependencies.

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the Jupyter Notebook or Python script.

---

## 👨‍💻 Author

Harshit Saini

---

## ⭐ Project Outcome

Successfully cleaned, analyzed, and visualized the Titanic dataset while gaining practical experience in Data Cleaning, Data Analysis, and Data Visualization using Python.
