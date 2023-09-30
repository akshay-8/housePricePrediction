# Predict the Cost of Homes in California Using Numpy + Pandas in Jupyter (with Pipelines)

This notebook trains a machine-learning model that predicts home costs in California.

The overall objective is to predict the value of home prices using **9 feature variables and 1 target variable:** 

#### **Feature Variables** ####

1.  **longitude:** A measure of how far west a house is (a higher value is farther west)
2.  **latitude:** A measure of how far north a house is (a higher value is farther north)
3.  **housingMedianAge:** Median age of a house within a block (a lower number is a newer building)
4.  **totalRooms:** Total number of rooms within a block
5.  **totalBedrooms:** Total number of bedrooms within a block
6.  **population:** Total number of people residing within a block
7.  **households:** Total number of households, a group of people residing within a home unit, for a block
8.  **medianIncome:** Median income for households within a block of houses (measured in tens of thousands of US Dollars)
9.  **oceanProximity:** Location of the house in proximity to the ocean

#### **Target Variable** ####
1.  **medianHouseValue:** Median house value for households within a block (measured in US Dollars)

## Background

## Scikit-learn

Scikit-learn is a machine-learning library for the Python programming language. It features various classification, regression and clustering learning algorithms. 

## Dependencies

- pandas - To work with solid data-structures, n-dimensional matrices and perform exploratory data analysis.
- matplotlib - To visualize data using 2D plots.
- seaborn - To make 2D plots look pretty and readable.
- scikit-learn - To create machine learning models easily and make predictions.
- numpy - To work with arrays.

**A few things to note:**

- You'll need to install the various libraries before importing them ```(i.e. %pip install pandas)```
- You may need to restart the kernel to use updated packages.
