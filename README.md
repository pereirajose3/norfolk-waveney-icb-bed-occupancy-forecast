# Norfolk and Waveney ICB Bed Occupancy Forecast 

This project explores the use of **time series forecasting** to predict the number of **hospital beds occupied overnight** across the Norfolk and Waveney Integrated Care Board (ICB). 

Using historical NHS bed occupancy data, I applied **SARIMA** model to identify seasonal patterns, trends, and forecast future demand. The objective is to support **capacity planning** and **resource allocation** at the regional level.

---
 
## What’s included

- Exploratory analysis of overnight hospital bed occupancy
- Forecasting using:
  - **Seasonal ARIMA (SARIMA)**
- Visual comparison of model results
- Evaluation using error metrics 

---

## Data Source

NHS England:  
**Bed Availability and Occupancy Data**  
https://www.england.nhs.uk/statistics/statistical-work-areas/bed-availability-and-occupancy/

---

## How to Use

1. Open the Jupyter Notebooks in the `notebooks/` folder.
2. Follow the workflow: data cleaning → model fitting → forecasting → evaluation.
3. Compare results from Baseline and SARIMA side-by-side.

---

## Goal

To help local NHS teams anticipate demand and improve operational readiness by forecasting inpatient bed use with interpretable, data-driven methods.



