# LSTM-MC-model-for-Portfolio-Optimization---A-High-Frequency-Data-approach

A Deep Learning-Monte Carlo Sampling method is introduced in the context of Portfolio Allocation for cryptocurrencies. Different LSTM-based Neural Networks are trained on high granularity Limit Order Book data in order to predict future returns. The predictions are then used to perform Monte Carlo sampling to approximate the optimal weights of the portfolio, that maximise the Sharpe Ratio. The training is performed on several contiguous days of high frequency data (ns), the last ten hours of which constitute the testing set. We compare the Deep Learning methods to other portfolio construction methods such as 1/N, random, and Monte Carlo simulations (directly on training data). The Sharpe Ratio, Expected Return and Volatility are used as metrics to measure how efficient a portfolio is. This project is made for COMP0162 - Advanced Machine Learning in Finance @ UCL.
