# Used Car Price Exploratory Data Analysis

## Project Overview

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on a used car dataset to understand the key factors influencing used car prices.

The analysis covers:
- Data understanding and quality assessment
- Data cleaning and preprocessing
- Univariate and bivariate analysis
- Feature engineering
- Statistical hypothesis testing
- Business-oriented insights

The goal of this project is to demonstrate a **structured EDA workflow** and extract meaningful insights from real-world data.

---

## Dataset Information

- **Source:** Kaggle (Used Cars Dataset – Cardekho)
- **Rows:** 8,128
- **Columns:** 12 (expanded to 17 with feature engineering)
- **Target Variable:** `selling_price`

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## Project Structure

```text
eda-project/
│
├── data/
│   ├── raw/                 # Original dataset
│   ├── interim/             # Cleaned dataset (Day 2)
│   └── processed/           # Final dataset (Day 4)
│
├── notebooks/
│   ├── 01_data_overview.ipynb
│   ├── 02_cleaning_preprocessing.ipynb
│   ├── 03_univariate_bivariate_eda.ipynb
│   └── 04_stats_time_features_final_insights.ipynb
│
├── reports/
│   └── figures/             # Exported plots
│
└── README.md

```

---

## Instructions to Run

**1. Clone the repository**
    
    git clone "https://github.com/irfan-mohamed/eda-project.git"
    
## 2. Run notebooks in sequence

* 01_data_overview.ipynb

* 02_cleaning_preprocessing.ipynb

* 03_univariate_bivariate_eda.ipynb

* 04_stats_time_features_final_insights.ipynb

## 3. Final processed dataset Located at: 
data/processed/final_cleaned_day4.csv

---

## Key Insights

* Selling price is strongly influenced by vehicle age and usage.

* Automatic and diesel cars generally have higher resale values.

* Ownership history plays a significant role in pricing.

* Luxury brands retain value better over time.

---

## Limitations

* Dataset represents listed vehicles and may not reflect the entire market. 
* Vehicle condition and location-specific effects are not fully captured. 
* Some categories have low representation.

