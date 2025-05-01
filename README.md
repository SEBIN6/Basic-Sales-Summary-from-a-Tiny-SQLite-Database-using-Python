# Sales Analysis Project

## Overview
This project performs sales data analysis using a SQLite database, Python, pandas, and matplotlib. It creates a SQLite database, populates it with sample sales data, queries the data to compute total quantity and revenue per product, and visualizes the results in a bar chart. The code is implemented in a Jupyter notebook designed to run in Google Colab.

## Files
- **`sales_analysis.ipynb`**: Jupyter notebook containing the Python code for:
  - Creating and populating a SQLite database (`sales_data.db`).
  - Querying the database to summarize sales data.
  - Printing the sales summary (total quantity and revenue per product).
  - Generating and saving a bar chart (`sales_chart.png`).
- **`sales_data.db`**: SQLite database with the `sales` table containing sample data (products, quantities, prices).
- **`sales_chart.png`**: Bar chart visualizing total revenue by product.

## Requirements
To run the notebook, you need:
- Google Colab (or a local Jupyter environment with Python).
- Python libraries: `sqlite3`, `pandas`, `matplotlib` (pre-installed in Colab).

## Instructions
1. **Open in Google Colab**:
   - Upload `sales_analysis.ipynb` to [Google Colab](https://colab.research.google.com/).
   - Alternatively, download the repository and open the notebook locally in Jupyter.

2. **Run the Notebook**:
   - Execute all cells in the notebook (`Ctrl + Enter` or **Run All**).
   - The script will:
     - Create `sales_data.db` with a `sales` table and sample data.
     - Query the database to compute total quantity and revenue per product.
     - Print the sales summary.
     - Generate and display a bar chart.
     - Save the chart as `sales_chart.png`.

3. **Verify Output**:
   - **Printed Output**:
