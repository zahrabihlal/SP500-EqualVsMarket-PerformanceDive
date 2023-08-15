# S&P 500 Constituents Analysis

This repository contains an analysis of the S&P 500 index, focusing on the differences in performance between equally weighted (EWI) and market-cap weighted (MWI) indices. The analysis explores the factors contributing to the outperformance of the EWI.

## Contents

`MWI_vs_EWI_SP500.ipynb`: Notebook for data cleaning, merging, and preprocessing then performing the analysis on the prepared data.

## Overview

This analysis aims to determine the reasons for the outperformance of the EWI over the MWI by investigating the distribution of individual stock returns within the index.

### Steps:

1. **Data Preprocessing**:
    - Merging multiple data sources.
    - Handling missing values.
    - Identifying and removing columns with NaN values.

2. **Exploratory Data Analysis (EDA)**:
    - Visualizing the distribution of daily returns.
    - Calculating and interpreting skewness.
    - Plotting the cumulative returns of EWI and MWI portfolios.

3. **Quantitative Analysis**:
    - Percentile analysis to understand the concentration of returns in the right tail of the distribution.
    - Determining the percentage of stocks responsible for a significant share of the return value.

4. **Cumulative Return Analysis**:
    - Visualization of cumulative returns for the S&P 500 constituents.
    - Highlighting the 90th percentile.

5. **Weight Analysis**:
    - Comparing the weights assigned to high-performing stocks by both indices, EWI and MWI.

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- NumPy
- SciPy
- Plotly
- statsmodels
- threading
- multiprocessing

## Usage

1. Clone this repository.
2. Open the `MWI_vs_EWI_SP500.ipynb` notebook.
3. Run the cells in each notebook to perform the analysis.

## Conclusion

This analysis reveals that the EWI approach may capture a greater share of returns from high-performing stocks within the S&P 500 index, contributing to its outperformance over the MWI. The distribution of cumulative returns for the constituents is skewed to the right, indicating a concentration of returns in a few stocks.

## Author

Bihlal Zahra
