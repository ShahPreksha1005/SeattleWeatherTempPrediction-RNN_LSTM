# SeattleWeatherTempPrediction-RNN_LSTM

This project focuses on predicting maximum daily temperatures in Seattle using Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) models. The objective is to utilize historical weather data to capture sequential dependencies and forecast temperature changes effectively.

## Project Overview
- **Dataset**: The Seattle Weather dataset, comprising daily weather observations.
- **Objective**: Forecast maximum temperature based on historical data patterns.
- **Models**: Multiple models were tested:
  - Simple RNN
  - LSTM
  - A comparison of RNN, LSTM, and GRU to evaluate efficiency and predictive capability.
- **Evaluation Metrics**: Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

## Steps Involved
1. **Data Preprocessing**: Handling missing values, scaling, and transforming the data for sequential modeling.
2. **Feature Engineering**: Creating supervised learning sequences to capture dependencies.
3. **Model Building**: Constructing, training, and comparing RNN, LSTM, and GRU architectures.
4. **Performance Evaluation**: Assessing model loss and validation loss across epochs to identify the best-performing model.
5. **Visualization**: Plotting predicted vs. actual temperature values for validation and test sets.

## Key Insights
- **Model Comparison**: 
  - The LSTM model demonstrated better long-term sequence learning than the Simple RNN.
  - The GRU model balanced efficiency and performance well, making it suitable for this dataset.
- **Model Recommendations**: Based on the dataset's sequential nature, GRU or LSTM models provided the most robust results for temperature prediction.

## Dependencies
- Python libraries: Pandas, NumPy, Matplotlib, Seaborn, Keras, TensorFlow
- **Model training environment**: Google Colab

## Results
- The LSTM model achieved the lowest validation loss, showing superior accuracy in predicting maximum temperatures.
- Visualizations provided insights into model performance and sequence learning.

## Future Directions
- Experimenting with additional layers and hyperparameters.
- Testing alternative sequential models like Transformer architectures for potentially improved accuracy.

---
