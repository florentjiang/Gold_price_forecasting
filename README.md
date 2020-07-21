# Gold Price Forecast

The task is to forecast **gold spot price** on *Jul 24, 2020*. As a summary, the following **four models** are invested and fine-tuned:
- Autoregressive **(AR)** Model of order 0 to 50, in **Sec.3.2**
- Autoregressive Distributed Lag **(ADL)** Model of order 0 to 20, in **Sec.3.3**
- Autoregressive Distributed Lag **(ADL)** Model of order 15 with consideration of **structural break**, in **Sec.3.7**
- Seasonal Autoregressive Integrated Moving Average **(SARIMA)** Model, in **Sec.3.8**

Data analysis **techniques** are performed and several **functions** are implemented for following purpose:
- Cross correlation, in **Sec.3.1**
- Stationarity test using Augmented Dickey Fuller **(ADF)** Test, in **Sec.3.4**
- Time series decomposition, in **Sec.3.5**
- Structural break test using **Chow Test**, in **Sec.3.6**

Auxiliary **data** are supposed to be useful according to literature, and are analyzed carefully:
- Crude oil price
- Silver price
- S&P 500 index
- Gold future price
- Google search trend for "gold investing"