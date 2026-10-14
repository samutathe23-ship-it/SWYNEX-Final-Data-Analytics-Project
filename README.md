# SWYNEX Final Data Analytics Project
## Titanic Survival Analysis — End-to-End Case Study

### 1. Project Overview
This project demonstrates the end-to-end data analytics process using the Titanic passenger dataset. It combines data cleaning, exploratory data analysis (EDA), data visualization, and an interactive Power BI dashboard.

This project was completed as part of the SWYNEX Data Analyst Internship.

### 2. Problem Statement
The objective of this project is to analyze Titanic passenger data to understand survival patterns and identify how passenger characteristics, such as gender, passenger class, age, and fare, relate to survival outcomes.

The analysis aims to transform raw data into meaningful insights using Python, Pandas, and Power BI.

### 3. Dataset Information
The Titanic dataset contains information about passengers aboard the Titanic, including:

- PassengerId
- Survived
- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked
- Cabin

The dataset contains 891 passenger records and 12 columns in the original dataset.

### 4. Tools and Technologies
- Python
- Pandas
- Jupyter Notebook / Google Colab
- Matplotlib and Seaborn
- Microsoft Power BI Desktop
- DAX
- GitHub

### 5. Data Cleaning and Preparation
The dataset was inspected to identify missing values and duplicate records.

The following cleaning steps were performed:
- Filled missing Age values using the median.
- Replaced missing Cabin values with "Unknown".
- Filled missing Embarked values using the mode.
- Checked the dataset for duplicate records.
- Exported the cleaned dataset as a CSV file.

Output: `titanic_cleaned.csv`

### 6. Exploratory Data Analysis
Exploratory analysis was performed to understand passenger survival patterns.

The analysis examined:
- Overall survival rate.
- Survival rate by gender.
- Survival rate by passenger class.
- Passenger age distribution.
- Passenger fare distribution.
- Relationships between passenger characteristics and survival.

### 7. Interactive Power BI Dashboard
An interactive dashboard was developed using Microsoft Power BI.

Dashboard components:
- Total Passengers KPI
- Survivors KPI
- Survival Rate KPI
- Average Fare KPI
- Survival rate by gender
- Survival rate by passenger class
- Passenger age distribution
- Passenger fare distribution
- Interactive slicers for Sex, Pclass, and Embarked

The dashboard allows users to explore the data using interactive filters.

### 8. Key Findings
- Total passengers analyzed: 891
- Total survivors: 342
- Overall survival rate: approximately 38.4%
- Female passengers had a substantially higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.

These findings describe patterns in the dataset and do not establish that any single characteristic caused survival.

### 9. Conclusion
This project demonstrates how data analytics can transform a raw dataset into meaningful information through cleaning, exploration, visualization, and dashboard development.

The project provided practical experience in Python, Pandas, exploratory data analysis, Power BI, DAX, and communicating analytical findings.

### 10. Project Files
- `SWYNEX_Data_Cleaning_Preparation.ipynb` — Data cleaning notebook
- `SWYNEX_Exploratory_Data_Analysis.ipynb` — Exploratory analysis notebook
- `SWYNEX_Interactive_Dashboard.pbix` — Interactive Power BI dashboard
- `titanic_cleaned.csv` — Cleaned dataset

### 11. Internship
Completed as Task 4 of the SWYNEX Data Analyst Internship.
