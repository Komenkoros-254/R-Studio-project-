# R-Studio-project-
Determinants and forecasting of Kenya’s annual inflation (2000–2024) using econometric regression, structural break analysis, and ARIMA time‑series models in R.

Author: Komen Kipkoros Meshack  
Date:24 April 2026  

This project analyses the determinants, structural breaks, and forecasts of annual inflation in Kenya over the period **2000–2024** using R. It combines descriptive statistics, econometric regression, and simple time-series modelling to understand what drives inflation and how it is likely to evolve.

---

## 1. Project Overview

The main goals of this project are to:

- Examine how **money growth**, **exchange-rate changes**, **GDP growth**, and **government expenditure** are related to **Kenya’s annual inflation**.
- Identify and quantify the impact of key **event years**:
  - 2008 – post-election violence and global food/fuel price spike.
  - 2020 – COVID‑19 shock.
- Build a **regression model with lagged variables** to explain inflation.
- Fit a simple **ARIMA time-series model** to forecast inflation for the next year.
- Provide a reproducible, well-documented analysis suitable for a portfolio/academic project.

The main analysis is contained in the R Markdown file:

- `Inflation rate prediction model.Rmd`

---

## 2. Repository Structure

The structure for this project is:

```text
.
├─ data/
│  └─ raw/
│     └─ Modeel_data.xlsx
├─ figures/
│  ├─ Rplot for Annual Inflation rates.png
│  ├─ Rplot for CPI index.png
│  ├─ Rplot for Explanatory variables trend.png
│  ├─ Rplot for inflation years with structural breaks.png
│  └─ Rplot  for correlation between variables.png
   └─ Rplot a year ahead prediction for inflation rate.png
├─ INFLATION RATE PREDICTION MODEL.Rmd
├─ INFLATION-RATE-PREDICTION-MODEL.html
└─ README.md
