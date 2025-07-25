\## Backtesting Framework for Technical Analysis Trading



\*\*Outline of project flow\*\*

1\. Fetch historical price data for AAPL, NVDA, GOOG, and META from Yahoo Finance for the past 10 years from period of 2013-01-01 to present date.

2\. Create indicator functions to calculate relevant indicator parameters (RSI / MACD / Bollinger Bands).

3\. Use the indicator parameters to generate buy / sell signals for any given stock. We shall let the technical signal be:

&nbsp;   o = 'nil',

&nbsp;   1 = 'buy' signal,

&nbsp;   -1 = 'sell' signal



&nbsp;   This means that whenever a stock has indication that it is overbought, we sell with signal -1 and vice versa.



4\. Create a backtesting pipeline that utilises the trading signals to execute trades while accounting for transaction costs.

5\. Formulate metric calculation function for results input from backtest.

6\. Generate metrics.

