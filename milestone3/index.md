---
layout: default
title: OM 620 - Inventory Analysis and Safety Stock
---

# Milestone 3

## Project Overview

The purpose of these assignments is to analyze historical inventory transactions to better understand demand patterns and inventory requirements through data cleaning, data aggregation, and statistical analysis. Our results can help management make informed decisions about when to increase or reduce inventory levels.

### How to Run

1. Download or clone the repository.
2. Install the required Python libraries.
3. Open the combined notebook in Jupyter Notebook.
4. Run the cells in order

### meta_data.csv description

The meta_data.csv file provides a brief explanation of the features found in the transaction_data.csv file.

### transaction_data.csv Description

Each row in the transaction_data.csv file represents an individual inventory transaction. The dataset contains 742,817 transactions and 9 features.

### Assignment 1

Assignment 1 focuses on standardizing features, identifying potential outliers caused by human error, checking for incorrect negative values, and determining how to handle duplicate records. We decided it was best to keep duplicate records since inventory managers could reorder inventory on the same day to meet demand.

We also had to decide how to handle missing values (NaN). We decided to replace missing categorical values with "Unknown" to avoid removing transactions from the dataset.

For the last few questions, we applied data aggregation, calculated sales values, and identified the transactions with the highest and lowest order quantities and sales values.

### Assignment 2

Assignment 2 focuses on calculating safety stock using the cleaned data from Assignment 1. We decided to exclude transactions with unknown SKU numbers since we could not identify which products they belonged to.

We then applied data aggregation to find the minimum, maximum, mean, median, variance, standard deviation, and average lead time for each SKU.

For the last few questions, we calculated safety stock at 75%, 90%, and 95% service levels. We also identified the highest, lowest, and average safety stock values at the 95% service level. These results can help management decide how much additional inventory is needed to meet demand.

### Key Findings

**Assignment 1**

- Identified 295,343 make-to-stock finished goods transactions.
- Identified 400 known SKUs, 18 manufacturing sites, and 54 divisions.

**Assignment 2**

- Calculated safety stock for 400 SKUs.
- At a 95% service level, the estimated safety stock averaged 121.72 units, with a minimum of 45.51 and a maximum of 366.91 units.

  ### Tools and Technologies

- Python
- Pandas
- NumPy
- SciPy
- Jupyter Notebook
