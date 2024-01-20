# Time series methods overview from ARIMA to LSTMs

### 1. Basic Concepts in Time Series

#### 1.1 From White Noise to ACF plots
- Simulate white noise and visualize with a plot.
- Create a white noise series with specific mean and standard deviation.
- Explore the concept of a random walk and explain stationarity for time series.
- Generate a random walk, plot it, and calculate the first difference series.

#### 1.2 ARMA Models
- Contrast AR(1) and AR(2) models.
- Explain the difference between Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF).
- Plot ACF and PACF of AR, MA, and ARMA models.
- Write the equation of an ARMA model.
- Elaborate on AIC and BIC criteria.
- Explain the Box-Jenkins method.

### 2. Forecasting Competition on Kaggle

#### 2.1 Data Description
- Overview of Kaggle dataset fields.

#### 2.2 Exercises
- Filter data for a specific item, transform into a time series object.
- Fit AR and MA models, predict sales, and compare using AIC and BIC.
- Perform residual analysis and diagnostic checks for various models.
- Use Auto-ARIMA for model fitting and explain the algorithm.

### 3. Forecasting with Prophet

#### 3.1 Introduction to Forecasting with Prophet
- Overview of Prophet and its differences from other models.

#### 3.2 Multiple Time Series Demand Forecasting Challenge with Prophet
- Apply Prophet to Kaggle dataset.
- Evaluate forecast performance using relevant metrics.

### 4. Fourier Transform

#### 4.1 Introduction to Fourier Transform
- Understand discrete Fourier transforms for capturing cyclicity.

#### 4.2 FFT Forecasting Model with Darts
- Replicate FFT steps in Python from an R tutorial.
- Explore detrending and its role in forecasting.

### 5. From Shapelet Mining to Discord Detection

#### 5.1 Motif Detection
- Explain matrix profile computation.
- Apply motif detection to a dataset and explore applications in different sectors.

#### 5.2 Discord Detection
- Compute matrix profile for NYC taxi dataset.
- Find discords in ECG data and discuss potential applications.

#### 5.3 Time Series Segmentation
- Use the Clasp algorithm for time series segmentation.
- Explore applications of time series segmentation.

### 6. Bonus on Deep Learning (RNNs)

#### 6.1 Introduction to Recurrent Neural Networks (RNNs) with LSTM using Darts
- Understand RNNs and LSTM models.

#### 6.2 Exponential Smoothing using Darts
- Forecast using Exponential Smoothing with Darts.