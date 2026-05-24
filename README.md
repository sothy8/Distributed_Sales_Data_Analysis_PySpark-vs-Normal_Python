# Distributed Sales Data Analysis (PySpark vs Pandas)

This project compares distributed processing with PySpark against single-machine processing with pandas using a grocery sales dataset. The notebook covers data loading, cleaning, basic analytics, visualizations, and a simple timing comparison.

## Contents

- Notebook: [Sale_Analysis.ipynb](Sale_Analysis.ipynb)
- Dataset: [grocerySale.csv](grocerySale.csv)

## Requirements

- Python 3.9+ recommended
- Java 8+ (required by Spark)
- PySpark
- pandas
- matplotlib

## Run the notebook

1. Open [Sale_Analysis.ipynb](Sale_Analysis.ipynb) in VS Code or Jupyter.
2. Run cells in order from top to bottom.
3. The notebook includes both PySpark and pandas sections, plus visualizations.

## What the notebook does

- Loads the CSV into Spark and pandas
- Cleans missing values and duplicates
- Normalizes category labels
- Computes totals, averages, and top outlets
- Builds multiple charts for comparison
- Compares timing for Spark vs pandas

## Notes

- Spark requires Java; make sure `JAVA_HOME` is set if Spark fails to start.
- The pandas section reuses the dataset locally; it is best for smaller data.
- The Spark section is designed for larger data and distributed processing.
