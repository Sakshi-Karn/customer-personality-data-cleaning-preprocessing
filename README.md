📌 Task 1 — Data Cleaning & Preprocessing

This task involves cleaning the Customer Personality Analysis dataset by handling missing values, removing duplicates, standardizing text fields, fixing data types, and exporting a cleaned version of the dataset.

🧹 Steps Performed
1. Data Loading

Loaded the dataset using pandas.read_csv()

Used the correct delimiter (sep='\t') because the file was tab-separated.

2. Missing Value Handling

Identified missing values using df.isnull().sum()

Filled missing values in the Income column using the median.

Dropped rows with missing values in the date column (Dt_Customer).
