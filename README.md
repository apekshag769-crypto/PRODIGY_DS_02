# PRODIGY_DS_02 - Titanic Data Cleaning and Exploratory Data Analysis

## Overview

This project was completed as part of the Prodigy InfoTech Data Science Internship.

The objective of this task is to perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset to explore relationships between different passenger characteristics and survival outcomes.

## Dataset

The Titanic dataset contains information about passengers, including:

- Passenger Class
- Sex
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Fare
- Cabin
- Embarkation Port
- Survival Status

## Data Cleaning

The following preprocessing steps were performed:

- Missing Age values were replaced using the median age.
- Missing Embarked values were replaced using the most frequent value.
- The Cabin column was removed because of a large number of missing values.
- The cleaned dataset was checked for remaining missing values.

## Exploratory Data Analysis

The following analyses were performed:

- Overall survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution and survival
- Fare distribution and survival
- Survival by embarkation port
- Survival by family size
- Correlation analysis

## Key Findings

- The overall survival rate was approximately 38.38%.
- Female passengers had a considerably higher survival rate than male passengers.
- First-class passengers generally had higher survival rates than second- and third-class passengers.
- Third-class passengers experienced the highest number of deaths.
- Age showed different survival patterns across age groups.
- Passengers paying higher fares generally had better survival outcomes.
- Survival rates varied across embarkation ports.
- Family size also showed a relationship with survival.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Files

- `PRODIGY_DS_02_Titanic_EDA.ipynb` — Complete analysis notebook
- `cleaned_titanic.csv` — Cleaned Titanic dataset
- `README.md` — Project documentation

## Conclusion

The analysis demonstrates how data cleaning and exploratory data analysis can be used to identify meaningful patterns in real-world data. Gender, passenger class, age, fare, embarkation port, and family size showed relationships with Titanic passenger survival.
