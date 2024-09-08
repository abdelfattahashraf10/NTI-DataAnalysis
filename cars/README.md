
# Data Wrangling Report

## Overview

This Jupyter notebook is dedicated to data wrangling, which involves gathering, inspecting, cleaning, and preparing data for analysis. The notebook follows a systematic approach to load raw data, inspect its structure, identify issues, and apply necessary transformations to make the data suitable for further analysis.

## 1. Data Gathering

### a. Loading Data
- **Data Values**: The notebook starts by loading data from a file named `data_values.txt` into a pandas DataFrame. Initially, the data is loaded without column headers.
- **Column Headers**: Column headers are loaded separately from another file named `column_headers.txt`. These headers are then assigned to the DataFrame, giving structure and meaning to the columns.

### b. Data Preview
- A preview of the first few rows of the DataFrame is displayed to give a quick look at the data structure and contents.
- It is noted that the column headers require cleaning, and the `normalized-losses` column contains `'?'` values instead of proper null values.

## 2. Data Inspection

### a. Data Dimensions
- The notebook checks the dimensions of the dataset, revealing that it contains 205 rows and 26 columns. This gives an idea of the dataset's size and complexity.

### b. Identifying Issues
- Several issues are identified during the inspection, including:
  - The need to clean column headers for consistency and readability.
  - The presence of `'?'` values in the `normalized-losses` column, which should be handled appropriately as these represent missing data.

## 3. Data Cleaning

The data cleaning section (presumably following the inspection) would typically involve:
- **Replacing or Removing Missing Values**: The `'?'` in the `normalized-losses` column would be converted to `NaN` and then handled through imputation or removal.
- **Standardizing Column Headers**: Column names might be standardized to follow a consistent format, removing spaces, converting to lowercase, etc.
- **Data Type Conversion**: Certain columns may need to be converted to appropriate data types (e.g., converting numerical columns that were initially read as strings).
- **Handling Outliers**: If there are any extreme outliers, they would be identified and managed accordingly.

## 4. Tidiness Issues

- Each variable forms a column and contains values: **Nothing**
- Each observation forms a row: **Nothing**
- Each type of observational unit forms a table: **Nothing**

## 5. Visualizations

1. **Distribution of Car Prices**: A histogram to show the distribution of car prices.
![Distribution of Car Prices](/visuals/Distribution%20of%20Car%20Prices.png)

2. **Horsepower vs. Price**: A scatter plot to visualize the relationship between horsepower and price.
![Horsepower vs. Price](/visuals/Horsepower%20vs.%20Price.png)

3. **Fuel Type Distribution**: A bar chart to show the count of different fuel types.
![AFuel Type Distribution](/visuals/Fuel%20Type%20Distribution.png)



## 6. Final Data Preparation

After cleaning, the data would be ready for analysis. This might include:
- **Feature Engineering**: Creating new features or transforming existing ones.
- **Normalization or Scaling**: Preparing the data for models that require normalized or scaled inputs.
- **Splitting Data**: If the notebook is preparing data for machine learning, it may split the data into training and test sets.

## Conclusion

This notebook systematically handles raw data, beginning with gathering and inspecting it, then moving on to identify and rectify issues through data cleaning. The outcome is a well-prepared dataset ready for analysis or modeling. The steps and transformations are documented and executed within the notebook, ensuring that the data is in optimal shape for the next phase of the project.
