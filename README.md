# Stock Market Prediction using Machine Learning

## Introduction

Stock market prediction or forecasting is a serious challenge for corporate brokers stakeholders and investors. The stock of each company fluctuates in a random manner and becomes hard and risky for investors to invest. In this project, we apply knowledge of machine learning techniques to predict the stock prices of a particular company. The stock market is so volatile and investors don’t want to fall at risk. So an approach with adequate expertise is designed to help investors to ascertain veiled patterns from the historic data that have the feasible predictive ability in their investment decisions. The historical data has a significant role in, helping the investing people to get an overview of the market behavior during the past decade.We have used **ARIMA model** to forecast stock price for short term.

## Result

**Trends of close prices with diffrent shifts**
Week Days | Monthly
:-------------------:|:-------------------------:
![](./Results/1.png) | ![](./Results/3.png)

|   Quarterly trend    |     Yearly trend     |
| :------------------: | :------------------: |
| ![](./Results/4.png) | ![](./Results/2.png) |

**Residual Dickey-Fuller Test**
![Residual Dickey-Fuller Test](./Results/ResDFT.png)
![](./Results/res2DFT.png)

**AutoCorrelation and Partial AutoCorrelation**
![ACF and PACF](./Results/AcPCf.png)

**ARIMA Model with p3 and q2**
![ACF and PACF](./Results/P3Q2.png)

**Forecasting stock price on test data**
![ACF and PACF](./Results/prediction.png)

## Refrences

[1]“TATA CONSULTANCY S (TCS.NS) stock historical prices &amp; data – Yahoo Finance,” Yahoo! Finance, 18-Mar-2021. https://in.finance.yahoo.com/quote/TCS.NS/history?p=TCS.NS

[2] Y. Ng, “Machine Learning Techniques Applied to Stock Price Prediction,” Medium, 03-Oct-2019. https://towardsdatascience.com/machine-learning-techniques-applied-to-stock-price-prediction-6c1994da8001.

[3] Poornima S P, Priyanka C N, Reshma P, Suraj Kr Jaiswal, and SurendraBabu K N, “Stock Price Prediction using KNN and Linear Regression”. 2019 International Journal of Engineering and Advanced Technology (IJEAT), Volume-8, Issue-5S. [Online]. Available: International Journal of Soft Computing and Engineering (ijeat.org)

[4] A. A. Ariyo, A. O. Adewumi, and C. K. Ayo, "Stock Price Prediction Using the ARIMA Model," 2014 UKSim-AMSS 16th International Conference on Computer Modelling and Simulation, Cambridge, UK, 2014, pp. 106-112, doi: 10.1109/UKSim.2014.67.

[5] T. Ozaki, “On the Order Determination of ARIMA Models,” Applied Statistics, vol. 26, no. 3, p. 290, 1977.

[6] “Forecasting: Principles and Practice (2nd ed),” 8.6 Estimation and order selection. [Online]. Available: https://otexts.com/fpp2/arima-estimation.html#arima-estimation. [Accessed: 11-Apr-2021].
