# Bhopal Climate Dynamics – Time Series Analysis

## Overview

This project investigates the climate dynamics of **Bhopal, India** by modeling the interdependence among three key meteorological variables: **temperature**, **humidity**, and **precipitation**. Using the **Vector Autoregressive (VAR)** model, the analysis captures how each variable evolves over time and how past values of one variable influence the others.

The project is implemented entirely in **R** and applies multivariate time series techniques to understand climate interactions and support data-driven environmental analysis.

## Objectives

* Analyze the temporal behavior of temperature, humidity, and precipitation.
* Model the dynamic relationships among multiple climate variables using a VAR model.
* Examine lagged dependencies and interactions between variables.
* Evaluate the statistical significance and predictive capability of the fitted model.
* Visualize climate trends and time series characteristics.

## Technologies Used

* **Programming Language:** R
* **Libraries:** `vars`, `forecast`, `tseries`, `ggplot2`, etc.

## Methodology

1. Import and preprocess the climate dataset.
2. Perform exploratory data analysis (EDA) and visualize the time series.
3. Test for stationarity using statistical tests such as the Augmented Dickey-Fuller (ADF) test.
4. Apply differencing or transformations if required.
5. Determine the optimal lag order using information criteria (AIC, BIC, HQ).
6. Train a Vector Autoregressive (VAR) model.
7. Analyze model diagnostics and residuals.
8. Interpret relationships using impulse response functions (IRF) and forecast error variance decomposition (FEVD).
9. Generate forecasts and visualize the results.

## Key Concepts

* Multivariate Time Series Analysis
* Vector Autoregressive (VAR) Models
* Stationarity Testing
* Lag Selection
* Forecasting
* Climate Data Analysis
* Time Series Visualization
