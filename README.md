# UNC Data Analytics Module 19: Unsupervised Learning

## Cryptocurrency Market Data Analysis

### Overview

This Jupyter Notebook analyzes cryptocurrency market data using various techniques such as data visualization, K-Means clustering, and Principal Component Analysis (PCA). It aims to provide insights into the behavior and trends of different cryptocurrencies based on their price change percentages.

### Requirements

Ensure you have the following libraries installed:

- pandas
- hvplot
- scikit-learn

You can install them via pip: 

'pip install pandas hvplot scikit-learn'

### Files Included

- **Crypto_clustering.ipynb**: Jupyter Notebook using K-Means clustering and PCA analysis to analyze cryptocurrency data.
- **Resources/cypto_market_data.csv**: CSV file with information on percentage changes of various cryptocurrenices over different time frames.

### Usage

1. Clone the repository to your local machine.
2. Execute the code in the `Crypto_clustering.ipynb` to see visualizations.

### Insights

Analyzing 41 different cryptocurrencies, focusing on price change percentages ranging from a single day to a year, revealed that the optimal K-Means value for both the scaled data and PCA data was 4. Through PCA analysis, the clusters appeared to be more tightly aggregated.