# Statistical Time Series Analysis for Irish import trade Data and Forecasting

**Experience Level:** Intermediate - Advance

**Technology Used:** R

### Summary of the Experiment:

1. The aim of the experiment was to perform forecasting on Ireland import trade in EUR(million) for 3 consecutive years of 2020, 2021, and 2022.
2. Steps from visually understanding the time-series data, checking for various components in the series, fitting different models to the data to comparing and evaluating the models and finally forecasting using a selected models are performed in the experiment.
3. Checks are performed for time-series components such as trend, seasonality and cycles using statistical tests for each component.
    1. Based on components present particular suited models are selected to fit the data
4. Four models were selected to fit the time series data were Naive model, Holts model, ETS model, ARIMA model.
    1. All the models are evaluated and compared on the AICc and RMSE metrics
    2. Best among all the models is selected for forecasting
5. Before performing the forecast model is first evaluated using statistical tests for no residual correlation (Ljung-Box test) and residual plot and ACF plot to check goodness of fit.
6. Three Forecasts are then made using the selected ARIMA 022 model.

---

**Objectives:**
* To fit a time-series model to perform forecast for Ireland import trade for years 2020, 2021, and 2022.
* To vizualize the time-series data for basic understanding
* To perform checks using statistical tests for components of time-series
* To fit, compare the time-series models on the trade data and select the model to perform forecasting.
* To check Goodness of fit using statistical test and techniques

---

Time-Series Analysis Experiment Project by [Abhishek Padalkar](https://github.com/Padlu).
