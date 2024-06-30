# World-Happiness-Report-Analysis-and-Climate-Change-Exploratory-Data-Analysis

Introduction

This repository contains the analysis and exploration of two major datasets: the World Happiness Report (2015-2019) and a Global Temperature dataset (1848-2020). The analyses address questions regarding global happiness metrics and climate change trends, 

providing insights into happiness scores, GDP, and temperature variations over time.

Data Sources

World Happiness Report (2015-2019): Kaggle Dataset

Global Temperature Data (1848-2020): NASA climate data (details for downloading or linking to data should be added here).

Setup and Requirements
To run the analyses in this repository, the following dependencies are required:


Python 3.x

Pandas

Matplotlib

Seaborn

Openpyxl

PIL (Python Imaging Library)

NumPy

Install the dependencies using the following command:



bash
Copy code

pip install pandas matplotlib seaborn openpyxl pillow numpy

Analysis Overview

Question 1: World Happiness Report Analysis

This part of the analysis involves working with the World Happiness Report datasets from 2015 to 2019. The tasks include:



Loading the datasets for each year into Pandas DataFrames.

Retrieving specific country data based on health metrics.

Identifying top countries with the highest happiness scores.

Calculating mean happiness scores by region.

Detecting outliers in happiness scores.

Exploring the relationship between happiness scores and GDP per capita.

Combining datasets into a single DataFrame for comparative analysis.

Visualizing trends in happiness scores for selected countries.

Analyzing regional economic data.

Determining correlations between various factors.

Question 2: Climate Change Exploratory Data Analysis

This part focuses on exploring climate change data, involving:



Handling missing values in the dataset.

Ensuring data type consistency.

Transforming date information.

Detecting and analyzing outliers in temperature data.

Computing summary statistics for temperature data.

Identifying countries and their average temperatures.

Determining global temperature trends.

Identifying seasonal patterns in temperature data.

Exploring temperature anomalies.

Comparing temperature trends for multiple countries.

Investigating correlations between temperature and anomalies.

Results

World Happiness Report Findings

Countries with Specific Health Values (2015):



List of countries with Health (Life Expectancy) values between 0.5 and 1.

Top 10 Happiest Countries (2016):



Finland, Denmark, Iceland, Norway, and others.

Mean Happiness Score by Region (2016):



Detailed breakdown of average happiness scores by region.

Outliers in Happiness Scores:



Visualizations showing the distribution and outliers for each year.

Happiness Score vs. Economy:



Scatter plot and analysis indicating the relationship between happiness scores and GDP per capita.

Combined Dataset Analysis:



A comprehensive DataFrame showing happiness scores across years.

Happiness Trends for Selected Countries:



Line charts illustrating the trends for countries like Finland and Denmark.

Regions with Low GDP (2015):



Identification of regions with low GDP values.

Correlation Analysis (2015-2016):



Variables with the highest correlations across the datasets.

Climate Change EDA Findings

Missing Values Handling:



Replacement of missing values using mean imputation.

Data Type Consistency:



Ensuring all columns have appropriate data types.

Date Transformation:



Conversion of Year and Month into a single Date column.

Temperature Outliers:



Visualization and analysis of extreme temperature values.

Summary Statistics:



Mean, median, standard deviation, and range for temperature data.

Average Temperature by Country:



Calculation of average temperatures for countries in the dataset.

Global Temperature Trends:



Visualization of overall temperature trends over the years.

Seasonal Temperature Patterns:



Analysis of the highest and lowest temperature months for each country.

Monthly Temperature Anomalies:


Identification of months with consistent temperature anomalies.

Temperature Trends Comparison:



Line charts comparing temperature trends for selected countries.

Correlation Analysis:


Investigation of correlation between temperature and anomalies.


Visualizations

This section provides visual representations of the analyses conducted:


Boxplots: For detecting outliers.

Scatterplots: Showing relationships between variables.

Line Charts: Illustrating trends over time.

Bar Charts: Representing mean values and other statistics.

Add the images or links to your visualizations here.







Run the Analysis Notebooks:

Open and run the Jupyter notebooks provided in the repository to execute the analyses.


View the Results:

The results will be displayed in the notebook outputs, including tables and visualizations.


Contributing


Contributions are welcome! Please fork the repository and create a pull request with your proposed changes. Ensure to follow the coding standards and write clear commit messages.



