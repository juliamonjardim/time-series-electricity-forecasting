# Time Series Forecasting Project in Python
Time series forecasting project analyzing historical electricity production data using Python and AutoReg models.

Project Overview:
This project explores historical electricity production data using Time Series Analysis and forecasting techniques in Python.

The primary objective was to analyze temporal patterns, identify trends and seasonality, evaluate stationarity, and generate future forecasts using autoregressive models.

The project was developed in Google Colab using Python libraries focused on data analysis, visualization, and statistical modeling.

Dataset:
Dataset Source:
https://www.kaggle.com/datasets/kandij/electric-production

Dataset Name:
Electric Production Dataset

The dataset contains historical monthly electricity production data and was used to analyze long-term patterns and forecast future electricity production values.

Objectives:
  Analyze historical electricity production behavior
  Explore trends and seasonal patterns
  Understand stationarity in time series data
  Apply forecasting techniques using AutoReg models
  Visualize and interpret future predictions
  Concepts Explored

Throughout this project, the following concepts were applied:
  Exploratory Data Analysis (EDA)
  Time Series Visualization
  Rolling Averages (Moving Average)
  Trend Analysis
  Seasonality Detection
  Seasonal Decomposition
  Stationarity Testing using the Augmented Dickey-Fuller Test
  Autoregressive Forecasting Models (AutoReg)
  Model Evaluation using AIC
  Future Value Forecasting
  Technologies & Libraries
  Python
  Pandas
  Matplotlib
  Statsmodels
  Google Colab
  
Forecasting Workflow
1. Data Preparation
  Imported the dataset
  Converted the DATE column into datetime format
  Structured the dataset as a time series
2. Exploratory Data Analysis
  Visualized historical electricity production values
  Identified recurring patterns and temporal behavior
3. Rolling Average Analysis
  Applied a 12-month rolling average to smooth short-term fluctuations
  Observed long-term production trends
4. Seasonal Decomposition
  Decomposed the series into:
  Trend
  Seasonality
  Residuals
5. Stationarity Testing
  Performed the Augmented Dickey-Fuller (ADF) Test
  Evaluated whether the series was stationary before forecasting
6. Forecasting Model
  Built an AutoReg forecasting model
  Tested multiple lag values
  Selected the optimal lag configuration using AIC
7. Future Forecasting
  Generated future electricity production predictions
  Compared historical and forecasted values through visualization
  Key Insights

The analysis revealed:
Clear seasonal patterns in electricity production
Long-term production trends
Cyclical temporal behavior
The importance of stationarity in forecasting workflows

The project also strengthened practical understanding of statistical reasoning and forecasting methodologies in time series analysis.

Results:
The final forecasting model successfully generated future electricity production predictions based on historical observations and autoregressive lag relationships.

Repository Structure
├── Time_Series_Forecasting_Project.ipynb
├── Electric_Production.csv
├── forecast_graph.png
└── README.md

Author

Julia Monjardim de Carvalho

Information Systems student focused on developing skills in Data Analytics and Data Science through hands-on projects involving forecasting, statistical analysis, and data visualization.

LinkedIn:
https://www.linkedin.com/in/julia-monjardim-de-carvalho/

GitHub:
https://github.com/juliamonjardim
