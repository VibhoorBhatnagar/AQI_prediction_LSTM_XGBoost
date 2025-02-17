****Air Quality Index (AQI) Forecasting for Indian Cities****
-------------------------------------------------------------

**Introduction**

This project aims to forecast the Air Quality Index (AQI) for various cities in India by leveraging machine learning models and geospatial analysis. The dataset, sourced from the Government of India’s data portal, includes historical pollutant levels for multiple cities. Our goal is to support urban planning and public health policies by providing accurate AQI forecasts and highlighting key pollutant trends.

**Project Overview**
- **Models Used:** Long Short-Term Memory (LSTM) and XGBoost

- **Geospatial Techniques:** Kriging and Inverse Distance Weighting (IDW)

- **Tools:** ArcGIS Pro

- **Performance:** Achieved a Root Mean Square Error (RMSE) of 0.90 for both LSTM and XGBoost

**Methodology**
- **Data Collection:** Historical pollutant data from the Government of India’s data portal.

- **Model Development:**

  - **LSTM:** Captures temporal dependencies within time-series data.

  - **XGBoost:** Analyzes feature interactions and performs well with structured data.

- **Geospatial Analysis:**

  - **Kriging:** Interpolates AQI levels for a more comprehensive understanding of AQI distribution.

  - **IDW**: Provides spatial variations across different urban regions.

- **Visualization**: Visualize AQI distribution across urban areas to aid in urban planning and public health policies.

**Results**
 - **Predictive Accuracy:** Both LSTM and XGBoost models achieved an RMSE of 0.90.

- **Spatial Analysis**: Geospatial techniques provided detailed insights into AQI distribution and spatial variations.

**Conclusion**

This project highlights the utility of combining machine learning models with geospatial analysis to provide accurate AQI predictions. 
These predictions are vital for urban planning and public health policy, supporting efforts to mitigate air pollution in urban environments across India.
