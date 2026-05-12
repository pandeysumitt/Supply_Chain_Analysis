# Supply_Chain_Analysis
# Overview
Analyzed supply chain operations to identify inefficiencies in inventory, suppliers, and logistics. This project transforms raw data into actionable insights that improve demand planning, reduce costs, and enhance delivery performance.

# Business Problem
Actual shipping times frequently deviate from scheduled delivery windows, creating eroded customer trust, reduced order profitability, and an inability to make reliable commitments to buyers at point of purchase.

# Analytical Objectives
* Understand the current state of delivery performance across all dimensions(region, mode, time, segment)
* Quantify the financial immpact of delays on order profitability.
* Identify the primary operational bottlenecks driving late deliveries.
* Build a predictive model to flag high_risk orders before they are shipped.
* Deliver actionable recommendations to improve on-time delivery and profitability.

# Tech Stack
* Python (Pandas, Numpy)
* Data Visualization (Matplotlib, Seaborn)
* Jupyter Notebook

# Data Processing & Cleaning
The analysis involved a rigorous cleaning pipeline to ensure reliable insights:
* Feature Engineering: Standardized date formats for order date and shipping date to calculate real vs. scheduled shipping durations.
* Data Refinement: Removed over 30 redundant or high-cardinality features (e.g., Customer Email, Product Image, Zipcodes) to focus on impactful variables.
* Noise Reduction: Filtered out "Shipping Canceled" orders to prevent skewed performance metrics.

# Project Structure
*  Exploratory Data Analysis (EDA): Profiling the dataset (129,519 rows, 20 optimized columns) to understand the distribution of delivery statuses.
* Profitability Analysis: Examining the relationship between Order Item Profit Ratio and Late_delivery_risk.
* Visualization: Using Seaborn and Matplotlib to create professional-grade heatmaps and trend charts for regional performance.

# How to Run
* Ensure you have the datasetsupply.csv file available in your environment.
* Install the required dependencies: pip install pandas numpy matplotlib seaborn
* Open SupplyChainAnalysis.ipynb and execute the cells sequentially to reproduce the findings.

