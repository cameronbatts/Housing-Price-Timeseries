# Housing Price Forecasting via Time Series & VAR Analysis

**Tools:** R · fredr · xts · forecast · vars · ggplot2 · tidyverse · ARIMA · VAR · Granger Causality · IRF

---

## Problem

Housing market analysts needed to forecast U.S. home price growth using historical price data and exogenous drivers like housing starts, while accounting for seasonality, non-stationarity, and temporal persistence in the series.

## Approach

Pulled monthly S&P/Case-Shiller Home Price Index and housing starts data from the FRED API (1987-2023). Applied a three-stage process -- Explore, Explain, Forecast -- covering seasonal decomposition, stationarity testing, ARIMA modeling with bootstrapped bagging, and a Vector Autoregression (VAR) to capture simultaneous relationships between prices and starts. Performed Granger causality testing and Impulse Response Function (IRF) analysis to identify the direction and duration of causal effects.

## Impact

Found that housing starts Granger-cause price growth (but not vice versa), with a 1-sigma shock to starts producing a price growth response that peaks within 2-3 months and dissipates within 1.5-2 years. Bagging improved upon the baseline ARIMA forecast by reducing both parameter and model uncertainty. COVID-period shocks remained the primary limitation of purely temporal models.

---

## Files

| File | Description |
|------|-------------|
| `housing_price_timeseries.qmd` | Quarto source file with full analysis |
| `housing_price_timeseries.html` | Rendered HTML output |

---

*Part of my data & analytics portfolio — [cameronbatts.github.io](https://cameronbatts.github.io)*
