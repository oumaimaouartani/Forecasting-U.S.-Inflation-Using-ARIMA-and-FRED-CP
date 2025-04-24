# Forecasting U.S. Inflation Using ARIMA and FRED CPI

This project aims to forecast U.S. inflation using time series analysis techniques, specifically the ARIMA model. It utilizes the **Consumer Price Index (CPI)** data obtained via the **FRED API (Federal Reserve Economic Data)**.

##  Objective
To build a predictive model that estimates future U.S. inflation trends, aiding economists, policy makers, and analysts in making data-informed decisions.

##  Tools & Technologies
- Python
- Jupyter Notebook
- `pandas`, `matplotlib`, `statsmodels`, `pmdarima`
- FRED API for CPI data

## 📁 Dataset
- Source: [FRED - Consumer Price Index for All Urban Consumers](https://fred.stlouisfed.org/series/CPIAUCNS)
- Frequency: Monthly CPI data

## Project Workflow

1. **Data Collection**  
   - Access CPI data from the FRED API

2. **Data Preprocessing**  
   - Handle missing values  
   - Convert date columns and format time series

3. **Exploratory Data Analysis (EDA)**  
   - Visualize trends, seasonality, and stationarity

4. **Model Building**  
   - Use ARIMA (AutoRegressive Integrated Moving Average)  
   - Grid Search for optimal hyperparameters (p, d, q)

5. **Forecasting & Evaluation**  
   - Forecast CPI values for future periods  
   - Evaluate using RMSE and residual diagnostics

6. **Visualization**  
   - Plot actual vs predicted CPI  
   - Show confidence intervals

##  Results
The final ARIMA model successfully captures CPI trends and generates reliable short-term inflation forecasts. Evaluation metrics and visual diagnostics confirm model validity.

##  Notebook
You can view the full code on Kaggle here:  
👉 [Kaggle Notebook](https://www.kaggle.com/code/oumaimaouartani/forecasting-u-s-inflation-using-arima-and-fred-cp)

---


