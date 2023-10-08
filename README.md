# MSCS-Python-Project

# Data Analysis and Visualization with Python

This repository contains Python code for data analysis and visualization tasks using Pandas, NumPy, Matplotlib, and Seaborn.

## Overview

Data analysis and visualization are fundamental in understanding and gaining insights from datasets. This Python project tackles various aspects of this process with two main tasks: Task-1 and Task-2.

### Task-1: Calculating Least Square Error (LSE)

Task-1 focuses on calculating the Least Square Error (LSE) for each column in the provided dataset. LSE is a statistical measure used to evaluate how well ideal functions fit the data. Here's what Task-1 does:

- Loads the training data, test data, and ideal functions from an Excel file.
- Iterates through columns in the training data to find the ideal function that minimizes LSE.
- Stores the column index and corresponding LSE in a DataFrame.
- Visualizes the LSE for each column using a bar plot, providing insights into the best-fitting functions.

### Task-2: Merging Ideal Functions and Calculating Deviations

Task-2 involves merging ideal functions with test data and calculating deviations. It helps us understand how well the ideal functions map to the test data. Here's what Task-2 does:

- Merges the ideal functions with the test data based on the selected ideal functions from Task-1.
- Calculates deviations between the test data and the merged ideal functions.
- Assigns an ideal index to each data point based on the best-fitting ideal function.
- Visualizes the merged data using line plots, providing insights into the relationship between 'x' and 'y' values.
- Visualizes deviations vs. 'x' using a scatter plot to identify outliers.
- Displays a count plot of ideal indices to understand how well the ideal functions match the test data.

## Usage

1. Install required libraries: `pandas`, `numpy`, `matplotlib`, and `seaborn`.
2. Load data from the provided Excel file.
3. Run the code for Tasks 1 and 2.
4. Visualize the results with various plots.

## Dependencies

- Pandas: Used for data manipulation and analysis.
- NumPy: Provides support for mathematical operations.
- Matplotlib: Used for creating a variety of plots.
- Seaborn: Enhances the aesthetics of Matplotlib plots.

## Author

- [ Devireddy sarath reddy ]
