# Titanic Klib EDA

Exploratory Data Analysis (EDA) of the Kaggle Titanic dataset using the Klib library in Jupyter Notebook.

## Project Overview

This project demonstrates a beginner-friendly EDA workflow using Klib, including:

- Loading the Kaggle Titanic `train.csv` dataset
- Checking dataset dimensions and data types
- Identifying missing values
- Visualizing missing values with Klib
- Checking duplicate rows
- Cleaning the dataset using Klib
- Categorical variable analysis with Klib
- Numerical distribution analysis with Klib
- Correlation analysis with Klib
- Correlation analysis against the `Survived` target

## Dataset

The project uses the Kaggle Titanic `train.csv` dataset.

Dataset size:
- 891 rows
- 12 columns

## Tools & Libraries

- Python
- Jupyter Notebook
- Pandas — dataset loading/basic checks
- Klib — automated data cleaning and EDA

## Notebook

Open `Titanic_Klib_EDA.ipynb` to run the complete analysis.

Place `train.csv` in the same directory as the notebook before running it.

## How to Run

1. Install the required libraries:

```bash
pip install pandas klib jupyter
```

2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `Titanic_Klib_EDA.ipynb`.

4. Make sure `train.csv` is in the same folder.

5. Run the notebook cells from top to bottom.

## Project Goal

The goal is to understand how Klib can automate common exploratory data analysis tasks while working with a real-world dataset containing missing values.
