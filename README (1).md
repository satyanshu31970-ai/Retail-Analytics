# Customer Segmentation and Retail Business Analysis Using RFM

## Project Overview
This project analyses historical retail transaction data to understand customer purchasing behaviour, identify valuable customer groups, and support data-driven marketing decisions. It uses **RFM analysis** to segment customers based on how recently and frequently they purchased and how much they spent.

## Objectives
- Clean and prepare the retail transaction dataset.
- Explore revenue trends and sales patterns.
- Identify top products and countries by revenue.
- Calculate Recency, Frequency, and Monetary values for each customer.
- Segment customers using RFM scores.
- Recommend practical marketing actions for each customer segment.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- GitHub

## Project Workflow
1. Data collection and loading
2. Data cleaning and preparation
3. Exploratory Data Analysis (EDA)
4. Monthly revenue trend analysis
5. Product and country revenue analysis
6. RFM calculation and scoring
7. Customer segmentation
8. Revenue analysis by customer segment
9. Business recommendations and conclusion

## Dataset
The project uses the **Online Retail** transaction dataset. The dataset contains invoice, product, quantity, transaction date, unit price, customer ID, and country information.

The notebook uses positive-quantity, positive-unit-price transactions for sales and RFM analysis. Cancelled invoices and records without customer IDs are excluded from customer-level RFM analysis. Therefore, the revenue figures represent the filtered historical sales data rather than net revenue after returns.

**Note:** The notebook may require the dataset to be placed in the correct local folder or its file path to be updated. Do not upload the dataset to GitHub unless its licence permits redistribution.

## Key Findings
- The cleaned data used for RFM analysis contains **392,692 transaction rows**.
- The analysis identifies **4,338 unique customers** for RFM segmentation.
- The filtered dataset records total revenue of approximately **£8.89 million**.
- **Champions** are the highest-revenue segment, contributing approximately **£5.74 million**.
- **Needs Attention** is the largest segment, with **1,074 customers** (approximately **24.76%** of the customers analysed).

These findings describe the historical dataset and should not be interpreted as current customer behaviour.

## Repository Contents
- `Customer_Segmentation_RFM.ipynb` — Jupyter Notebook containing the analysis, charts, tables, and recommendations.
- `README.md` — Project overview and instructions.

If you include the dataset in the repository, add its filename here as well.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Download or obtain the Online Retail dataset from an authorised source.
4. Update the dataset path in the notebook to match your computer, or use a relative path if the CSV is stored in the repository.
5. Open and run `Customer_Segmentation_RFM.ipynb` from top to bottom.

## Limitations
- The dataset contains historical transactions from 2010–2011.
- Transactions with non-positive quantities or unit prices are excluded from the sales analysis.
- Records without customer IDs cannot be included in customer-level RFM segmentation.
- Customer segments are based on the scoring rules defined in the notebook.

## Future Improvements
- Test the segmentation on more recent transaction data.
- Compare customer segments over time.
- Evaluate whether targeted campaigns improve repeat purchases and customer retention.

## Author
PGDM — Business Analytics Project
