# Stock Price Prediction

This project uses machine learning techniques to predict stock prices based on historical data and market trends. It combines Long Short-Term Memory (LSTM) models with data visualization to help investors make informed decisions.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)

## Overview

The goal of this project is to develop a model that can predict future stock prices using past stock market trends. By leveraging LSTM, a type of recurrent neural network, the system captures time-series dependencies in stock data to generate accurate forecasts. The project also integrates real-time predictions and visualizations to enhance usability and decision-making.

## Features

- Predicts stock prices using LSTM neural networks
- Data preprocessing and feature engineering
- Visualization of stock trends using charts
- Real-time prediction updates
- Performance evaluation using RMSE and MAE metrics

## Technologies Used

- **Python**
- **NumPy**, **Pandas** – data processing
- **Matplotlib**, **Seaborn** – data visualization
- **TensorFlow** / **Keras** – building LSTM models
- **Yahoo Finance API** – data collection

## System Architecture

The system architecture includes:
- **Data Collection** from Yahoo Finance
- **Preprocessing**: handling missing values, scaling
- **Feature Engineering**
- **LSTM Model** training and evaluation
- **Prediction and Visualization** of results

## Installation

1. Clone the repository:
  
   git clone https://github.com/jaithunshifaya/Stock-Price-Prediction.git
   
   cd Stock-Price-Prediction

2. Install the required packages:

   pip install -r requirements.txt
   
3. Run the main script:

   python stock_predictor.py
  
## Usage

- Modify the stock symbol and date range in the script as required.

- Use the plots to analyze predictions vs. actual performance.

- Results are displayed in both graphical and numerical formats.

## Results

The model achieved:
- **Prediction Accuracy:** ~90%
- **RMSE:** 0.045
- Strong alignment between actual and predicted prices across test sets.
- Visual trend graphs that reflect stock market patterns clearly.

## Future Work
- Integrate attention mechanisms or Transformer models
- Include news sentiment analysis and social media trends
- Develop a web-based dashboard for real-time interaction
- Improve model adaptability across varying market conditions

## Connect
📧 Email: jaithunshifaya@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/jaithun-shifaya03

Thank you for stopping by!
   
