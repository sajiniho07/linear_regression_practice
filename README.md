# linear_regression_practice

## Introduction
This is a Python script for performing linear regression on data stored in an Excel file using the OpenPyXL library. The script loads data from an xlsx file, performs linear regression and plots the predicted values against the actual values.

## Dependencies
* numpy
* matplotlib
* openpyxl
* sklearn

## Installation
Clone or download the repository.

## Code Explanation
The script loads data from an Excel workbook using the ```load_workbook``` method from the ```openpyxl``` package. It then extracts the relevant data into separate numpy arrays. The ```LinearRegression()``` method from the sklearn package is used to perform linear regression on the data. The ```model_prediction()``` function takes two input arrays and returns the predicted y-values. Finally, the ```plot_output_prediction()``` function plots the predicted values against the actual values.

## Limitations
* The script assumes that the data is in a specific format: four columns (x1, x2, x3, y) with no header row.
* The script only works with Excel files and requires the openpyxl package to be installed.
* The script does not perform any data cleaning or preprocessing before performing linear regression.
