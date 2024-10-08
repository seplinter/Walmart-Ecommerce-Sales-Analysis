
# Walmart E-Commerce Sales Analysis

This repository contains an analysis project focused on Walmart e-commerce sales data. The main objective of the project is to clean, aggregate, and analyze the data to gain insights into sales patterns and trends.

## Project Structure

- **notebook.ipynb**: The main Jupyter Notebook containing the data cleaning, manipulation, and analysis steps.
- **clean_data.csv**: Cleaned version of the raw data, used for analysis and aggregation.
- **agg_data.csv**: Aggregated sales data, which includes calculations of average weekly sales by month.
- **extra_data.parquet**: Additional data provided in Parquet format, possibly used for extended analysis.
- **walmartecomm.jpg**: An image associated with the project, potentially illustrating the analysis results or related visualizations.

## Requirements

To run the project, you'll need the following dependencies:
- Python 3.x
- Jupyter Notebook
- Pandas
- PyArrow (for handling Parquet files)

You can install the required dependencies using `pip`:

```bash
pip install pandas pyarrow jupyter
```

## Usage

1. **Open the Jupyter Notebook**: Run the `notebook.ipynb` file to see the data cleaning, manipulation, and analysis steps.
   
   ```bash
   jupyter notebook notebook.ipynb
   ```

2. **Data**: The data used in this project includes:
   - `clean_data.csv`: Cleaned data used for the final analysis.
   - `agg_data.csv`: Aggregated sales data based on specific groupings such as month and sales figures.
   - `extra_data.parquet`: Additional data in Parquet format.

## Analysis

The analysis focuses on:
- **Data Cleaning**: Handling missing values, transforming date columns, and filtering sales.
- **Aggregations**: Grouping data by month and calculating average weekly sales.
- **Visualization**: The project likely includes visualizations to represent sales trends and patterns.

