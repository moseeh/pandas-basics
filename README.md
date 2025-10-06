# Pandas Basics

A comprehensive collection of Jupyter notebooks demonstrating data analysis and manipulation using pandas, numpy, and other data science libraries.

## Repository Information

- **Repository**: [pandas-basics](https://github.com/moseeh/pandas-basics)
- **Learn Zone01 Kisumu**: [pandas](https://learn.zone01kisumu.ke/git/moonyango/pandas.git)

## Overview

This repository contains practical exercises and examples for learning pandas fundamentals through hands-on data analysis projects. Each notebook focuses on different aspects of data manipulation, cleaning, and analysis using real-world datasets.

## Contents

### Notebooks

1. **Notebook_ex01.ipynb** - DataFrame Creation and Basic Operations
   - Creating DataFrames from numpy arrays and pandas Series
   - Understanding data types and column operations
   - Basic DataFrame manipulation techniques

2. **Notebook_ex02.ipynb** - Household Power Consumption Analysis
   - Loading and processing large datasets (2M+ rows)
   - Data cleaning and type conversion
   - Missing value handling with dropna()
   - Date parsing and indexing
   - Data filtering and aggregation
   - Time series resampling

3. **Notebook_ex03.ipynb** - E-commerce Purchase Analysis
   - Customer purchase behavior analysis
   - Data exploration and statistical summaries
   - String manipulation and extraction
   - Conditional filtering and value counting
   - Data aggregation by categories

4. **Notebook_ex04.ipynb** - Missing Value Handling Strategies
   - Different approaches to handling missing data
   - Comparison of mean, median, and zero-fill strategies
   - Discussion of bias implications in data imputation
   - Best practices for missing value treatment

### Datasets

- **iris.csv** (5KB) - Classic iris flower dataset for classification analysis
- **Ecommerce_purchases.txt** (2.7MB) - Synthetic e-commerce transaction data
- **household_power_consumption.txt** (127MB) - Real household power consumption measurements

## Prerequisites

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

### Key Dependencies
- pandas 2.3.3
- numpy 2.3.3
- jupyter
- matplotlib-inline

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/moseeh/pandas-basics.git
cd pandas-basics
```

2. Create and activate a virtual environment:
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Linux/Mac:
source venv/bin/activate
# On Windows:
# venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

5. Open any of the notebook files to start exploring the examples.

## Learning Objectives

Through these notebooks, you will learn:

- **Data Loading**: Reading data from CSV files and text files
- **Data Cleaning**: Handling missing values, data type conversion
- **Data Manipulation**: Filtering, sorting, grouping, and aggregating data
- **Time Series**: Working with datetime indices and resampling
- **Statistical Analysis**: Computing descriptive statistics and summaries
- **Best Practices**: Understanding the implications of different data handling strategies

## Key Concepts Covered

- DataFrame and Series creation and manipulation
- Data type handling and conversion
- Missing value strategies and their implications
- Date/time parsing and indexing
- Conditional filtering and boolean indexing
- String operations and data extraction
- Statistical computations and aggregations
- Time series analysis and resampling

## Contributing

Feel free to submit issues or pull requests to improve the examples or add new learning materials.

## License

This project is for educational purposes as part of the Zone01 curriculum.