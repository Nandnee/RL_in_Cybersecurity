# Predicting Stock Price using Reinforcement Learning

## 1. Installation
```
git clone https://github.com/lex-hue/Stock-Predictor-V4.git
cd Stock-Predictor-V4
python SPV4.py --install
```


## 2. Data
data.csv file here contains the stock data for Tesla.

## 3. Training the LSTM RL Model

To train the LSTM RL Model with the `data.csv` file, run this command

```
python SPV4.py --train
```

## 4. Evaluating the Model
To evaluate the trained model, run this command

```
python SPV4.py --eval
```

After running this command, the root mean squared error (RMSE), the MAPE and Total Rewards will be plotted.

---


