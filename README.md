# Environmental Statistics

## Lecture 8: Time Series, GAM and Spatial Regression: VCOV and GLS (incl. AR1)
Suppose we measure daily river discharge for five years. Yesterday's discharge strongly influences today's discharge. Similarly, annual tree-ring growth depends on the previous year's climate. These observations are therefore not independent, violating one of the key assumptions of ordinary regression and can lead to biased inference. 

This lecture distinguishes between misspecification of the mean structure (handled by GAM) and misspecification of the covariance structure (handled by GLS).

In this lecture we cover:

-   Autocorrelation in time and space
-   Diagnostics: ACF, PACF, correlogram, variogram
-   Generalized Additive Models (GAMs) for non-linear trends
-   Generalized Least Squares (GLS) with AR(1) correlation structure
-   Consequences for inference and model interpretation
