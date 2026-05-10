# Housing Price Forecasting via Time Series & VAR Analysis

**Tools:** R · Quarto · Time Series Forecasting · VAR · FRED API · fredr · dplyr · ggplot2

---

## Business Problem

Housing markets are heavily influenced by macroeconomic conditions, supply trends, and long-term market cycles. This project analyzes historical housing price growth and housing starts to better understand market relationships and improve forecasting accuracy.

The objective was to evaluate how housing supply activity relates to national housing price trends using both univariate and multivariate time series techniques.

---

## Project Approach

- Retrieved economic data directly from the Federal Reserve Economic Data (FRED) API
- Analyzed:
  - S&P/Case-Shiller U.S. National Home Price Index
  - U.S. Housing Starts
- Cleaned and transformed monthly economic time series data
- Conducted exploratory trend and stationarity analysis
- Applied forecasting workflows for housing market analysis
- Built Vector Autoregression (VAR) models to analyze dynamic relationships between variables
- Used Quarto and R Markdown for reproducible analytical reporting

---

## Data Sources

Data obtained from the Federal Reserve Economic Data (FRED) database:

| Series ID | Description |
|---|---|
| `CSUSHPINSA` | S&P/Case-Shiller U.S. National Home Price Index |
| `HOUSTNSA` | New Privately-Owned Housing Units Started |

Source: https://fred.stlouisfed.org/

---

## Analytical Focus Areas

- Time series forecasting
- Housing market trend analysis
- Economic indicator analysis
- Vector Autoregression (VAR)
- Forecasting with multiple variables
- Reproducible analytical reporting

---

## Project Visuals

### Housing Price Trends

Visualization of historical housing price movement using the S&P/Case-Shiller U.S. National Home Price Index.

![Housing Price Trends](images/housing-price-trends.png)

---

### Housing Starts Analysis

Monthly U.S. housing starts used to evaluate supply-side market activity and economic trends.

![Housing Starts Analysis](images/housing-starts-analysis.png)

---

### VAR & Forecasting Results

Time series forecasting and Vector Autoregression (VAR) outputs used to analyze relationships between housing prices and housing starts.

![VAR Forecast Results](images/var-forecast-results.png)

---

## Repository Structure

```text
data/        -> downloaded or processed datasets
images/      -> charts and forecasting visuals
notebooks/   -> Quarto and R Markdown analytical workflows
reports/     -> exported PDF project reports
```

---

## Files

| File | Description |
|------|-------------|
| `notebooks/housing_price_timeseries.qmd` | Quarto workflow for housing price forecasting and VAR analysis |
| `notebooks/housing_price_timeseries.rmarkdown` | R Markdown version of the project |
| `reports/` | Exported reports and final outputs |

---

## Portfolio

Portfolio Website: https://cameronbatts.github.io/

GitHub Profile: https://github.com/cameronbatts
