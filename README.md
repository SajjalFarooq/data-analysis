# Data Analysis with Pandas — Complete Guide

A beginner-friendly Python notebook covering pandas completely, step by step. Every new code type in this notebook is explained with a mini definition in the text above it, and with proper comments inside the code, so every beginner can understand why each piece of code is used.

This is the next notebook in the series, after Python Basics and Object-Oriented Programming.

## What this notebook covers

- Series — one column of data
- DataFrame from a dictionary
- Reading a CSV file
- Viewing data: head, tail, shape, columns, info
- Descriptive statistics with describe
- Selecting columns and rows with loc and iloc
- Filtering rows with a condition
- Sorting data
- Adding, renaming and dropping columns
- Handling missing values: isna, fillna and dropna
- Removing duplicates
- Grouping and aggregation with groupby and agg
- Value counts
- Apply: running a function on every value
- Merging two DataFrames
- Pivot table
- Creating a bar chart

## Comments and mini definitions

This notebook follows a strict rule: no new code type is used without an explanation. Each section starts with a mini definition in plain English, and the code itself contains comments explaining why that code is there, for example why `loc` uses labels while `iloc` uses positions, and why missing values are filled or dropped.

## Executed notebook

This notebook was executed before upload, so every code cell shows its real output on GitHub. You can see the result of each example without running the code yourself.

GitHub itself does not run code. To run this notebook yourself, use one of these options:

- **Jupyter Notebook / JupyterLab:** Download the notebook and run all cells.
- **VS Code:** Open the notebook in VS Code with the Python extension and run all cells.
- **Google Colab:** Upload the notebook to Colab and run all cells.

## Requirements

- Python 3
- pandas, matplotlib and numpy

Install them with:

```bash
pip install pandas matplotlib numpy
```

## Files

- `data-analysis.ipynb` — the executed notebook with code, comments, mini definitions and outputs
- `students.csv` — the data file used in the reading CSV example
- `average-marks-by-field.png` — the bar chart created in the chart section
- `README.md` — this file

## Next steps

The next notebook in this series will cover machine learning, building on this data analysis work one step at a time.
