# Matplotlib Challenge

## Overview
This project is part of a data analysis challenge where we use the Matplotlib library to visualize and analyze data from a pharmaceutical study. The study involves 249 mice treated with various drug regimens to measure the effectiveness of treatments against squamous cell carcinoma (SCC), a type of skin cancer.

## Objectives
The main objectives of this project are to:
1. Prepare and clean the data.
2. Generate summary statistics.
3. Create visualizations including bar plots, pie charts, box plots, line plots, and scatter plots.
4. Calculate correlation and linear regression.

## Steps:
1. Prepare the Data
- Read the CSV files into Pandas DataFrames.
- Merge the DataFrames on 'Mouse ID'.
- Identify and remove any duplicate records.

2. Generate Summary Statistics
- Calculate mean, median, variance, standard deviation, and SEM (standard error of the mean) for tumor volumes for each drug regimen.

3. Create Bar Charts and Pie Charts
- Bar Charts: Show the total number of time points for each drug regimen using both Pandas and Matplotlib.
- Pie Charts: Show the distribution of female versus male mice using both Pandas and Matplotlib.

4. Calculate Quartiles, Find Outliers, and Create a Box Plot
- Calculate the final tumor volume for each mouse for four drug regimens (Capomulin, Ramicane, Infubinol, and Ceftamin).
- Calculate quartiles and IQR to determine outliers.
- Create a box plot to show the distribution of tumor volumes.

5. Create a Line Plot and a Scatter Plot
- Line Plot: Tumor volume vs. time point for a single mouse treated with Capomulin.
- Scatter Plot: Mouse weight vs. average tumor volume for the Capomulin regimen.

6. Calculate Correlation and Regression
- Calculate the correlation coefficient between mouse weight and average tumor volume for the Capomulin regimen.
- Perform linear regression and plot the regression line on the scatter plot.
