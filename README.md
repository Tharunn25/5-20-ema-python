
# EMA Crossover Strategy

This Python code implements an EMA (Exponential Moving Average) crossover strategy for generating buy and sell signals based on the crossover of short-term and long-term EMAs.


## Dependencies

The code relies on the following dependencies:

pandas

numpy

matplotlib

You can install these dependencies using the following command:

pip install pandas numpy matplotlib

#Screenshots

<img width="546" alt="image" src="https://github.com/Tharunn25/5-20-ema-python/assets/98308855/9830b69f-ff43-4abd-88d8-73a326aed639">


## Usage

1.Prepare the data file:

->Replace 'BN.csv' with the appropriate file path to your own dataset in the code.

->Make sure the data file contains a column named 'Close' that represents the closing prices of the asset.

2.Set the input variables:

->emaShortLength: The length (period) of the short-term EMA.

->emaLongLength: The length (period) of the long-term EMA.

->reward_ratio: The desired risk-reward ratio for setting target and stop-loss prices.

3.Run the code:

->Execute the Python script to run the EMA crossover strategy.

->The script will plot the closing prices, the short-term and long-term EMAs, and indicate the buy and sell signals on the chart.

->The generated buy and sell signals will be printed in the console, along with the corresponding entry, target, and stop-loss prices.

## Example

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

Define the input variables

emaShortLength = 5

emaLongLength = 20

reward_ratio = 2  # Risk-reward ratio

Read the data into a DataFrame (replace with your own data)

data = pd.read_csv('BN.csv')

Close = data['Close']

 Rest of the code...
 ...

This project is licensed under the MIT License.


## Pin Script Version

The pin Script of the same code version is mentioned in the below github feel free to checkout and implement in Tradingview.

https://github.com/Tharunn25/5-20-Ema-corssover-strategy
