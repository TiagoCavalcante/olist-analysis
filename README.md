# Olist E‑Commerce EDA

**Project for the Introduction to Data Science course at NES**

This repository contains an exploratory data analysis project on the public Brazilian E‑Commerce dataset provided by Olist. It was developed as part of the *Introduction to Data Science* course at NES.

## 🌟 Features

* **Data Loading:** Reads and parses nine separate CSV tables using Pandas.
* **Data Cleaning & Engineering:** Computes delivery times, total order values, merges customer and review information, and enriches order items with category and geographic details.
* **Cohort Analysis:** Calculates customer retention rates for monthly cohorts.
* **Revenue Heatmap:** Aggregates revenue by product category and customer state.
* **Payment Share Over Time:** Analyzes the share of different payment methods across months.
* **Visualizations:** Generates four high-quality charts:

  1. Monthly repeat-purchase rate
  2. Category × State revenue heatmap
  3. Delivery time vs. review score boxplot
  4. Stacked area chart of payment type share

## 📂 Repository Structure

```
├── data/                # Raw CSV files (download from Kaggle)
├── figures/             # Generated PNG visualizations
├── olist_eda.ipynb      # Jupyter notebook with the analysis
└── README.md            # Project overview and instructions
```

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/olist-eda.git
   cd olist-eda
   ```

2. **Install dependencies**

   ```bash
   pip install pandas matplotlib
   ```

3. **Run the analysis**

   ```bash
   jupyter notebook olist_eda.ipynb
   ```

4. **View results**

   * Charts and figures will be saved under `figures/`.
   * Outputs show quick stats and diagnostics.
