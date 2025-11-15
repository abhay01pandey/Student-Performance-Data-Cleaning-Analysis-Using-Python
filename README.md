# Student-Performance-Data-Cleaning-Analysis-Using-Python
This project focuses on cleaning and analyzing a small student performance dataset using Python. The goal is to fix inconsistent data formats, handle missing values, correct date formats, standardize text fields, and prepare the dataset for further analysis or visualization.

# Dataset & Tools Used

Dataset

A students_data.csv file containing:

Student demographic details

Subject wise scores

Enrollment dates

Remarks

The dataset includes intentional issues (duplicates, mixed date formats, inconsistent casing, missing values) to simulate real-world data cleaning.

Tools & Libraries

Python

Pandas

Jupyter Notebook

# Workflow

Data Loading

Loaded the CSV file into a Pandas DataFrame

Data Cleaning

Removed duplicate entries

Handled missing numeric values using mean imputation

Standardized text fields (names, gender, remarks)

Cleaned inconsistent category values (remarks, grades)

Converted english_score from object → numeric and rounded values

Normalized all date formats and converted to datetime

Ensured consistent datatypes across columns

# Results

After processing:

All categorical fields are standardized

Date formats are unified

Missing and inconsistent values corrected logically

Numeric scores properly typed and cleaned

The dataset is now fully ready for EDA, reporting, or downstream analysis.

This project demonstrates essential data preprocessing — a core skill for any data analyst.
