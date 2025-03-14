BBRI Stock Price Prediction using LSTM

📌 Project Overview

This project implements a Long Short-Term Memory (LSTM) model to predict BBRI (Bank Rakyat Indonesia) stock prices using historical data. The repository contains a Jupyter Notebook for training the model and a CSV file with stock price data.


🔧 Installation & Setup

Clone the Repository

git clone https://github.com/yourusername/bbri-stock-prediction.git
cd bbri-stock-prediction

Create a Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install Required Dependencies

pip install -r requirements.txt

Open the Jupyter Notebook

jupyter notebook

Then, navigate to notebooks/bbri_stock_lstm.ipynb and run the cells step by step.

📊 Dataset

The dataset (data/bbri_stock_data.csv) contains historical stock prices for BBRI.

Columns include:

Date → Date of stock price record

Open → Opening price

High → Highest price of the day

Low → Lowest price of the day

Close → Closing price (used for prediction)

Volume → Number of shares traded

🔍 Model & Training

Uses an LSTM neural network (a type of Recurrent Neural Network - RNN) to learn patterns in stock price movements.

Data Preprocessing:

Load data and handle missing values

Normalize stock prices using MinMaxScaler

Convert time series data into sequences for LSTM input

LSTM Model Architecture:

Input layer

LSTM layers with dropout

Dense output layer for predicting stock price

Training & Evaluation:

Train model on past stock price data

Evaluate on validation/test set

Visualize loss and prediction results

🚀 Running the Prediction

After running the notebook, the model will output:

Stock price predictions for future days

Plots comparing actual vs. predicted stock prices

📌 Future Improvements

Incorporate technical indicators (e.g., moving averages, RSI, MACD)

Optimize hyperparameters (e.g., sequence length, learning rate, dropout)

Implement attention mechanisms for better feature importance analysis

📞 Contact

For any issues or suggestions, feel free to open an issue or reach out!

📌 Happy coding and stock predicting! 📈
