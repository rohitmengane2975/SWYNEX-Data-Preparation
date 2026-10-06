# SWYNEX Data Preparation – Titanic Dataset

## Project Overview

This project was completed as part of the SWYNEX Data Science Internship.

The objective of this task was to prepare and clean the Titanic dataset for further data analysis and machine learning.

## Dataset

The Titanic dataset contains passenger information such as:

- Passenger class
- Age
- Sex
- Number of siblings/spouses
- Number of parents/children
- Ticket
- Fare
- Embarked port
- Survival status

## Data Preparation

The following data preparation steps were performed:

1. Checked the dataset shape and columns.
2. Checked for missing values.
3. Filled missing Age values using the median.
4. Filled missing Embarked values using the mode.
5. Removed the Cabin column because a large proportion of its values were missing.
6. Checked for duplicate rows.
7. Reviewed the data types.
8. Validated the cleaned dataset.
9. Exported the cleaned dataset as a CSV file.

## Final Dataset

- Original rows: 891
- Original columns: 12
- Final columns: 11
- Missing values after cleaning: 0
- Duplicate rows: 0

## Files

- `SWYNEX_Data_Preparation.ipynb` – Google Colab notebook containing the data preparation process.
- `SWYNEX_Titanic_Cleaned.csv` – Cleaned Titanic dataset.

## Internship

This project was completed as part of the **SWYNEX Technologies Data Science Internship**.
