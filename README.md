# Superstore Sales Analysis

This project analyzes sales data from a fictional Superstore to uncover insights about sales, profits, discounts, and other business metrics using Python data science tools. The analysis includes basic data exploration, cleaning, visualization, and clustering techniques.

## Project Overview

- **Data Source:** `Superstore.csv` (21 columns, 9994 rows)
- **Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn
- **Main Notebook:** [`Superstore_sales_analysis.ipynb`](Superstore_sales_analysis.ipynb)

## Key Steps

1. **Data Loading & Inspection**
   - Load dataset using Pandas
   - View the shape, column names, and data types
   - Generate descriptive statistics
   - Check for missing/null values

2. **Data Cleaning**
   - Confirm no missing values in the dataset
   - Inspect and understand data types and distributions

3. **Exploratory Data Analysis (EDA)**
   - Visualize sales, profits, discounts, and quantities
   - Analyze patterns by region, category, segment, etc.
   - Identify top/bottom performing products and regions

4. **Clustering & Advanced Analysis**
   - Standardize data and apply clustering (e.g., KMeans)
   - Visualize clusters in 2D/3D plots

## Why Clustering Was Used

Clustering was applied to the Superstore sales data to group similar records (such as customers, orders, or products) based on features like sales, profit, and discount. The main reasons for using clustering are:

- **To identify distinct customer segments:** Clusters reveal groups of customers with similar purchasing behavior or profitability.
- **To spot regions or products with similar performance:** Uncover which products or regions behave alike in terms of sales and profit.
- **To support targeted business strategies:** Help the business understand where to focus marketing, sales, or discounting efforts.

## What We Inferred From Clustering

- **Distinct Groups:** The clustering revealed that the data could be divided into groups with unique characteristics (e.g., high-profit vs. low-profit segments, high-discount vs. no-discount sales).
- **Business Insights:** These groups allowed us to see which clusters contributed most to profit, which ones were affected by discounting, and where potential improvements could be made.
- **Actionable Patterns:** For example, a cluster with high sales but low profit might indicate that discounts are too deep or costs are high, suggesting a need to adjust pricing or promotions for that segment.

**Summary:**  
Clustering provided a data-driven way to segment and analyze the Superstore’s sales, leading to actionable insights on customer behavior, product and region performance, and the impact of discounts, which can guide future business decisions.

## Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/JoannJibin/Superstore-Sales-Analysis.git
   cd Superstore-Sales-Analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Run the notebook**
   - Open `Superstore_sales_analysis.ipynb` in Jupyter Notebook or Google Colab.
   - Run cells sequentially to reproduce the analysis.

## File Structure

```
├── Superstore_sales_analysis.ipynb  # Main analysis notebook
├── Superstore.csv                   # Dataset
└── README.md                        # Project documentation
```

## Features

- **Comprehensive EDA:** Summaries, distributions, and visualizations of key metrics.
- **No Missing Data:** Dataset is clean and ready for analysis.
- **Clustering:** Segment sales data for deeper business insights.
- **Visualization:** Use Matplotlib and Seaborn for clear, informative plots.

## Example Insights

- Identify most profitable products and regions
- Find sales trends across time, segments, and categories
- Discover patterns in discounting and its impact on profit

## Contributing

Pull requests, suggestions, and issues are welcome! Please open an issue or submit a PR to improve the analysis.

## License

This project is released under the [MIT License](LICENSE).

## Author

- Joann Jibin
