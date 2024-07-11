# Electronic-Vehicles-data-Analysis-and-visualizations

This repository contains a Python script that performs data analysis on electric vehicle data. The script uses various Python libraries to analyze and visualize the data, focusing on electric vehicle models, their age, and their electric range.

## Requirements

To run the script, you need the following libraries:

    pandas
    numpy
    scikit-learn
    matplotlib
    seaborn
    plotly

## Dataset

Used the dataset from data.gov

## Script Overview

The script performs the following steps:

    Import Libraries:
    Imports the necessary libraries for data manipulation, visualization, and machine learning.

    Load Dataset:
    Reads the CSV file into a DataFrame and displays the first few rows.

    Data Cleaning:
    Checks for missing values and drops rows with missing data.

    Data Visualization:
       - Plots the distribution of electric vehicle makes.
       - Plots the top 10 cities with the highest number of electric vehicles.
       - Adds an Age column to the DataFrame based on the current year and the model year.
       - Visualizes the relationship between the age of the model and the electric range using scatter plots.
       - Plots the counts of electric vehicles by model year and type.
       - Plots the distribution of electric range with respect to Clean Alternative Fuel Vehicle (CAFV) eligibility.

    Correlation Analysis:
    Calculates and prints the Pearson correlation coefficient between the age of the model and the electric range.

## Conclusion 

This script provides a comprehensive analysis of electric vehicle data, including data cleaning, visualization, and correlation analysis. The visualizations help in understanding the distribution and trends in the dataset, supporting data-driven decision-making.
