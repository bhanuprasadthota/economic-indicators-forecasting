# Economic Indicators Forecasting

Machine learning analysis and time series forecasting on macroeconomic indicators. This project applies PCA for dimensionality reduction, K-Means clustering for segmentation, and ARIMA for forecasting economic trends.

## Overview

This project takes a multi-technique approach to economic data analysis — reducing complexity with PCA, discovering patterns with clustering, and predicting future values with ARIMA time series models.

## Techniques Used

- Data cleaning and missing value imputation
- Principal Component Analysis (PCA)
- K-Means Clustering
- Linear & Logistic Regression
- ARIMA Time Series Forecasting
- Seasonal Decomposition

## Dataset

- **Source:** Economic Indicators Dataset (CSV)
- **Features:** Macroeconomic variables including GDP-related indicators, employment, and financial metrics

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| pandas | Data manipulation |
| NumPy | Numerical operations |
| scikit-learn | PCA, clustering, regression |
| statsmodels | ARIMA, seasonal decomposition |
| matplotlib | Visualization |
| Jupyter Notebook | Analysis environment |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/bhanuprasadthota/economic-indicators-forecasting.git
   cd economic-indicators-forecasting
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib scikit-learn statsmodels jupyter
   ```

3. Place the dataset file `economic-indicators.csv` in the project root.

4. Launch the notebook:
   ```bash
   jupyter notebook MTH_Project3.ipynb
   ```

## Key Findings

- Used PCA to reduce high-dimensional economic data while retaining variance
- Clustered economic periods into distinct regimes using K-Means
- Built ARIMA models to forecast key economic indicators
- Applied seasonal decomposition to separate trend, seasonality, and residual components

## License

MIT License — see [LICENSE](LICENSE) for details.
