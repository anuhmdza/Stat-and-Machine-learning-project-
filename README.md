
#  Disease Case Count Prediction Project

This project explores multiple machine learning and statistical models to forecast disease case counts across U.S. states using historical features like temperature, income, rent, immunization, and exemption rates. We are predicting disease count per state per year.

##  Files Included
- `final_model_dataset_with_features.csv` - the dataset used for all analyses.
- `visualizations for project (1).ipynb` - the Jupyter notebook for EDA.
- `XGBOOST RANDOM FOREST ARIMA SARIMA MODELING.ipynb` - XGBoost,Random Forrest,ARIMA/SARIMA Modeling + Predictions Per State Per Year
- `bsts.Rmd` - Bayesian Structural Time Series Modeling+ Predictions
##  Models Used
1. **ARIMA** – basic time series forecasting using case counts.
2. **SARIMA** – time series with seasonal components.
3. **Random Forest Regressor** – tree-based model using all available numeric features.
4. **LSTM (Long Short-Term Memory)** – neural network model designed for sequential data.
5. **BSTS** - a statistical method for analyzing and forecasting time series data by decomposing it into components like trend, seasonality, and regression
##  Visualizations
- Trend line of average case counts by year.
- Correlation heatmap of all numeric features.
- Choropleth map showing average case counts by state.
- Model comparison graphs and predictions.

##  Key Findings
- **XBOOST** gave the best predictive performance with the lowest RMSE.
- LSTM and SARIMA showed potential for more sequential modeling but may need further tuning.
- Visualizing data helped uncover trends and correlations that informed model choices.

##  What You’ll Learn
- How to preprocess and visualize a complex dataset.
- How to apply time series and machine learning models to real-world epidemiological data.
- How to evaluate and compare model performance.
- How to build a project pipeline from data to insight.

---

Created for academic and exploratory purposes.
