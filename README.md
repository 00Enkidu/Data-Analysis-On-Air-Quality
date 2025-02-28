# Air Quality Data Analysis

## Overview
This project focuses on analyzing air quality data using various statistical and visualization techniques. The analysis covers relationships between pollutants and environmental factors, statistical distributions, and dimensionality reduction methods.

## Analysis Tasks

### 1. Supervised Scatter Plots
- **Proximity to Industrial Areas vs. CO**
  - Generate a scatter plot to observe the relationship between proximity to industrial areas and carbon monoxide (CO) levels.
  - Interpret the trends and possible correlations.

- **PM2.5 vs. PM10**
  - Visualize the relationship between PM2.5 and PM10 concentrations.
  - Analyze their correlation and potential dependencies.

### 2. Histograms and Statistical Measures
- **Humidity Distribution**
  - Plot a histogram using 30 bins.
  - Calculate the mean, standard deviation, and median.
  - Interpret the distribution pattern.

- **Proximity to Industrial Areas Distribution**
  - Generate a histogram with 30 bins.
  - Compute the mean, standard deviation, and median.
  - Analyze the spread and characteristics of the distribution.

### 3. Supervised Scatter Plot Matrix and Correlation Analysis
- **Attributes: Temperature, PM2.5, CO, Proximity to Industrial Areas**
  - Construct a scatter plot matrix to explore relationships between these attributes.
  - Compute Pearson correlation coefficients.
  - Interpret the correlation between CO and each of the other three attributes.

### 4. Box Plot Analysis
- **PM2.5 for "Poor" Air Quality Class**
  - Generate a box plot.
  - Identify Q1, median, Q3, IQR, minimum, and maximum values.
  - Count the number of outliers.
  - Determine if the distribution is skewed and the type of skewness.

- **CO for "Poor" and "Moderate" Air Quality Classes**
  - Compare the distributions of CO in "Poor" and "Moderate" air quality classes using a box plot.
  - Analyze differences in median, IQR, and spread.

### 5. Principal Component Analysis (PCA)
- **PCA on Nine Attributes (Excluding "Air Quality")**
  - Reduce the dimensionality to two principal components.
  - Visualize the data in a 2D scatter plot.

- **Normalization and PCA Comparison**
  - Apply Z-Score and Min-Max normalization separately.
  - Perform 2D PCA on both normalized datasets.
  - Compare the results before and after normalization.
  - Discuss the impact of normalization and the benefits of PCA in this analysis.

## Conclusion
This project provides insights into air quality patterns and relationships using statistical and machine learning techniques. The results help in understanding pollution sources, correlations between environmental factors, and the effectiveness of dimensionality reduction methods.

