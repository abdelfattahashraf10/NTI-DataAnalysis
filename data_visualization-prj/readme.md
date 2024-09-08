# Fuel Economy Data Analysis Project

## 1. Project Description
This project aims to analyze vehicle fuel economy metrics, exploring relationships between fuel consumption, engine size, and CO2 emissions. The dataset contains information on city and highway mileage, engine displacement, number of cylinders, and emissions. The objective is to identify trends and correlations that can provide insights into vehicle efficiency and environmental impact.

## 2. Challenges and Issues

### 2.1 Data Quality and Cleaning
- **Missing or Inconsistent Data**: The dataset initially had missing values, particularly in fuel consumption and engine size fields.
- **Inconsistent Column Names**: Some column names were either misspelled or inconsistent, requiring renaming for better readability and usability.
- **Outliers**: There were extreme values in CO2 emissions and fuel consumption, likely due to errors or unusual data points.

### 2.2 Data Normalization
- Data in different columns had varying scales (e.g., engine size in liters vs fuel economy in miles per gallon), so normalization was necessary for comparison.
- Certain vehicles with unusual features (e.g., very high engine displacement but low mileage) had to be examined more carefully to ensure their impact on analysis was minimized.

## 3. Solutions and Techniques

### 3.1 Handling Missing Data
- **Dropped Rows**: Rows with missing critical values (like CO2 or engine displacement) were dropped to avoid skewing the analysis.
- **Column Renaming**: Inconsistent column names were standardized for clarity, ensuring the dataset was easy to manipulate.

### 3.2 Addressing Outliers
- **Visual Inspection**: Outliers were identified using box plots, and some extreme data points were removed or handled through capping techniques.
- **Statistical Analysis**: Z-scores were used to quantify outliers and remove those beyond a reasonable threshold.

### 3.3 Data Correlation and Analysis
- A correlation matrix was used to measure relationships between variables like city mileage, highway mileage, engine size, and CO2 emissions. This allowed us to identify strong correlations and key insights.

## 4. Visualization Summary

### 4.1 Scatter Plots
- **City Mileage vs. Highway Mileage**: A scatter plot was used to visualize the relationship between these two metrics, revealing an inverse relationship in many vehicle categories.
- **Engine Displacement vs. CO2 Emissions**: This plot showed that larger engines tend to produce more CO2, helping highlight the environmental impact of certain vehicles.

### 4.2 Correlation Heatmap
- A correlation heatmap was generated to identify strong relationships between key variables. For instance, engine displacement and CO2 emissions were strongly positively correlated, while city mileage and CO2 emissions had a strong negative correlation.

### 4.3 Bar Charts
- **Fuel Efficiency by Vehicle Type**: Bar charts were used to compare fuel efficiency across different vehicle categories, showcasing differences in urban vs. highway performance.

## 5. Conclusion
The analysis shows that fuel efficiency is significantly influenced by engine size, and larger engines are associated with higher CO2 emissions. Vehicles with higher highway mileage generally perform worse in city conditions, highlighting the trade-offs in vehicle design.

