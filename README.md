# Stock-Price-Prediction

Stock Price Prediction using LSTM and yFinance
Overview
This project aims to predict stock prices using Long Short-Term Memory (LSTM) networks and historical data from Yahoo Finance (yFinance). It focuses on preprocessing data, training an LSTM model, and visualizing the results through an interactive web application built with Streamlit.

Features
1. Fetches historical stock data using yFinance
2. Preprocesses data including normalization and creation of training/testing sets
3. Trains an LSTM model for time series prediction
4. Visualizes stock prices and moving averages (50-day, 100-day, and 200-day)
5. Deploys an interactive web application using Streamlit to display predictions

Project Structure
1. Data Collection and Preprocessing
  - Uses yFinance to download historical stock price data.
  - Normalizes data and splits it into training and testing datasets.
2. Model Training
  - Constructs and trains an LSTM model with multiple layers.
  - Uses dropout layers to prevent overfitting.
3. Visualization
  - Plots actual vs. predicted stock prices.
  - Displays moving averages (50-day, 100-day, and 200-day) alongside stock prices.
4. Web Application
  - Builds a Streamlit application to display stock data, moving averages, and price predictions interactively.
