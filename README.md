`Stock Market Prediction Using LSTM`
This is project for predicting closing value of stocks.
Dataset:- For the dataset we import it from yfinance library which is Yahoo Finance which gives real-time data of the stock required.
Model:- We use Sequential Model along with Dense, Dropout and LSTM layers. As given in the following image.
<img width="575" alt="Screenshot 2024-04-12 at 11 19 02 PM" src="https://github.com/striver-24/Stock-Market-Prediction-using-LSTM/assets/106349960/ad57384d-2201-4c6c-a731-d687b517387c">
Also, we use MinMax Scaler to calculate the whole data in the range of 0 to 1 because the data is so robust that it can take a dip or rise of many points all together.
