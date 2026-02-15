# Household Energy Consumption Forecasting

## Objective

Forecast short-term household electricity consumption using historical time-series data.

Accurate energy prediction helps optimize smart grids and manage electricity demand efficiently.

---

## Dataset

**Household Power Consumption Dataset**

Contains minute-level measurements including:

* Global active power
* Voltage
* Current intensity
* Date and time

Data was resampled into daily averages for forecasting.

---

## Approach

### 1. Data Processing

* Parsed datetime column
* Handled missing values
* Resampled to daily consumption

### 2. Feature Engineering

Created temporal features:

* Day
* Month
* Weekday
* Lag values

### 3. Models Compared

* ARIMA (Statistical time series model)
* Prophet (Seasonality-aware forecasting)
* XGBoost (Machine learning regression)

### 4. Evaluation Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Square Error)

---

## Results

* Prophet captured seasonal patterns effectively
* XGBoost achieved lowest prediction error
* ARIMA performed moderately but struggled with complex patterns

---

## Visualization

Plotted actual vs predicted energy consumption for model comparison.

---

## Conclusion

Machine learning-based forecasting outperformed traditional statistical models for short-term energy prediction.

---

## Repository Structure

* notebook.ipynb
* forecast_plot.png
* README.md
