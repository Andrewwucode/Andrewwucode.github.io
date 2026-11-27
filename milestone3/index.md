---
layout: default
title: OM 620 - Inventory Analysis and Safety Stock
---

# Milestone 3

## Project Overview

Assignments 1 and 2 build upon each other to analyze historical inventory transactions to better understand demand and inventory requirements through data cleaning, data aggregation, and statistical analysis. Our results can help management make informed decisions about when to increase or reduce inventory levels.

### How to Run The Source Code

1. Download or clone the repository
2. Install the required Python libraries
3. Open the combined notebook in Jupyter Notebook
4. Run the cells in order

### meta_data.csv

The meta_data.csv file provides a brief explanation of the features found in the transaction_data.csv file.

### transaction_data.csv

Each row in the transaction_data.csv file represents an individual inventory transaction. The dataset contains 742,817 transactions and 9 different features.

### Assignment 1

The focus of Assignment 1 was to standardize features, identify potential outliers, check for incorrect negative values, and determine how to handle duplicate records. Assignment 1 required us to use our judgment on what to do with duplicate values and how to handle missing values. The last question required us to apply data aggregation, calculate sales values, and identify the transactions with the highest and lowest order quantities and sales values.

Key Findings

- Identified 295,343 make-to-stock finished goods transactions
- Identified 400 known SKUs, 18 manufacturing sites, and 54 divisions

### Assignment 2

The main focus of Assignment 2 was to find the minimum, maximum, mean, median, variance, standard deviation, and average lead time for each SKU. Safety stock was calculated at 75%, 90%, and 95% service levels. Assignment 2 identified the highest, lowest, and average safety stock values at the 95% service level.

Key Findings

- Calculated safety stock for 400 SKUs
- At a 95% service level, the estimated safety stock averaged 121.72 units, with a minimum of 45.51 and a maximum of 366.91 units

  ### Tools and Technologies

- Python
- Pandas
- SciPy
