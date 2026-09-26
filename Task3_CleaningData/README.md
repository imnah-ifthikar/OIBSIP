# Task 3 - Cleaning Data

## Objective
Take a messy student admission dataset and clean it into an analysis-ready dataset, documenting every decision made.

## Tools Used
Python, pandas, numpy, Jupyter Notebook

## Dataset
Student Admission Records (Kaggle) - 157 rows with missing values, duplicates, and invalid negative values.

## Cleaning Steps
1. Checked data quality: nulls, duplicates, dtypes
2. Removed rows with missing Name or Admission Status; filled other missing values using median (numeric) or mode (categorical)
3. Removed 7 duplicate rows
4. Checked text columns for inconsistent formatting (none found)
5. Detected and fixed impossible negative values in Age, Test Score, and High School Percentage using IQR method
6. Verified correct data types
7. Produced before/after summary: 157 to 132 rows, 72 to 0 nulls, 6 to 0 duplicates

## How to Run
1. Clone this repo
2. Open `ImnahIfthikar_Task3.ipynb` in Jupyter Notebook
3. Ensure `student_admission_records.csv` is in the same folder
4. Run all cells
