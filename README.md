# 📊Superstore Sales Analysis

This repository contains a comprehensive exploratory data analysis (EDA) notebook for the [Superstore Sales dataset]([https://github.com/JoannJibin/Superstore-Sales-Analysis](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)). The analysis leverages Python's data science stack to inspect, clean, and visualize sales data from a fictional superstore, uncovering business insights and trends.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Setup & How to Run](#setup--how-to-run)
- [Analysis Sections](#analysis-sections)
- [Visualizations](#visualizations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

The notebook `Superstore_sales_analysis.ipynb` demonstrates the following:

- Loading and inspecting the Superstore dataset
- Data cleaning: checking for nulls, duplicates, and fixing data types
- Generating descriptive statistics
- Exploratory Data Analysis (EDA) with insightful visualizations
- Analyzing sales, profit, discount, category, region trends
- Time-series breakdown of monthly sales

---

## Features

- **Easy-to-follow EDA workflow:** From loading data to advanced visualizations
- **Interactive charts:** Sales distribution, profit by region, discount vs profit, sales over time, etc.
- **Clear code comments & markdown explanations**
- **Ready for extension:** You can build on this for machine learning, forecasting, or dashboarding

---

## Requirements

Make sure you have the following installed:

- Python 3 (recommended: 3.7+)
- Jupyter Notebook (or Google Colab)
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

Install dependencies via pip:

```sh
pip install pandas numpy matplotlib seaborn
```

---

## Setup & How to Run

1. **Clone this repository:**

   ```sh
   git clone https://github.com/JoannJibin/Superstore-Sales-Analysis.git
   cd Superstore-Sales-Analysis
   ```

2. **Download the Superstore dataset:**

   - Place `Superstore.csv` in the same directory as the notebook.

3. **Open the notebook:**

   - Run locally:
     ```sh
     jupyter notebook Superstore_sales_analysis.ipynb
     ```
   - Or upload/run in [Google Colab](https://colab.research.google.com/).

4. **Run all cells step-by-step:**

   - Follow the analysis sections; each cell is commented and explained.

---

## Analysis Sections

### 1. Data Loading & Inspection

- Load CSV with pandas
- Display first few rows (`head`)
- Check shape, columns, datatypes, missing values, duplicates

### 2. Data Cleaning

- Convert date columns to datetime
- Verify datatypes
- Ensure no nulls/duplicates

### 3. Descriptive Statistics

- Overview: mean, min, max, quartiles for sales, profit, discount, etc.

### 4. Exploratory Data Analysis (EDA)

- Total Sales & Profit
- Sales Distribution (histogram)
- Sales by Category (barplot)
- Profit by Region (barplot)
- Discount vs Profit (scatterplot with color coding)
- Monthly sales trend (time-series line plot)

### 5. Visualizations

- All plots use `matplotlib` and `seaborn` for clarity and aesthetics
- Each chart includes titles, axes labels, and legends where appropriate

### 6. Insights

- Identify top-performing categories, regions, periods
- Spot relationships between discount and profit
- Understand monthly sales seasonality

---

## Usage

- Use this notebook as a template for your own retail sales analysis
- Modify/extend to include predictive modeling or dashboarding
- Integrate with other datasets for deeper insights

---

## Contributing

Pull requests are welcome! Please open an issue or submit improvements.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Contact

For questions or collaborations, reach out to [JoannJibin](https://github.com/JoannJibin).

---

## Example Outputs

Below are example visualizations you will generate:

- **Sales Distribution Histogram**
- **Total Sales by Category Barplot**
- **Profit by Region Barplot**
- **Discount vs Profit Scatterplot**
- **Monthly Sales Trend Line Plot**

---

## Tips

- If you get an error about missing libraries, run `pip install` as above.
- For very large datasets, consider running in Colab or on a machine with sufficient RAM.
- You can easily adapt the notebook to new data sources by changing the CSV path and relevant column names.

---

Happy analyzing!



