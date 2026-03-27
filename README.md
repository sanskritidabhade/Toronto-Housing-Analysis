# Toronto Housing Analysis

Exploratory data analysis of Toronto residential housing listings, focusing on price distributions and the relationship between bedroom count and listing price.

---

## Overview

This project uses two Kaggle datasets — one specific to Toronto and one covering the top 45 Canadian cities — to examine how housing prices are distributed and what role bedroom count plays in pricing. The analysis covers data cleaning, descriptive statistics, and several visualizations.

---

## Dataset

| File | Description |
|------|-------------|
| `Toronto_Housing_Prices_Kaggle.csv` | Toronto-specific housing listings |
| `HouseListings-Top45Cities-10292023-kaggle.csv` | Listings across 45 major Canadian cities (used for context) |
| `toronto_housing_cleaned.csv` | Cleaned version used for analysis |

Source: [Kaggle](https://www.kaggle.com/)

---

## Analysis

The notebook (`Assignment1_Toronto_Housing.ipynb`) walks through:

- **Data cleaning** — handling missing values, filtering to Toronto listings, standardizing columns
- **Descriptive statistics** — summary stats and per-bedroom breakdowns (`summary_statistics.csv`, `bedroom_statistics.csv`)
- **Price distribution** — histogram (PDF) and cumulative distribution (CDF) of listing prices
- **Bedroom vs. price relationship** — boxplots, scatter plots, and mean price by bedroom count
- **Correlation heatmap** — numeric feature correlations

---

## Visualizations

| File | Description |
|------|-------------|
| `1_price_histogram_pdf.png` | Price distribution (PDF) |
| `2_price_cdf.png` | Cumulative distribution of prices |
| `3_price_by_bedrooms_boxplot.png` | Price spread by bedroom count |
| `4_price_vs_bedrooms_scatter.png` | Scatter plot of price vs. bedrooms |
| `5_mean_price_by_bedrooms_bar.png` | Mean listing price per bedroom category |
| `6_correlation_heatmap.png` | Correlation matrix of numeric features |

---

## Requirements

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

## Usage

```bash
git clone https://github.com/sanskritidabhade/Toronto-Housing-Analysis.git
cd Toronto-Housing-Analysis
jupyter notebook Assignment1_Toronto_Housing.ipynb
```

---

## Repository Structure

```
Toronto-Housing-Analysis/
├── Assignment1_Toronto_Housing.ipynb   # Main analysis notebook
├── Toronto_Housing_Prices_Kaggle.csv
├── HouseListings-Top45Cities-10292023-kaggle.csv
├── toronto_housing_cleaned.csv
├── summary_statistics.csv
├── bedroom_statistics.csv
└── *.png                               # Generated plots
```
