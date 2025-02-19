# Blinkit-Orders-Analysis-

# Blinkit Sales Analysis

This repository contains a Jupyter notebook (`Blinkit_sales_analysis.ipynb`) that performs an analysis of sales data from Blinkit, an online grocery delivery service. The analysis includes data extraction, data cleaning, exploration, and visualization to gain insights into sales trends, delivery status, and payment methods.

## Dataset

The dataset used in this analysis consists of two CSV files:
1. `blinkit_orders.csv`: Contains information about customer orders, including order details, delivery status, and payment methods.
2. `blinkit_order_items.csv`: Contains details about the items in each order, including product IDs, quantities, and unit prices.

## Analysis Steps

1. **Data Extraction**: The dataset is extracted from a ZIP file and loaded into Pandas DataFrames.
2. **Data Exploration**: Basic exploration of the dataset is performed to understand the structure and content of the data.
3. **Data Cleaning**: The dataset is cleaned by converting date columns to the appropriate datetime format.
4. **Data Merging**: The two datasets are merged on the `order_id` column to create a combined dataset for analysis.
5. **Visualization**: Various visualizations are created to analyze the distribution of delivery statuses and payment methods.

## Key Insights

- **Delivery Status Distribution**: The majority of orders are delivered on time.
- **Payment Method Distribution**: The most common payment methods are Cash, UPI, and Card.

## Requirements

To run the notebook, you will need the following Python libraries:
- `pandas`
- `matplotlib`
- `seaborn`

You can install these libraries using pip:

```bash
pip install pandas matplotlib seaborn
