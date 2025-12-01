# Bitcoin-Price-Prediction
This project applies Long Short-Term Memory (LSTM) neural networks to forecast the closing price of Bitcoin using historical time-series data. The workflow includes preprocessing, feature engineering, model building, tuning, and evaluation.

🔍 Features

Uses historical cryptocurrency price data (Open, High, Low, Close, Volume)

Converts time-series data into supervised learning format using sliding windows

Implements LSTM architecture for sequential pattern learning

Includes dropout, early stopping, and learning rate scheduling to prevent overfitting

Compares performance against a baseline forecasting method

Visualizes predicted vs actual closing prices

🧠 Tech Stack

Python

TensorFlow / Keras

Pandas, NumPy

Matplotlib / Seaborn

Scikit-learn

🚀 Model Workflow

Load and clean historical Bitcoin dataset

Normalize values using MinMax scaling

Create time window sequences for training

Build and train the LSTM network

Tune model parameters for stability

Evaluate performance and visualize results

📈 Results

The final model demonstrated improved stability and trend prediction compared to the baseline moving-average model.

The visualization plot shows predicted values closely following real market behavior.

▶ How to Run
pip install -r requirements.txt
python train.py

📬 Future Improvements

Integrate sentiment analysis (Twitter/news)

Deploy as a web dashboard

Experiment with hybrid LSTM + GRU models
