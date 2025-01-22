# Tasks

Make sure to re-read the [assessment instructions](instructions.md) regularly.

## Task 1: Source the Data Set

Import the Iris data set from the `sklearn.datasets` module.  
Explain, in your own words, what the `load_iris()` function returns.  

## Task 2: Explore the Data Structure

Print and explain the shape of the data set, the first and last 5 rows of the data, the feature names, and the target classes.  

## Task 3: Summarize the Data

For each feature in the dataset, calculate and display:  

- mean
- minimum
- maximum
- standard deviation
- median

## Task 4: Visualize Features

Plot histograms for each feature using `matplotlib`.  
Add appropriate titles and axis labels.  

## Task 5: Investigate Relationships

Choose any two features from the data set and create a scatter plot of them.  
Color-code the three different classes of the scatter plot points.

## Task 6: Analyze Relationship

Use `numpy.polyfit` to add a regression line to the scatter plot from Task 5.

## Task 7: Analyze Class Distributions

Create box-plots of the petal lengths for each of the three classes.

## Task 8: Compute Correlations

Calculate the correlation coefficients between the features.  
Display the results as a heatmap using `matplotlib`.  

## Task 9: Fit a Simple Linear Regression

For your two features in Task 5, calculate the coefficient of determination $R^2$.  
Re-create the plot from Task 6 and annotate it with the $R^2$ value.

## Task 10: Too Many Features

Use `seaborn` to create a `pairplot` of the data set.  
Explain, in your own words, what the `pairplot` depicts.  
