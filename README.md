# Housing Market Prediction

Predicting Demand and Supply of Housing Markets in the United States using PySpark and Machine Learning.

## Project Overview

This project aims to predict housing market conditions (buyers' market, sellers' market, or neutral market) using machine learning techniques and PySpark. We analyze multiple factors including:
- Housing market metrics from Zillow
- Building permits data
- Treasury bill rates
- Bank failure information

## Data Sources

- Zillow Research Data: https://www.zillow.com/research/data/
- Building Permits: https://www.census.gov/construction/bps/historical/state_units.html
- Treasury Bill Rates: https://home.treasury.gov/resource-center/data-chart-center/interest-rates/
- Bank Failures: https://catalog.data.gov/dataset/fdic-failed-bank-list

## Project Structure

```
housing-market-prediction/
├── data/               # Data files
├── notebooks/         # Jupyter notebooks
├── src/               # Source code
├── docs/             # Documentation
└── requirements.txt  # Project dependencies
```

## Key Features

- Multi-source data integration using PySpark
- Machine learning models:
  - Logistic Regression
  - Random Forest
  - Naive Bayes
- Handling class imbalance
- Seasonal trend analysis
- Geographic market variation analysis

## Results

- Achieved over 80% accuracy in market condition prediction
- Logistic Regression performed best with:
  - 87% precision for sellers' market
  - 85% precision for buyers' market
- Successfully identified seasonal patterns in market behavior

## Setup and Installation

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/housing-market-prediction.git
cd housing-market-prediction
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

## Contributors

- Aadit Malikayil
- Bhavika Karale
- Kapil Tare
- Shreyas Kashyap
