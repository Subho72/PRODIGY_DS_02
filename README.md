# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic dataset from Kaggle.

The objective of this project is to:
- Clean and preprocess the dataset
- Handle missing values
- Explore relationships between variables
- Identify patterns and trends affecting passenger survival
- Create visualizations and an interactive Tableau dashboard

---

## 📂 Dataset Used

Dataset: Titanic Dataset from Kaggle

🔗 Dataset Link:  
https://www.kaggle.com/c/titanic/data

### Primary File Used for EDA
- train.csv

### Additional Files
- test.csv (used for prediction/testing purposes)
- gender_submission.csv (sample submission file provided by Kaggle)

---

## 🛠️ Technologies & Tools Used

- Python
- VS Code
- Jupyter Notebook
- Tableau
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GitHub

---

## 📊 Data Cleaning Process

The following preprocessing steps were performed:

✅ Checked missing values  
✅ Filled missing Age values using median  
✅ Filled missing Embarked values using mode  
✅ Replaced missing Cabin values with "Unknown"  
✅ Removed duplicate records (if any)

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Survival Count Analysis
- Gender vs Survival Analysis
- Passenger Class vs Survival Analysis
- Age Distribution Analysis
- Fare Analysis
- Correlation Heatmap

---

## 📷 Visualizations Included

- Survival Count Plot
- Gender vs Survival Chart
- Passenger Class vs Survival Chart
- Age Distribution Histogram
- Fare Analysis Chart
- Correlation Heatmap
- Tableau Dashboard

---

## 🔍 Key Insights

- Female passengers had a higher survival rate than male passengers.
- First-class passengers survived more frequently than lower-class passengers.
- Most passengers belonged to the age group of 20–40 years.
- Passenger fare and passenger class influenced survival probability.

---

## 📷 Dashboard Preview

![Dashboard](dashboard.png)


## 📁 Updated Project Structure

```text
Titanic_EDA_Project/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── gender_submission.csv
│   └── cleaned_titanic.csv
│
├── notebooks/
│   └── Titanic_EDA.ipynb
│
├── dashboard/
│   ├── Titanic_EDA_Dashboard.twb
│   └── dashboard.png
│
└── README.md
