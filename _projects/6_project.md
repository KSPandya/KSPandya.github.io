---
layout: page
title: Solar Activity Prediction & Time-Series Forecasting
description: Comparing classical statistical models (ARIMA, SARIMA) with Deep Learning architectures (LSTM) for space weather forecasting.
img: /assets/img/projects/solar_activity_feature.jpg
importance: 2
category: fun
related_publications: false
---

As part of my coursework exploring advanced time-series analysis and non-linear forecasting, I undertook a project predicting solar activity indices (such as sunspot numbers and solar flux). Space weather forecasting is notoriously challenging due to the high volatility, non-stationarity, and multi-scale cyclical nature of solar dynamics (e.g., the 11-year solar cycle).

The objective of this project was to benchmark traditional statistical forecasting models against modern deep learning architectures to evaluate predictive accuracy, computational efficiency, and long-term horizon stability.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/solar_decomposition.jpg" title="Time Series Decomposition" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/acf_pacf_plots.jpg" title="ACF and PACF Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Exploratory Data Analysis: (Left) Time-series decomposition isolating trend, seasonality, and residual noise from historical sunspot records. (Right) Autocorrelation (ACF) and Partial Autocorrelation (PACF) plots used for parameter tuning in classical models.
</div>

### Methodology & Model Architecture

The study evaluated two distinct paradigms of time-series modeling:

1. **Classical Statistical Models:**
   * **ARIMA & SARIMA:** Fitted using iterative Box-Jenkins methodology, incorporating differencing and seasonal moving average terms to capture the periodic 11-year solar flux cycles.
   * **Exponential Smoothing (Holt-Winters):** Used as a baseline for trend and seasonality smoothing.

2. **Deep Learning Approaches:**
   * **LSTM (Long Short-Term Memory Networks):** Designed to capture long-term temporal dependencies and non-linear patterns that linear statistical models miss.
   * **GRU & Hybrid Architectures:** Explored for faster training convergence and gradient stability across multi-step forecasting horizons.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/arima_vs_lstm_forecast.jpg" title="Forecast Comparison" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Model Performance Comparison: Comparing actual solar activity curves against SARIMA baseline projections and LSTM predictions over a 24-month horizon.
</div>

### Key Findings & Insights

While classical models like SARIMA performed exceptionally well for short-term stationary windows and interpretable seasonal decomposition, LSTM networks demonstrated superior adaptability when modeling sudden solar flare eruptions and complex non-linear transitions. This coursework bridge between classical econometrics/statistics and deep sequence modeling provided valuable intuition into temporal feature engineering and loss landscape optimization.

{% raw %}
```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/arima_vs_lstm_forecast.jpg" title="Forecast Comparison" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
