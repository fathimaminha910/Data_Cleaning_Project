Data Ingestion, Cleaning & Preprocessing with Pandas

Project Overview
This project focuses on data ingestion, cleaning, and preprocessing using Python Pandas.
Dataset
Online Retail Dataset
- Initial Rows: 541,909
- Final Rows: 534,129
- Final Columns: 11
Tools Used
- Python
- Google Colab
- Pandas
Data Cleaning Steps
- Checked missing values
- Removed duplicate records
- Removed rows with missing Description
- Removed invalid UnitPrice values
- Checked data types
Feature Engineering
Created three new columns:
- Year
- Month
- TotalSales
Outlier Detection
Used the IQR method to detect outliers in UnitPrice.
Number of outliers detected: 39,448.
Final Results
- Rows: 534,129
- Columns: 11
- Duplicate Rows: 0
Project Files
- Data_Cleaning_Project-Copy.ipynb
- clean_dataset.zip
Conclusion
Data cleaning and preprocessing were performed using Python Pandas. The cleaned dataset was exported for further analysis.
