# 5G Network Traffic Prediction using LSTM

This project focuses on predicting 5G network traffic using a Long Short-Term Memory (LSTM) model. The goal is to forecast future network traffic based on historical data, which can help in optimizing network resources and improving performance.

---

## Project Overview
Predicting network traffic is crucial for efficient resource management in 5G networks. This project uses a synthetic dataset to simulate 5G network traffic and trains an LSTM model to predict future traffic volumes. The model is implemented using TensorFlow and Keras.

### Key Features:
- Synthetic 5G network traffic data generation.
- Time series forecasting using LSTM.
- Evaluation metrics: Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

---

## Dataset
Since real-world 5G network traffic data is often proprietary or unavailable, this project uses a **synthetic dataset** that mimics real-world traffic patterns. The dataset includes:
- **Timestamp**: Time of each data point (10-minute intervals).
- **Traffic Volume**: Simulated network traffic volume.

The synthetic data is generated using the following components:
- **Base Traffic**: Constant traffic volume.
- **Trend**: Linear increase in traffic over time.
- **Seasonality**: Daily repeating patterns.
- **Noise**: Random variations to simulate real-world conditions.

---

## Installation
To run this project, you need the following dependencies:

- Python 3.8 or higher
- TensorFlow 2.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
---

## Model Architecture
The LSTM model is implemented using TensorFlow and Keras. The architecture consists of:
- **Input Layer**: Accepts sequences of 50 time steps.
- **LSTM Layer**: 50 units with ReLU activation.
- **Dropout Layer**: 20% dropout for regularization.
- **Output Layer**: Dense layer with 1 unit (predicts traffic volume).

### Hyperparameters:
- **Sequence Length**: 50 time steps.
- **Batch Size**: 32.
- **Epochs**: 20.
- **Optimizer**: Adam.
- **Loss Function**: Mean Squared Error (MSE).

---

## Results
The model achieves the following performance metrics on the test set:
- **Mean Absolute Error (MAE)**: [9.826416002220219] 
- **Root Mean Squared Error (RMSE)**: [12.096928795212959]


## Contact
- **Author**: Samoua Alsamoua
- **GitHub**: [samoua-alsamoua](https://github.com/samoua-alsamoua)
- **Website**: [saalsamoua.github.io](https://samoua-alsamoua.github.io/saalsamoua/)
```
