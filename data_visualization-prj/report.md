
**Fuel Economy Data Visualization Project**

**Overview**

This project is part of the Data Analysis Training through NTI, focusing on Python visualization techniques. The goal was to analyze a dataset related to fuel economy and emissions, clean and transform the data, and create visualizations to uncover insights and patterns.

**Table of Contents**

1\. Project Description

2\. Data Gathering

3\. Data Cleaning and Preparation

4\. Tidiness Issues

5\. Visualization

6\. Tools and Libraries

7\. Conclusion

**Project Description**

The dataset used for this project contains detailed vehicle information, including fuel efficiency, CO2 emissions, and engine specifications. The main objectives were to clean and prepare the data, address tidiness issues, and create visualizations to analyze the following aspects:

\-  Correlation between fuel efficiency and CO2 emissions

\-  Impact of engine displacement and cylinders on fuel economy

\-  Comparison of fuel economy across different vehicle classes

\-  Manufacturers' performance in terms of CO2 emissions

**Data Gathering**

The data was loaded from a CSV file named `fuel-econ.csv` containing various attributes related to vehicles' fuel economy and emissions.




**Data Cleaning**

- **Handling Missing Values:** No missing values were detected in the dataset.
- **Duplicate Data:** No duplicate rows were found.
- **Inconsistent Data Types:** Converted the 'year' column to a date format for consistency.

**Tidiness Issues**

- **Issue 1: Column Redundancy:** The dataset had redundant columns that were combined for simplicity. For example, 'engine\_displacement' and 'cylinders' were combined into a single 'engine\_specs' column.
- **Issue 2: Multiple Values in Single Columns:** Some columns contained multiple values separated by commas. These were split into separate columns for clarity.
- **Issue 3: Unstandardized Units:** The units for fuel economy varied across rows. These were standardized for consistency.

**Visualization**

Various visualizations were created to represent the insights from the data:

- **Efficiency vs. Emissions:** 

Understanding how fuel efficiency metrics (e.g., city, highway, combined MPG) correlate with CO2 emissions across different vehicle classes

![Efficiency vs. Emissions](visuals/Efficiency%20vs%20Emissions.png)












- **Engine Displacement vs. Fuel Economy:**

Analyzing how engine displacement and the number of cylinders affect fuel economy 

and emissions

![Engine Displacement vs. Fuel Economy](visuals/Engine%20Displacement%20vs.%20Fuel%20Economy.png)












- **Combined Fuel Economy by Vehicle Class:** 

  Identifying which vehicle classes tend to be more fuel-efficient or emit less CO2

  ![Combined Fuel Economy by Vehicle Class](visuals/Combined%20Fuel%20Economy%20by%20Vehicle%20Class.png)











- **Manufacturers' Performance:**

  Comparing fuel economy and emissions across different manufacturers

  to see if some consistently perform better or worse.

![Manufacturers' Performance](visuals/Manufacturers'%20Performance.png)










- **Correlation Between Features:**

Identifying the relationships between numeric variables like CO2, combined MPG, engine size, and cylinders.

![Correlation Between Features](visuals/Correlation%20Between%20Features.png)














**Tools and Libraries**

- **Python:** Programming language used for data analysis and visualization.
- **Pandas:** Library for data manipulation and analysis.
- **Matplotlib:** Library for creating static, animated, and interactive visualizations.
- **Seaborn:** Library for making statistical graphics.

**Conclusion**

The project successfully demonstrated the power of Python for data cleaning, preparation, and visualization. The visualizations provided valuable insights into fuel economy and emissions, revealing patterns and trends that can inform decision-making for vehicle manufacturers and consumers.

