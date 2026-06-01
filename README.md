# Bengaluru House Price Prediction 🏠📉
This repository contains the data engineering, cleaning, and exploratory data analysis (EDA) pipeline for real estate data in Bengaluru. The goal of this project is to take raw, messy housing data and transform it into a pristine, outlier-free dataset ready for machine learning model training.

# 🚀 Project Overview
- Objective: Clean and preprocess a real estate dataset containing 13,320 records to eliminate anomalies and handle missing values.
- Dataset: `Bengaluru_House_Data.csv` (9 features detailing location, size, total square feet, bath, price, etc.)

# 🛠️ Data Pipeline & Workflow
1. Handling Missing Values: Imputed the data-driven median for missing `bath` and `balcony` values, and the mode for missing `size` counts.
2. Text & Data Normalization: Standardized location formatting and utilized Regex to clean and transform the string-based `total_sqft` column into numeric floats.
3. Outlier Mitigation: Isolated and stripped extreme variance anomalies at the 1st and 99th percentiles to protect future modeling algorithms from skew and bias.
4. Exploratory Data Analysis (EDA): Generated descriptive statistics and statistical distribution visualizations using `Seaborn` and `Matplotlib`.

# 🧰 Tech Stack
- Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Regex

# ⚙️ How to Run
1. Clone this repository:
```bash
   git clone [https://github.com/Itemabo/bengaluru-house-price-prediction.git](https://github.com/Itemabo/bengaluru-house-price-prediction.git)
```
2. Install dependencies:
pip install pandas numpy matplotlib seaborn
3. Open the Jupyter Notebook inside the notebooks/ directory and run the cells.
