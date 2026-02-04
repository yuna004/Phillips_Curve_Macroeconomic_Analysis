# Comparative Analysis of the Phillips Curve: Ukraine vs. CEE Countries

A comprehensive econometric study investigating the empirical relationship between unemployment rates and inflation (The Phillips Curve). This project compares the economic stability of Ukraine (2011–2021) against Central and Eastern European (CEE) peers: the Czech Republic, Estonia, Poland, and Romania.

## Overview
Does the classic inverse relationship between inflation and unemployment still hold in volatile economies? This project uses **Ordinary Least Squares (OLS) Regression** to test the stability of the Phillips Curve, analysing how structural transformations and geopolitical shocks in Ukraine impact traditional macroeconomic models.

## Tech Stack
* **Language:** Python
* **Analysis Libraries:** `pandas`, `numpy`, `statsmodels` (OLS Regression)
* **Visualization:** `matplotlib`
* **Data Sources:** State Statistics Service of Ukraine, National Bank of Ukraine, and Eurostat.

## Key Features
* **Comparative Econometrics:** Built individual regression models for 5 different countries to compare the "slope" of the Phillips Curve across regions.
* **Statistical Rigour:** Performed significance testing ($p$-values) and R-squared analysis to determine the explanatory power of unemployment on inflation.
* **Ukraine Case Study:** Detailed analysis of the 2011-2021 period, accounting for the unique economic shocks experienced by the Ukrainian economy.
* **Augmented Modelling:** Discussion on "Augmented Phillips Curves" incorporating exchange rates and external price shocks (oil prices).
* **Monetary Policy Tool:** The findings provide a framework for central banks to evaluate the "sacrifice ratio" between price stability and employment.
* **Structural Analysis:** Identified that while the Phillips Curve is present in CEE countries, Ukraine's model is significantly more sensitive to external shocks rather than just domestic labor market shifts.
* **NAIRU Estimation:** Theoretical exploration of the Non-Accelerating Inflation Rate of Unemployment in transition economies.

## How to Run
To view the models and regression outputs:

1. Install required Python packages

```
pip install pandas numpy matplotlib statsmodels
```

2. Launch Jupyter Notebook

```
jupyter notebook main.ipynb
```
