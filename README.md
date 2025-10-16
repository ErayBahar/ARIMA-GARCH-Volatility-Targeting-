# Volatility Targeting with ARIMA + GARCH

This repository implements a hybrid **ARIMA–GARCH** model to forecast stock return volatility and perform **dynamic volatility targeting** on Apple (AAPL) daily data.  
---

## 📊 Project Overview

Financial returns are not constant in volatility. ARIMA models capture the predictable component of the **mean**, while GARCH captures the **conditional variance** (volatility clustering).  
This notebook combines both to generate forecasts of next–day volatility and adjusts portfolio exposure accordingly.
---

## 📰 Related Article

Read the full explanation and step-by-step guide on Medium:  
[Volatility Targeting with ARIMA + GARCH — Forecasting and Risk Control in Quant Finance](https://medium.com/your-medium-article-link)


**Workflow:**
1. Data Collection from Yahoo Finance using `yfinance`
2. Mean Modeling via ARIMA
3. Volatility Modeling via GARCH
4. Volatility Targeting for dynamic position sizing
5. Backtesting and performance evaluation

---

## 🧰 Requirements

All dependencies are listed in [`requirements.txt`](requirements.txt).

To install them:

```bash
pip install -r requirements.txt
