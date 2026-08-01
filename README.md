# Pandas CSV Reader & Basic Analysis

## Project Overview
This project demonstrates how to use the Pandas library in Python to read and analyze an Employee dataset. It covers basic data inspection, summary statistics, filtering, column selection, slicing, and exporting filtered data.

## Dataset
**Employee Dataset**

## Objectives
- Read a CSV file into a Pandas DataFrame.
- Inspect the dataset using `head()`, `tail()`, `info()`, and `dtypes`.
- Generate summary statistics including mean, median, minimum, maximum, and count.
- Filter rows based on specific conditions.
- Select required columns from the dataset.
- Slice subsets of data using Pandas indexing.
- Export the filtered data to a new CSV file.

## Steps Performed
- Imported the Pandas library.
- Loaded the Employee dataset into a DataFrame.
- Displayed the first and last few records using `head()` and `tail()`.
- Examined the structure and data types of the dataset.
- Generated summary statistics using `describe()`.
- Filtered employee records where **Age > 30**.
- Selected specific columns for analysis.
- Created data subsets using `iloc`.
- Saved the filtered results as **filtered_employee.csv**.

## Technologies Used
- Python
- Pandas
- Jupyter Notebook

## Project Files
- `Pandas_CSV_Reader_Basic_Analysis.ipynb`
- `Employee.csv`
- `filtered_employee.csv`

## Output
The filtered employee records were successfully exported to **filtered_employee.csv** for further analysis.
