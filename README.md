<!DOCTYPE html>
<html lang="en">

<body>
    <h1>Google Stock Price Prediction</h1>
    <p>This repository contains an LSTM (Long Short-Term Memory) model to predict Google stock prices. The model is implemented in Python using popular libraries such as TensorFlow, Keras, and Pandas.</p>

This repository contains an LSTM model to predict Google stock prices using historical data. The model is built with TensorFlow and Keras.

## Introduction
Long Short-Term Memory (LSTM) networks, which are adept at capturing long-term dependencies in time series data, the model is built with TensorFlow and Keras. These powerful libraries facilitate the construction and training of deep learning models for accurate stock price prediction.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/SarthakGadge/Google-Stock-price-prediction.git
    cd Google-Stock-price-prediction
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Data Preprocessing:**
    ```bash
    python src/data_preprocessing.py
    ```

2. **Model Training:**
    ```bash
    python src/model_training.py
    ```

3. **Model Evaluation:**
    ```bash
    python src/model_evaluation.py
    ```

## Dataset

The dataset includes historical Google stock prices:
- `Google_Stock_Price_Train.csv`: Training data
- `Google_Stock_Price_Test.csv`: Test data

## Model Architecture

The LSTM model includes:
- Input layer
- LSTM layers with dropout
- Dense output layer

The model uses the Adam optimizer and mean squared error loss function.

## Results

Model performance is evaluated using RMSE. Detailed results and visualizations are available in the  notebook.

