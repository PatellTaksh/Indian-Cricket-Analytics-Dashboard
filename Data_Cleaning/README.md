# Data Cleaning

This folder contains the notebooks used to clean and preprocess the raw batting statistics scraped from the BCCI website.

Each notebook focuses on a specific dataset (Men/Women and Test/ODI/T20I).

## Data Cleaning Tasks

- Removed unnecessary symbols
- Handled missing values
- Converted data types
- Standardized column names
- Corrected inconsistent values
- Exported cleaned CSV files

## Files
- Cleaned_CSV
- Men_ODI_Data_Cleaning.ipynb
- Men_T20I_Data_Cleaning.ipynb
- - Men_Test_Data_Cleaning.ipynb
- Women_ODI_Data_Cleaning.ipynb
- Women_T20I_Data_Cleaning.ipynb
- Women_Test_Data_Cleaning.ipynb

The cleaned datasets generated from these notebooks are later merged and loaded into PostgreSQL.
