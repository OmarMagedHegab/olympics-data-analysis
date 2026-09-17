# Olympics Historical Data: Cleaning & Exploratory Data Analysis (EDA)

## Overview
This project demonstrates a complete data processing pipeline using a massive historical dataset of the Olympic Games (over 270,000 athlete records). The primary goal of this notebook is to transform messy, incomplete raw data into a clean, structured format and extract actionable visual insights.

## Key Features & Workflow
* **Automated Data Ingestion:** Utilizes the `kagglehub` API to automatically download the latest dataset directly from Kaggle servers. This eliminates the need for manual `.csv` file handling and ensures full reproducibility.
* **Advanced Data Cleaning:** Addressed significant missing data (Null values) in sensitive columns like Age, Height, and Weight using intelligent grouping and statistical imputation, rather than dropping valuable records.
* **Exploratory Data Analysis (EDA):** Uncovered hidden trends, such as historical participation growth, gender distribution across different eras, and top-performing demographics.
* **Data Visualization:** Built clear, professional charts and graphs to translate complex numerical data into easily digestible visual reports.

## Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## How to Run This Project
1. Clone this repository or download the `.ipynb` file.
2. Open the notebook in **Jupyter Notebook** or **Google Colab**.
3. Run all cells. The first cell will automatically download the required dataset via the Kaggle API—no manual CSV downloads required.
