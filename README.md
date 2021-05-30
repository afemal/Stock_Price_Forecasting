# Stock Price Forecasting
## Predictive Analytics

### Introduction
Financial investing is an effective way to create monetary growth and appreciation. Stocks offer a return on investment when stock prices increase. The average annual stock market return is approximately 10% but vary greatly between each company (Royal & O'Shea, 2021). Though they have the potential to be very profitable, stocks can be volatile and can also contribute to financial loss. Though losses are inevitable, risk management can help mitigate them. One way to minimize the risk is through stock price forecasting. 

### Tools
* Python and Jupyter Notebook 
* Libraries
  * pandas
  * numpy
  * math
  * matplotlib
  * seaborn
  * plotly
  * warnings
  * sklearn
  * statsmodel
  * keras

### Data
Historical [Disney](https://github.com/afemal/Stock_Price_Forecasting/blob/main/data/DIS.csv), [Comcast](https://github.com/afemal/Stock_Price_Forecasting/blob/main/data/CMCSA.csv), [Viacom](https://github.com/afemal/Stock_Price_Forecasting/blob/main/data/Viacom.csv), and [Netflix](https://github.com/afemal/Stock_Price_Forecasting/blob/main/data/Netflix.csv) stock data obtained from Yahoo Finance, ranging from the earliest available data of each to April 22, 2021.  

### Modeling Methods
* Autoregressive Integrated Moving Average (ARIMA) 
* Long Short-Term Memory (LSTM)

### Conclusion
The ARIMA model outperformed the LSTM model, with lower root mean square errors for all companies. The resulting RMSE for Disney, Comcast, Viacom, and Netflix were 3.56, 0.91, 2.22, and 13.14, respectively.  

### Navigation
* Stock Price Forecasting.ipynb: Data prep, EDA, and analysis conducted in Jupyter Notebook (Python) 
* Final Paper.pdf: Documentation of my findings.

### Presentation
[![stockpriceforecasting](https://user-images.githubusercontent.com/61814648/120120457-3e33e700-c152-11eb-927d-bae71d2eec69.png)](https://youtu.be/cV5D9zP-ze0)

