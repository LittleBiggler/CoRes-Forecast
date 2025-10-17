# CoRes-Forecast
Forecasting on SVD-reconstructed (imputed) data from CoResidence

To-Do
Native Feature Space Forecasting
1) Import df_mstr from CoResidence
2) Perform truncated SVD with 40 and 60 components (on scaled, centered data)
4) Fill only the missing values with reconstructed values (Remember to keep unscaled version of original values)
5) Unscale reconstructed values with fitted scaler

Lagged SVD Components Forecasting
1) Perform 1 & 2 above
2) Lag USigma per year
3) Forecast on lagged features

Validate with a Holt line on univariate Gini
