# Temperature Prediction Using Time Series Models

This project focuses on predicting temperature values using time series data.
Several machine learning and deep learning models are implemented and compared
to evaluate their effectiveness in capturing temporal patterns.

## Objectives
- Predict future temperature values from historical data
- Compare classical machine learning models with deep learning approaches
- Analyze model performance on time-dependent data

## Models Implemented
- Linear Regression (baseline model)
- Random Forest Regressor
- LSTM (Long Short-Term Memory neural network)

## Methodology
- Data preprocessing and normalization
- Train / validation / test split adapted for time series
- Feature engineering for supervised learning
- Model training and evaluation using error metrics
- Visual comparison of predicted vs actual values

## Evaluation Metrics
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

## Files in This Repository
- `temperature_prediction_lstm_rf_lr.ipynb`  
  Complete implementation, experiments, visualizations, and results

- `Temperature_Prediction_Time_Series_Report.pdf`  
  Detailed academic report explaining methodology, theory, and analysis  
  *(Note: the report is written in French)*

## Tools & Technologies
- Python
- NumPy, Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## Conclusion
The project highlights the limitations of traditional regression models on
time series data and demonstrates how LSTM networks can better capture temporal
dependencies for temperature prediction.
