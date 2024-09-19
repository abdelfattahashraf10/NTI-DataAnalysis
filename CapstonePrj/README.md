
# ![Supermarket Icon](CityMart%20logo.png) 
# Supermarket Sales Data Wrangling


## Project Overview

This project involves cleaning and analyzing supermarket sales data collected from three different branches: Yangon, Mandalay, and Naypyitaw. The main objectives are to address quality and tidiness issues in the dataset, and perform meaningful data visualizations to uncover insights regarding sales distribution, customer behavior, and product performance.

## Dataset

The dataset includes over 1000 sales records from different branches and product lines, capturing various features like:

- Invoice ID
- Branch (Yangon, Mandalay, Naypyitaw)
- Customer Type (Normal, Member)
- Product Line (e.g., Fashion, Electronics, Food)
- Unit Price, Quantity, Total Sales
- Payment Method (Cash, Credit, Ewallet)
- Customer Ratings

## Project Steps

### 1. Data Gathering
- Loaded the dataset from a CSV file.
- Previewed the first few and last few rows to get a quick look at the structure.

### 2. Data Inspection
- Identified inconsistencies such as negative quantity values, missing data in tax and total columns, and incorrect formats in date and time columns.
- Observed missing values in important columns such as "Customer Type" and "Tax 5%".

### 3. Data Cleaning
#### Quality Issues Addressed:
- Corrected negative quantities by converting them to absolute values.
- Fixed inconsistent values in the "Customer Type" and "Time" columns.
- Handled missing values by recalculating the "Tax" and "Total" based on unit price and quantity.
- Removed duplicates from the dataset.

#### Tidiness Issues Addressed:
- Consolidated branch information into a single "City" column.
- Removed redundant columns like separate city indicators (Yangon, Naypyitaw, Mandalay).

### 4. Data Visualization
- **Sales Distribution by City**: Displayed the proportion of total sales in each city using a pie chart.
- **Customer Type Distribution**: Visualized the distribution of customer types (Normal vs. Member).
- **Sales Trend Over Time**: Analyzed how sales fluctuated over the time period covered in the dataset.
- **Average Purchase by Gender**: Compared the average purchase amount by gender using bar charts.
- **Product Line Preferences**: Showcased the total sales for each product line.
- **Payment Method Distribution**: Displayed the distribution of payment methods used by customers.

## Key Insights
- The majority of sales come from a few specific cities, with Yangon contributing the highest percentage.
- Normal customers made up a larger portion of the total sales, but members contributed more per transaction on average.
- There is a clear preference for certain product lines such as Fashion and Electronics.
- Ewallet is the most commonly used payment method, followed by Cash.

## Tools & Libraries
- **Pandas**: For data loading, cleaning, and manipulation.
- **NumPy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For generating data visualizations.



## Future Work
- Expand analysis to include customer segmentation and purchase patterns.
- Use machine learning models to predict customer behavior and preferences.

## Author
[Abdelfattah Ashraf]()

