# 📊 Statistical Analysis on Global and Indian Equity Market  

## 📌 Project Overview  
This project analyzes and compares the **Global and Indian equity markets** using statistical and time series forecasting techniques.  
The study focuses on stock price dynamics of leading companies—**TCS, Infosys (India), Apple, Alphabet (USA), Fujitsu, and NEC (Japan)**—to identify patterns, trends, and provide forecasts.  

The project applies **ARIMA (Autoregressive Integrated Moving Average) models** to predict future stock movements and evaluates forecast accuracy using **MPE (Mean Percentage Error)** and **MAPE (Mean Absolute Percentage Error)**.  

---

## 🎯 Objectives  
- Understand the behavior of **stock prices** in global and Indian equity markets.  
- Apply **time series forecasting (ARIMA models)** for stock price prediction.  
- Compare forecast performance across companies from **different regions**.  
- Assess accuracy using statistical error measures.  
- Provide insights into **market trends, seasonality, and volatility**.  

---

## 📊 Dataset  
- **Source:** Yahoo Finance  
- **Period Covered:** 1st April 2019 – 31st March 2024 (5 years)  
- **Frequency:** Daily stock prices (Adjusted Close values)  
- **Companies Analyzed:**  
  - TCS (India)  
  - Infosys (India)  
  - Apple (USA)  
  - Alphabet (USA)  
  - Fujitsu (Japan)  
  - NEC Corporation (Japan)  

---

## 🛠️ Methodology  
1. **Exploratory Data Analysis (EDA):**  
   - Trend and seasonality decomposition.  
   - Moving averages (weekly, monthly, yearly).  

2. **Stationarity Check:**  
   - Augmented Dickey-Fuller (ADF) Test.  
   - Differencing applied to achieve stationarity.  

3. **ARIMA Modeling:**  
   - Auto ARIMA used to select optimal (p,d,q) parameters.  
   - Model validation using residual diagnostics (Ljung-Box test).  

4. **Forecasting:**  
   - Short-term stock price predictions generated.  
   - Visualization of observed vs forecasted values.  

5. **Accuracy Evaluation:**  
   - Mean Percentage Error (MPE).  
   - Mean Absolute Percentage Error (MAPE).  

---

## 🧪 Tools & Technologies  
- **Programming Language:** R  
- **Libraries Used:**  
  - `forecast` – ARIMA modeling & forecasting  
  - `tseries` – time series analysis and ADF test  
- **Techniques:** Time Series Analysis, ARIMA, Correlation, Forecast Accuracy Metrics  

---

## 📈 Key Findings  
- **TCS & Infosys:** Showed strong **seasonality** with moderate forecast accuracy (MAPE ≈ 6–17%).  
- **Apple:** Forecast accuracy was good, with average deviation around **10.7%**.  
- **Alphabet:** Higher deviation (~28%) indicating more volatility.  
- **Fujitsu & NEC:** Showed significant underestimation bias (MAPE ≈ 25% for Fujitsu, 8.8% for NEC).  
- **Overall Insight:** ARIMA performed well in capturing seasonality but struggled with high volatility stocks.  

---

## 🚀 Future Scope  
- Apply advanced models like **SARIMA, Prophet, or LSTM (Deep Learning)** for improved accuracy.  
- Extend study to **more companies and indices** for broader comparison.  
- Incorporate **macroeconomic indicators** (GDP, interest rates, inflation) into forecasting.  

---

## 📚 References  
- Hyndman, Rob J., & Koehler, Anne B. (2006). *Another look at measures of forecast accuracy*.  
- Newbold, P., Miller, W. L., & Thorne, R. J. M. *Statistics for Business and Economics*.  
- Freund, R. J., & Wilson, W. J. *Regression Analysis*.  

---


