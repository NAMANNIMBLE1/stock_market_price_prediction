
# Stock Market Price Prediction using LSTM

## Overview

This project aims to predict stock market prices using a Long Short-Term Memory (LSTM) neural network. The dataset is fetched using Yahoo Finance, and data visualization is done using Seaborn and Matplotlib. The model is trained using TensorFlow/Keras.

## Screenshots 
![demo](https://github.com/NAMANNIMBLE1/stock_market_price_prediction/blob/main/images/Screenshot%202025-03-06%20184622.png)
![demo](https://github.com/NAMANNIMBLE1/stock_market_price_prediction/blob/main/images/Screenshot%202025-03-06%20184629.png)
![demo](https://github.com/NAMANNIMBLE1/stock_market_price_prediction/blob/main/images/Screenshot%202025-03-06%20184634.png)
![demo](https://github.com/NAMANNIMBLE1/stock_market_price_prediction/blob/main/images/Screenshot%202025-03-06%20184642.png)
![demo](https://github.com/NAMANNIMBLE1/stock_market_price_prediction/blob/main/images/Screenshot%202025-03-06%20184647.png)
![demo](https://github.com/NAMANNIMBLE1/stock_market_price_prediction/blob/main/images/Screenshot%202025-03-06%20184654.png)

## Acknowledgements

- [Yahoo Finance for stock data](https://finance.yahoo.com)
- [TensorFlow/Keras for deep learning](https://keras.io/api/)

- [Seaborn & Matplotlib for data visualization](https://seaborn.pydata.org/)
## Features

- Fetch real-time stock data using Yahoo Finance API
- Perform exploratory data analysis (EDA) with Seaborn and Matplotlib
- Preprocess data for LSTM model training
- Train and evaluate the LSTM model for price prediction
- Visualize the predicted vs. actual stock prices


## Installation

Install my-project-dependencies with pip

```bash
  pip install yfinance 
```
### For data analysis and preprocessing 
```bash
  pip install matplotlib 
  pip install numpy 
  pip install scikit-learn 
  pip install seaborn 
```
### For neural network 
```bash
  pip install tensorflow
  pip install keras 
```


## Roadmap

- downloading or accesing the real time data from yahoo finance 

- visualization of data and preprocesing 
- feeding the data to LSTM 
- predictions  made on prepared test data 
- predicted next unknown days predictions

## Results

After training the LSTM model, the predicted stock prices are visualized against actual prices using Matplotlib and Seaborn. The model’s performance is evaluated using Mean Squared Error (MSE) as it is a regression problem to be solved not categorical.
## Future Improvements 


- Implement hyperparameter tuning for better model performance

- Experiment with different activation functions and optimizers

- Incorporate additional features like trading volume and techniccal analysis 

-- using some more advance indicators on trading view.com 
## License

[MIT](https://choosealicense.com/licenses/mit/)


## Authors

- [@NAMANNIMBL1](https://github.com/NAMANNIMBLE1)

