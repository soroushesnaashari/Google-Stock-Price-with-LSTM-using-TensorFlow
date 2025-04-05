## Google Stock Price Forecasting
[![](Image.jpg)](https://unsplash.com/photos/the-google-logo-is-displayed-on-the-side-of-a-building-r-oebX7qWxM)

### Overview
This project demonstrates how to use a Long Short-Term Memory (LSTM) neural network to predict Google stock prices. By leveraging TensorFlow and its high-level APIs, the notebook guides you through loading historical stock data, preprocessing it for a time series forecast, constructing and training an LSTM model, and ultimately visualizing the predicted versus actual stock prices.

<br>

### Project Flow
1. **Data Collection & Preparation:**
  - Historical stock price data for Google is loaded.
  - The data is preprocessed by handling missing values, normalizing features, and formatting the data into a time series structure suitable for LSTM input.

2. **Model Development:**
  - An LSTM model is built using TensorFlow.
  - The architecture typically includes one or more LSTM layers followed by Dense layers to output predictions.

3. **Training & Evaluation:**
  - The model is compiled with an appropriate optimizer and loss function.
  - Training is conducted on a subset of the data with validation on a separate set.
  - Key performance metrics are monitored to evaluate the forecasting accuracy.

4. **Prediction & Visualization:**
  - Once trained, the model generates predictions on unseen data.
  - Visualizations are created to compare predicted stock prices with the actual values, providing insights into the model’s performance.

<br>

### Key Features
- **LSTM Architecture:** Tailored for time-series prediction, capturing temporal dependencies in stock prices.
- **TensorFlow Implementation:** Utilizes TensorFlow’s robust framework to build, train, and evaluate the neural network.
- **Data Preprocessing:** Incorporates techniques like normalization and data reshaping to optimize model performance.
- **Modular Code Structure:** The project is organized into clear sections for data preparation, model development, training, and evaluation, making it easy to understand and modify.
- **Visualization:** Graphs and plots are included to effectively communicate the model’s predictions against actual market trends.

<br>

### Results
- **Forecast Accuracy:** The LSTM model demonstrates promising results by effectively capturing the trends in Google stock prices.
- **Performance Metrics:** Evaluation metrics such as loss (and potentially others like Mean Squared Error) indicate that the model is well-tuned for forecasting.
- **Visual Validation:** Plots comparing the predicted and actual stock prices show a strong correlation, reinforcing the model’s predictive capability.

<br>

### Repository Contents
- **`google-stock-price-lstm-using-tensorflow.ipynb`**: Jupyter Notebook with full code, visualizations, and explanations.
- **`Data`:** Contains the [Original Dataset](https://www.kaggle.com/datasets/soroushesnaashari/google-stock-price-2018-2025) and you can see the cleaned dataset in notebook.
- **`README.md`:** Project documentation.

<br>

### How to Contribute
Contributions are welcome! If you'd like to improve the project or add new features:

1. **Fork the repository.**
2. **Create a new branch.**
3. **Make your changes and submit a pull request.**
