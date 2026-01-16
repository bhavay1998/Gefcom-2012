# Gefcom-2012
Load Forecasting Competition (Kaggle)

This repository holds my master's thesis work that evaluates applied time series methods for short-term load forecasting in electric power systems, using the GEFCom2012 load forecasting dataset. Motivated by the critical role of accurate load forecasting in maintaining grid stability, optimizing resource allocation, and supporting essential infrastructure reliant on reliable electricity, the study addresses challenges in high-frequency load data under realistic constraints like limited training periods and data scarcity. The primary objective is to compare classical time series models—such as exponential smoothing, harmonic regression, piecewise linear regression, seasonal ARIMA (SARIMA), and SARIMA with exogenous variables (SARIMAX)—against naïve baseline and competition benchmark to identify efficient approaches that achieve at least 30% error reduction relative to competition's benchmark, while emphasizing model simplicity for practical deployment. 

Models are trained on approximately three weeks of data per session (last weeks of selected 2004 months as test sets), evaluated using RMSE and R²scores. Naïve methods include repeating prior cycles or averaging loads. Advanced techniques incorporate harmonics for seasonality, piecewise segments for non-linearity, and ARIMA components for serial dependencies. 

For the full grid forecast horizon, piecewise linear regression combined with harmonics achieves 37% RMSE reduction vs. naïve (10804 vs. 17128) and 30% RMSE reduction vs. benchmarks (15513). This performance is at par with high accuracy models found globally in the Gefcom 2012 Kaggle competition. When forecasting horizon is considered together with missing values, the improvement over benchmark (in terms of avg RMSE) is 13%. Key findings demonstrate that simpler methods for load estimation outperform complex ones under practical constraints of data scarcity. This gives strong support to traditional statistical methods in realistic settings, promoting efficienct deployment for emerging smart grid solutions.

# Dataset & Competition's Link
Official Dataset can be found at: <i>https://www.kaggle.com/competitions/global-energy-forecasting-competition-2012-load-forecasting/data</i>

# Dataset's Publication
ScienceDirect, International Journal of Forecasting: <i>https://www.sciencedirect.com/science/article/abs/pii/S0169207013000745</i>

# About the Dataset's Author
Energy Forecasting blog by Dr. Tao Hong: <i>http://blog.drhongtao.com/</i>
