---
layout: default
title: OM 620 - Inventory Analysis and Safety Stock
---

# Milestone 3

## Project Overview

The purpose of these assignments is to analyze historical inventory transactions to better understand demand patterns and inventory requirements through data cleaning, data aggregation, and statistical analysis. Our results can help management make informed decisions about when to increase or reduce inventory levels.

### How to Run

1. Download or clone the repository
2. Install the required Python libraries
3. Open the combined notebook in Jupyter Notebook
4. Run the cells in order

### meta_data.csv description

The meta_data.csv file provides a brief explanation of the features found in the transaction_data.csv file.

### transaction_data.csv Description

Each row in the transaction_data.csv file represents an individual inventory transaction. The dataset contains 742,817 transactions and 9 features.

### Assignment 1

The focus of assignment 1 was to standardizing features, identifying potential outliers, checking for incorrect negative values, and determining how to handle duplicate records. Assignment 1 required us to use our judgment on what to do with duplicate values and how to handle missing values. Question 5 required us to apply data aggregation, calculate sales values, and identify the transactions with the highest and lowest order quantities and sales values.

### Assignment 2

The main focus of assignment 2 was to find the minimum, maximum, mean, median, variance, standard deviation, and average lead time for each SKU. The safety stock was calculated at 75%, 90%, and 95% service levels. Assignment 2 identifies the highest, lowest, and average safety stock values at the 95% service level.

### Key Findings

**Assignment 1**

- Identified 295,343 make-to-stock finished goods transactions
- Identified 400 known SKUs, 18 manufacturing sites, and 54 divisions

**Assignment 2**

- Calculated safety stock for 400 SKUs
- At a 95% service level, the estimated safety stock averaged 121.72 units, with a minimum of 45.51 and a maximum of 366.91 units

  ### Tools and Technologies

- Python
- Pandas
- NumPy
- SciPy
- Jupyter Notebook
