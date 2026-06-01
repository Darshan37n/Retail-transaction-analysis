# Retail Transaction Analysis

I explored a retail dataset to understand customer buying behavior — who spends the most,
when sales peak, and which customers are at risk of churning.

## What's in this project?

Two datasets were used:
- **Retail_Data_Transactions.csv** — contains individual transaction records
- **Retail_Data_Response.csv** — contains whether each customer churned or not

## What I did

**Cleaned the data first**
Merged both datasets, handled missing values, fixed data types,
and checked for outliers using Z-score method.

**Explored the data**
Found the top customers by number of orders and by total spend.
Also looked at which months had the highest sales.

**Time Series Analysis**
Plotted monthly sales over time to spot trends and seasonal patterns.

**Customer Segmentation (RFM)**
Grouped customers into 3 tiers based on how recently they bought,
how often they buy, and how much they spend:
- **P0** → High-value, loyal customers
- **P1** → Mid-tier customers
- **P2** → Low engagement / at-risk customers

**Churn Analysis**
Checked how many customers are active vs churned,
and tracked spending trends of the top customers over time.

## Tools used
Python, Pandas, Matplotlib, Seaborn, Scipy

## How to run
Open the `.ipynb` file in Jupyter Notebook or VS Code and run the cells top to bottom.
Make sure both CSV files are in the same folder as the notebook.
