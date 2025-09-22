# Task-1
**Data Cleaning and Preprocessing**

# Tools Used
- Python (Pandas)

# Cleaning Steps Performed

# 1. Missing Values
- Identified missing values using `.isnull().sum()`
- Filled missing `Income` values with median using `fillna()`

# 2. Duplicates
- Removed duplicate rows using `.drop_duplicates()`

# 3. Text Standardization
- Mapped inconsistent categories (e.g., `"2n cycle"` → `"Master"`, `"yolo"` → `"Other"`)

# 4. Date Formatting
- Converted `Dt_Customer` column to datetime format using `pd.to_datetime()` with `dayfirst=True`

# 5. Column Renaming
- Renamed all column headers to lowercase with underscores (e.g., `"Marital Status"` → `"marital_status"`)

# 6. Data Type Fixes
- Ensured numeric columns are of correct type (`int`, `float`)
- Verified `Dt_Customer` is in `datetime64` format

# Final Deliverables
- A cleaned dataset ready for analysis

# Notes
This task was completed using  Python (Pandas). The goal was to ensure the dataset is consistent, readable, and analysis-ready for future tasks.
