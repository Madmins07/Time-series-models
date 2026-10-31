<div align="center">
  <img src="assets/banner.svg" alt="Time Series Models. ARIMA on USD/INR. Stationarity tests, ACF and PACF, walk-forward RMSE." width="100%"/>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/jupyter-notebook-A6BDAD?style=flat-square&labelColor=0B0E0D&logo=jupyter&logoColor=EEF1ED" alt="jupyter notebook"/>
  <img src="https://img.shields.io/github/last-commit/Madmins07/Time-series-models?style=flat-square&labelColor=0B0E0D&color=788A7F&label=updated" alt="last-commit"/>
  <img src="https://img.shields.io/github/license/Madmins07/Time-series-models?style=flat-square&labelColor=0B0E0D&color=5A6A60" alt="license"/>
</div>

## about

Forecasting the **USD/INR** exchange rate with ARIMA, the proper way round: test for stationarity first, read the
ACF and PACF to pick the order, fit, then evaluate with a rolling one-step walk-forward and RMSE instead of a single
in-sample fit.

## notebooks

| notebook | what it does | open |
|:--|:--|:--|
| [`ARIMA_USD_INR_PREDICTOR.ipynb`](ARIMA_USD_INR_PREDICTOR.ipynb) | ADF test, differencing, ACF/PACF, ARIMA(2,1,0) fit, walk-forward RMSE and plots. | <a href="https://colab.research.google.com/github/Madmins07/Time-series-models/blob/main/ARIMA_USD_INR_PREDICTOR.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a> |

## data

The notebook reads `data.csv` with a `DEXINUS` column, which is the daily USD/INR series from FRED. Download it from
[fred.stlouisfed.org/series/DEXINUS](https://fred.stlouisfed.org/series/DEXINUS) and drop the CSV next to the notebook.

---

<div align="center">
  <sub>Part of <a href="https://github.com/Madmins07">Madmins07</a> · Madhav Agarwal · IIT Kharagpur</sub>
</div>
