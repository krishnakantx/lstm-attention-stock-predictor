# LSTM-Attention Stock Predictor

A deep learning model for stock price prediction using Long Short-Term Memory (LSTM) networks with an attention mechanism. It captures long-range dependencies in time-series data while prioritizing key historical patterns for improved predictive accuracy, making it adaptable to various stocks and market conditions.

## Table of Contents
- [Technical Overview](#technical-overview)
- [Frameworks and Libraries](#frameworks-and-libraries)
- [Approach](#approach)
- [Performance Metrics](#performance-metrics)
- [Accuracy Calculation](#accuracy-calculation)
- [Future Enhancements](#future-enhancements)

## Technical Overview
This project employs advanced deep learning techniques to analyze historical stock price data and predict future price movements.

## Frameworks and Libraries
- **TensorFlow**: For building and training the deep learning model.
- **Keras**: For simplifying model development with high-level APIs.
- **Python**: The primary programming language used for implementation.
- **yfinance**: For fetching real-time stock data.
- **matplotlib**: For data visualization.
- **mplfinance**: For advanced financial visualizations.

## Approach
1. **Data Collection**: Real-time stock data is fetched using the `yfinance` library.
2. **Data Preprocessing**: The stock price data is cleaned and normalized using MinMaxScaler.
3. **Model Architecture**: 
   - Built a multi-layer LSTM model enhanced with an attention mechanism to capture long-term dependencies in the data.
4. **Evaluation**: Utilized metrics like Mean Absolute Error (MAE) and Root Mean Square Error (RMSE) to assess model performance.

## Performance Metrics for 'TSLA' stock
- **Test Loss**: 0.000544
- **Mean Absolute Error (MAE)**: 0.0187
- **Root Mean Square Error (RMSE)**: 0.0233

These metrics indicate that the model performs well in predicting stock price movements with minimal error.
