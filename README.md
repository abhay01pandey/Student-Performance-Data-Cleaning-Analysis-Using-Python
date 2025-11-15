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

### 1. Data Loading
- Loaded the CSV file into a Pandas DataFrame.

### 2. Data Cleaning
- Replaced “missing” strings with NaN.
- Converted english_score from object → numeric.
- Filled missing numeric values using mean imputation.
- Standardized text fields:
  - Lowercased + title-cased names
  - Normalized gender values (Male/Female)
  - Cleaned remarks/categories
- Fixed inconsistent grade formats (10 / 10th / 11th → standardized).
- Unified all date formats and converted to datetime.
- Removed duplicated records.
- Ensured all columns have correct datatypes.
  
 ### 3. Output
- Produced a fully cleaned dataset ready for EDA or further modeling.


# Results

After preprocessing:
- All text fields are standardized and consistent.
- Dates follow a single uniform format.
- Missing values are handled logically.
- Numeric fields are properly typed and cleaned.
- Duplicates are removed.
- The final dataset is stable, readable and ready for:
  - Data visualization  
  - KPI reporting  
  - Exploratory data analysis  
  - Machine learning pipelines  
