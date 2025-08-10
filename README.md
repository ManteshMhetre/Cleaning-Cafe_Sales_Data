# Cleaning Cafe Sales Data

This repository contains a dataset cleaning workflow for cafe sales data. The project demonstrates how to transform a raw CSV dataset into a clean, analysis-ready format using Python in a Jupyter Notebook.

## Repository Structure

├── dirty_cafe_sales.csv          # Raw dataset with duplicates, missing values, and inconsistent formatting
├── data cleaning.ipynb           # Jupyter Notebook for cleaning the dataset
├── cleaned_cafe_sales_data.csv   # Cleaned dataset after preprocessing
└── README.md                     # Project documentation

## Overview

The dataset cleaning process includes:
1)Removing duplicates to ensure data integrity.
2)Handling missing values by applying appropriate imputation or removal strategies.
3)Formatting columns for consistency (e.g., date formats, capitalization, removing extra spaces).

##Requirements
To run the notebook, install the following Python libraries:
pip install pandas numpy

## Usage
1)Clone the repository:

git clone https://github.com/your-username/your-repo-name.git

2)Open the Jupyter Notebook:

jupyter notebook "data cleaning.ipynb"

3) Run all cells to:
Load dirty_cafe_sales.csv
Clean and preprocess the data
Export the cleaned dataset to cleaned_cafe_sales_data.csv

##Output

The output file cleaned_cafe_sales_data.csv contains:
No duplicate rows
Missing values handled appropriately
Properly formatted column names and values

##License
This project is licensed under the MIT License.
