# EV Market Trends and Forecast: Tesla vs. BYD (2018–2025)

This project compares the battery electric vehicle (BEV) sales of **Tesla** and **BYD** from 2018 to Q1 2025 using time series forecasting, financial feature engineering, and interactive dashboards. It aims to understand sales trends of both brands amid the gloabal transition to EV, and explore how financial indicators like stock returns impact future sales volumes.

---

## 📁 Project Structure

### 1. Exploratory Data Analysis (EDA)
- Cleaning and merging quarterly and yearly **sales**, exploring gloabal EV adoption trends, and stock market data.
- Visualization of sales by brand, powertrain transition, EV adoption, market performance
- [Telsa_BYD_EDA.ipynb](Tesla_BYD_EDA.ipynb)

### 2. Predictive Modelling (Prophet)
- Forecasts based on:
  1. Basic quarterly sales
  2. Tuned model
  3. Model with added external regressor: quarterly lagged stock returns
- Evaluation using RMSE, MAE, MAPE, R2
- [Tesla_BYD_ML.ipynb](Tesla_BYD_ML.ipynb)

### 3. Tableau Dashboards
- Key insights visualized in an interactive Tableau dashboards 
- [View Dashboard on Tableau Public](https://public.tableau.com/views/Tesla_BYD_sales/Sales?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
![Dashboard Preview 1](Tesla_BYD_Tableau_Preview_1)  
![Dashboard Preview 2](Tesla_BYD_Tableau_Preview_2)
![Dashboard Preview 3](Tesla_BYD_Tableau_Preview_3)  
![Dashboard Preview 4](Tesla_BYD_Tableau_Preview_4)

---

## Data Sources

**Sales Data**:
- Manufacturer reports obtained from Wikipedia ([Tesla](https://en.wikipedia.org/wiki/History_of_Tesla,_Inc.), [BYD](https://en.wikipedia.org/wiki/BYD_Auto)
- BYD report for Q1 2025 collected manually from https://www.bydglobal.com/en/InvestorNotice.html
**Global EV Sales and Adoption Data**: [Global EV Outlook](https://www.iea.org/reports/global-ev-outlook-2025) 2025 by International Energy Agency (IEA)
**Stock Data**: `yfinance` API – daily Tesla & BYD prices (TSLA and BYDDYY)

*All data used is public and non-commercial, intended strictly for educational purposes.*

---

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Prophet)
- yfinance for financial data
- Tableau Public for dashboarding
- Jupyter Notebooks

---

## Author

**Aleksej Talstou**  
Aspiring Data Scientist  
[LinkedIn Profile](https://www.linkedin.com/in/aliaxey-talstou)

---
