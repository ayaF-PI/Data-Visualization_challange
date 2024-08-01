#data_visualization_callange

# Tumer Treatment Data Analysis

## Overview

This project analyzes data from a study on mouse treatments to understand how different drug regimens affect tumor volume. The analysis involves preparing the data, calculating statistics, and creating various plots to visualize the results.

## Steps in the Project

### 1. Data Preparation
- **Merged Data**: Combined different datasets into one.
- **Counted Mice**: Found out how many mice are in the data.
- **Found Duplicates**: Checked for duplicate mouse data using Mouse ID and Timepoint.
- **Cleaned Data**: Removed duplicates to get clean data.
- **Recounted Mice**: Counted the mice again after cleaning.

### 2. Summary Statistics
- **Calculated Averages**: Found the mean (average) tumor volume for each drug regimen.
- **Found the Middle Value**: Calculated the median tumor volume.
- **Measured Spread**: Calculated variance and standard deviation to see how spread out the data is.
- **Calculated SEM**: Found the standard error of the mean for tumor volume.
- **Created Summary Table**: Put all these statistics into a new table.

### 3. Bar Charts and Pie Charts
- **Bar Charts**: 
  - Used Pandas to make a bar chart showing how many timepoints were recorded for each drug regimen.
  - Used Matplotlib’s Pyplot to create the same bar chart.
- **Pie Charts**: 
  - Made a pie chart with Pandas showing the proportion of male and female mice.
  - Created the same pie chart using Pyplot.

### 4. Quartiles, Outliers, and Box Plot
- **Grouped by Last Timepoint**: Created a table to find the last timepoint for each mouse.
- **Reset Index**: Made the table easier to work with by resetting its index.
- **Selected Key Drugs**: Focused on four specific drugs: Capomulin, Ramicane, Infubinol, and Ceftamin.
- **Checked for Outliers**: Used quartiles to find any outliers (unusual values) in the data.
- **Box Plot**: Made a box plot to visualize the tumor volumes for each drug.

### 5. Line Plot and Scatter Plot
- **Line Plot**: Made a line plot showing tumor volume over time for one mouse treated with Capomulin.
- **Scatter Plot**: Created a scatter plot showing how average tumor volume relates to mouse weight for the Capomulin regimen.

### 6. Correlation and Regression
- **Correlation and Regression**: Checked if there’s a relationship between mouse weight and tumor volume for Capomulin-treated mice using correlation and regression analysis.

## Conclusion

This project helps us understand the effects of different drugs on tumor growth in mice. The charts and statistics give us a clear picture of the data.