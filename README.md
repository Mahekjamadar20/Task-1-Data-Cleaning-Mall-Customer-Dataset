Task 1 – Data Cleaning and Preprocessing

Dataset: Mall Customer Segmentation Data
Objective: The goal of this task was to clean and standardize a raw dataset by identifying and fixing missing values, duplicate records, inconsistent text formatting, and incorrect data types using Python and Pandas. Data cleaning ensures that the dataset is accurate, consistent, and ready for analysis or modeling.

Steps Performed

Loaded Dataset
A synthetic dataset was generated to replicate the Kaggle Mall Customer Segmentation dataset. The dataset contained information such as Customer ID, Gender, Age, Annual Income, and Spending Score.

Identified Missing Values
Missing values were detected using the .isnull().sum() function. Numerical columns were imputed using the mean value, while categorical columns such as Gender were filled using the mode. This step ensured data completeness and reliability.

Removed Duplicates
Duplicate records were identified and removed using .drop_duplicates() to maintain the uniqueness of each observation.

Standardized Text Data
The Gender column contained inconsistent text formats such as “male”, “FEMALE”, and “Other”. These were standardized into consistent labels — “Male”, “Female”, “Other”, and “Unknown” — using string manipulation techniques.

Renamed Columns
Column names were cleaned by converting them to lowercase and replacing spaces with underscores for uniformity, for example, “Annual Income (k$)” was renamed to “annual_income_k”.

Verified Data Types
Ensured that all numerical fields, such as Age, Annual Income, and Spending Score, were stored in appropriate numeric formats.

Exported Clean Dataset
The final cleaned dataset was saved as mall_customers_cleaned.csv for future analysis or modeling tasks.

Tools Used

Language: Python

Libraries: Pandas, NumPy

IDE: Jupyter Notebook

 Key Learning
Through this task, I learned how to handle real-world data issues such as missing values, duplicates, and inconsistent text. I practiced key preprocessing techniques in Pandas and gained confidence in preparing raw data for analysis. This task strengthened my data wrangling and quality assurance skills, both of which are essential for data analysis and machine learning workflows.
