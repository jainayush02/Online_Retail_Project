# Online Retail Analysis

This project analyzes an online retail dataset using Python, Pandas, NumPy, and Matplotlib. The dataset contains transaction data from an online retailer, and the Jupyter notebook (`Online_Retail.ipynb`) performs data cleaning and basic exploratory data analysis.

## Project Overview

The dataset (`Copy of online_retail_II.csv`) includes details of transactions such as invoice numbers, quantities, prices, customer IDs, and invoice dates. The notebook:
- Loads and inspects the dataset.
- Removes unnecessary columns (`Description`, `Country`, `StockCode`).
- Handles missing values in the `Customer ID` column.
- Provides a foundation for further analysis (e.g., sales trends, customer behavior).

## Dataset

- **File**: `Copy of online_retail_II.csv`
- **Source**: The dataset is based on the "Online Retail II" dataset, commonly available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II) or similar sources.
- **Columns** (before cleaning):
  - `Invoice`: Invoice number
  - `StockCode`: Product code
  - `Description`: Product description
  - `Quantity`: Number of items purchased
  - `InvoiceDate`: Date and time of the transaction
  - `Price`: Unit price
  - `Customer ID`: Unique customer identifier
  - `Country`: Country of the customer
- **Note**: The dataset may be large (over 500,000 rows). If not included in the repository due to size, download it from the source or contact the repository owner for a link.

## Requirements

To run the notebook, you need the following Python packages:
- Python 3.x
- Pandas
- NumPy
- Matplotlib

Install the dependencies using pip:
```bash
pip install pandas numpy matplotlib
