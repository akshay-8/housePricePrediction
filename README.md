# Estimating Home Prices in California Using Numpy and Pandas in Jupyter (with Pipelines)

This Jupyter Notebook constructs a machine-learning model for estimating home prices in California.

The primary goal is to make predictions regarding home values by utilizing **9 feature variables and 1 target variable:**

#### **Feature Variables** ####

1. **longitude:** An indicator of the westward distance of a house (higher values imply a greater westward location).
2. **latitude:** An indicator of the northward distance of a house (higher values imply a greater northward location).
3. **housingMedianAge:** The median age of a house within a specific block (lower values represent newer buildings).
4. **totalRooms:** The total number of rooms within a block.
5. **totalBedrooms:** The total number of bedrooms within a block.
6. **population:** The total number of individuals residing within a block.
7. **households:** The total number of households in a block (a household is a group of people residing within a single housing unit).
8. **medianIncome:** The median income of households within a block of houses (measured in tens of thousands of US Dollars).
9. **oceanProximity:** The proximity of the house to the ocean.

#### **Target Variable** ####
1. **medianHouseValue:** The median house value for households within a block (measured in US Dollars)

## Context

## Scikit-learn

Scikit-learn is a Python machine-learning library that offers a wide range of classification, regression, and clustering algorithms.

## Required Libraries

- **pandas:** Used for data manipulation, working with data structures, and conducting exploratory data analysis.
- **matplotlib:** Employed for creating 2D data visualizations.
- **seaborn:** Used to enhance the visual appeal and interpretability of 2D plots.
- **scikit-learn:** Utilized for constructing machine learning models and making predictions.
- **numpy:** Applied for array manipulation and computations.

**Important Notes:**

- Make sure to install the necessary libraries before importing them (e.g., `%pip install pandas`).
- In some cases, restarting the kernel might be necessary for updated packages to take effect.
