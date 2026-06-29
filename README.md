# Gefcom-2012
`Topic:` Statistical Forecasting Under Demand Uncertainty

- [Publication Repository - Qucosa](https://nbn-resolving.org/urn:nbn:de:bsz:14-qucosa2-1016244)

## Published Submissions
- [Thesis Report](Master's%20Thesis%20-%20Bhavay%20Singhal.pdf)
- [Presentation - Overview](Thesis%20Presentation%20-%20Project%20Overview.pptx)

## Dataset Information
- [Dataset Author - Dr. Hong](http://blog.drhongtao.com/)
- [Official Dataset Link](https://www.kaggle.com/competitions/global-energy-forecasting-competition-2012-load-forecasting/data)
- [Dataset Publication - ScienceDirect, International Journal of Forecasting](https://www.sciencedirect.com/science/article/abs/pii/S0169207013000745)

## About
Thesis work evaluates the application of statistical modelling to historical time-series dataset from a US utility company, to analyse demand variability and forecast future demand, that can support quantitative decision-making under uncertainty. The study focuses on realistic operational constraints, including high-frequency load data, limited historical observations, high variability, and elevated forecast risk — conditions commonly faced in practice rather than academic benchmark settings. 

## Aim & Methodology
The primary objective is to assess whether classical statistical models can deliver strong forecasting performance under these constraints while remaining interpretable and easy to adopt by businesses in real time. A range of models — including exponential smoothing, regression splines, and SARIMAX — are evaluated against naïve baselines and competition benchmarks. Model performance is assessed using RMSE, with a target of achieving at least a 30% error reduction relative to the competition benchmark. Models are trained on approximately three weeks of data per session, with final weeks of selected months in year 2004 as test sets. Naïve methods include repeating prior cycles or averaging loads. Advanced techniques incorporate harmonics for seasonality, piecewise segments for non-linearity, and ARIMA components for serial dependencies. 

## Findings & Conclusion
Results are positive and show that piecewise linear regression combined with harmonic components meet the target with a 37% RMSE reduction relative to naïve baselines and a 30% reduction relative to competition benchmarks over the entire forecast horizon. This performance is at par with high accuracy models found globally in the Gefcom 2012 Kaggle competition. When forecasting horizon is considered together with missing values, the improvement over benchmark is found to be 13% (in terms of average RMSE). 

Within the scope of the models evaluated, classical statistical methods achieved strong forecasting performance while remaining highly interpretable and suitable for operational deployment. Scenario analysis indicates that the forecasting framework could contribute to estimated annual savings exceeding USD 2 million through improved demand planning and resource allocation.
