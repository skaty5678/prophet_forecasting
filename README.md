# Time series forecasting using Facebook's Prophet

In 2017, a few researchers at Facebook published a paper called, “Forecasting at Scale” which introduced the open-source project Facebook Prophet, giving quick, powerful, and accessible time-series modeling.


It is an open-source algorithm for generating time-series models that uses a few old ideas with some new twists. It is particularly good at modeling time series that have multiple seasonalities and doesn’t face some of the drawbacks of other algorithms.


## Steps involved in the process
### 1. Installing and importing dependencies
Installing fbprophet and pystan (PyStan is a Python interface to Stan, a package for Bayesian inference. Stan® is a state-of-the-art platform for statistical modeling and high-performance statistical computation. Thousands of users rely on Stan for statistical modeling, data analysis, and prediction in the social, biological, and physical sciences, engineering, and business).


### 2. Preparing data for time series forecasting
Load data into a pandas dataframe. We are using a store and products(store --> products they sell -->their values) related dataset.

### 3. Training Prophet time series models
Training model.

### 4. Making forecast predictions and plotting
Making future dataframes and forecast forward
Plotting static and interactive forecasts.

