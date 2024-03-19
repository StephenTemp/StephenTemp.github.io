---
title: "Energy Consumption Prediction for Climate Planning"
excerpt: "Energy Consumption Prediction for Climate Planning"
excerpt: "For Data Science for the Common Good (DS4CG), produced traditional machine learning and Gaussian processes to forecast property emissions data for the Massachusetts Department of Capital Asset Management and Maintenance (DCAMM).<br/><img src='/images/GPR.png'>"
collection: portfolio
---

**Collaborators:** [Purva Pruthi](https://purvapruthi.github.io), [Erin Bartuska](https://ekbartus.carrd.co), [Nelson Evbarunegbe](https://www.linkedin.com/in/nelson-evbarunegbe-753240156/)

Working as a Machine Learning Engineer for The University of Massachusetts [Center of Data Science](https://ds.cs.umass.edu/about) (CDS) my team was approached by the Massachusetts Department of Capital Asset Management and Maintenance (DCAMM) to apply data science expertise to their climate initatives. After review, we chose to implement and adapt state-of-the-art time series forecasting to aid long term emission prediction for state-owen buildings. We tried various time-series forecasting approaches (Moving Average, Simple Exponential Smoothing, **Holt-Winter's Exponential Smoothing**, **Gaussian Process Regression**) and provided two methods for 365-day predictions. 

* <ins> Holt-Winter's Exponential Smoothing </ins>
![Holts Winter's plot showing damping and non-damping results for 365-day prediction](/images/holtswinters.jpg)

Time series data consists of sequences of observations collected over time, composed of trends, seasonality, and irregular fluctuations:
- **Trends:** A long-term increase or decrease in the data. This can be seen as a slope (is doesn’t have to be linear) roughly going through the data.
- **Seasonality:** A time series is said to be seasonal when it is affected by seasonal factors (hour of day, week, month, year, etc.). Seasonality can be observed with nice cyclical patterns of fixed frequency.
- **Cyclicity:** A cycle occurs when the data exhibits rises and falls that are not of a fixed frequency. 
- **Residuals:** The difference between an observation and its predicted value at each time step.

Holt-Winter's includes seasonality component along with level and trend components, working best when data has clear linear trend and seasonality. The figure above shows results for a candidate meter with and without _damping_, i.e decaying the linear trend over time. 


* <ins> Gaussian Process Regression </ins>
![Gaussian Regression plot showing damping and non-damping results for 365-day prediction](/images/GPR.png)