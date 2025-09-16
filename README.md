# Pandas Crash Course

This repository contains a Jupyter Notebook (`Pandas_crash_course.ipynb`) that serves as a quick, hands-on introduction to the Python pandas library. It is designed for beginners to get started with fundamental data manipulation, analysis, and visualization techniques.

## Topics Covered

This notebook walks through the essential features of the pandas library, including:

* **Core Data Structures**: Introduction to `Series` (1D) and `DataFrame` (2D).
* **Creating DataFrames**:
    * From Python dictionaries.
    * By reading data from CSV files (`pd.read_csv`).
* **Data Inspection**:
    * Viewing the first and last few rows with `.head()` and `.tail()`.
    * Getting a concise summary with `.info()`.
    * Generating descriptive statistics with `.describe()`.
* **Data Selection**:
    * Selecting columns by name (`df['ColumnName']`).
    * Selecting specific rows and columns by integer location using `.iloc[]`.
* **Data Cleaning**:
    * Handling missing values (`NaN`) using `.dropna()` and `.fillna()`.
* **Data Modification**:
    * Adding new columns.
    * Applying functions to columns with `.apply()`.
    * Renaming columns with `.rename()`.
    * Changing a column's data type with `.astype()`.
* **Combining DataFrames**:
    * Stacking DataFrames vertically with `pd.concat()`.
    * Joining DataFrames based on common columns with `pd.merge()`.
* **Basic Visualization**:
    * Creating simple line plots and pie charts directly from DataFrames using `.plot()`.
* **Exporting Data**:
    * Saving a DataFrame to a CSV file with `.to_csv()`.

## Getting Started

To run this notebook, you'll need to have Python, Jupyter, and the required libraries installed.
## Created By Sujay Roy

### Prerequisites

* Python 3.x
* pandas
* matplotlib

You can install these dependencies using pip:
```bash
pip install pandas matplotlib jupyterlab
