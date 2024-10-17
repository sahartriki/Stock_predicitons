# Stock Prediction

This repository contains a Stock Prediction application built with Python, Streamlit, and an LSTM (Long Short-Term Memory) neural network model. The application provides stock market predictions using historical stock data, allowing users to visualize stock trends and forecast future prices based on selected stocks.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Running the Streamlit App](#running-the-streamlit-app)
- [Contributing](#contributing)
- [License](#license)

## Features
- Visualize historical stock prices with interactive charts.
- Forecast future stock prices using an LSTM neural network.
- User-friendly interface for selecting and analyzing different stocks.
- Supports real-time data updates.

## Technologies Used
- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras (for LSTM model)
- Matplotlib / Plotly
- Yahoo Finance API

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sahartriki/Stock_predictions.git
   ```

## Usage
Make sure you have the necessary data files (e.g., historical stock data) in the appropriate directory if required by the app.

## Running the Streamlit App

To run the Streamlit application, follow these steps:

1. **Navigate to the Project Directory**
   Make sure you are in the root directory of the project where your `app.py` file (or the Streamlit app file) is located.

2. **Run the Streamlit App**
   Use the following command to start the Streamlit app:
   ```bash
   streamlit run app.py
   ```

   Replace `app.py` with the actual name of your Streamlit application file if it's different.

3. **Access the App in Your Browser**
   After running the command, Streamlit will launch a local server. You can access the app by opening your browser and navigating to:
   ```
   http://localhost:8501
   ```

   The app will open automatically in your browser, or you can copy and paste the URL manually.

4. **Interacting with the App**
   - Use the interface to select the stock you want to analyze.
   - View visualizations of historical stock data and forecasted prices based on the LSTM model.
   - Adjust any parameters or settings available to fine-tune your analysis.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

