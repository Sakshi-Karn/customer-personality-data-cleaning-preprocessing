📌 Task 1 — Data Cleaning & Preprocessing

This task involves cleaning the Customer Personality Analysis dataset by handling missing values, removing duplicates, standardizing text fields, fixing data types, and exporting a cleaned version of the dataset.

🧹 Steps Performed

1.Loaded data using Pandas with tab (\t) delimiter.

2.Checked missing values and filled missing Income using median.

3.Removed duplicate rows from the dataset.

4.Converted Dt_Customer into proper datetime format using dayfirst=True.

5.Renamed all columns to lowercase.

6.Standardized text values in education and marital_status columns.

7.Converted numerical columns to correct data types using pd.to_numeric.

8.Exported the cleaned dataset as cleaned_marketing_campaign.csv.

📁 Files in This Repository

Task1_Data_Cleaning.ipynb — Google Colab notebook

cleaned_marketing_campaign.csv — cleaned dataset

Original dataset

🧠 Tools Used

Python

Pandas

Google Colab

