# Student-Performance-Data-Cleaning-Analysis-Using-Python
This project focuses on cleaning and standardizing a messy student performance dataset containing demographic details, exam scores, enrollment dates, and remarks.  
The original file had multiple real-world data issues: missing values, inconsistent date formats, incorrect categories, mixed casing and duplicated entries.  
The goal was to transform this raw dataset into a reliable, analysis-ready format using Python and Pandas.

# Dataset & Tools Used

### Dataset
The project uses students_data.csv, which includes:
- Student IDs  
- Names  
- Age and gender  
- Subject-wise scores  
- Enrollment dates  
- Remarks / performance feedback  

Common data problems present in the file:
- Missing numeric and text values  
- “missing” strings instead of NaN  
- Mixed date formats (YYYY-MM-DD, DD-MM-YYYY, MM/DD/YYYY)  
- Duplicated rows  
- Inconsistent gender, grade and remarks values  
- Irregular text casing  

### Tools & Libraries
- *Python 3*
- *Pandas*
- *NumPy*
- *Jupyter Notebook*

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

The dataset is now fully ready for EDA, reporting, downstream analysis.
