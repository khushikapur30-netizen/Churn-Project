# Superstore Sales Analysis & Customer Segmentation

Analysis of the Superstore sales dataset: sales and profit trends, loss-making areas, customer segmentation, and loss prediction.

## What's inside
- **Sales analysis:** total sales, profit, margin, YoY growth, monthly trend
- **Profit insights:** sales by region, profit by sub-category, impact of discounts
- **Customer segmentation:** RFM analysis + K-Means clustering (Champions, Loyal, At Risk, Needs Attention)
- **Loss prediction:** Random Forest model to predict loss-making orders and show what drives them

## Data
[Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Tools
Python, pandas, NumPy, matplotlib, scikit-learn

## How to run
1. Download the dataset and update the file path in the notebook.
2. Install requirements: `pip install pandas numpy matplotlib scikit-learn`
3. Open `superstore_analysis.ipynb` in Jupyter and run all cells.

## Output
- `superstore_clean.csv` – cleaned data
- `superstore_customer_segments.csv` – customer segments (usable in Power BI)
