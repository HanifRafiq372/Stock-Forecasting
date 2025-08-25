
---

## 📈 Visualizations Generated
1. Distribution of Closing Price & Trading Volume  
2. Price & Volume Trends (2020–2024)  
3. Correlation Heatmap (Features: RSI, MACD, Bollinger Bands, Volume)  
4. Forecast Comparison (Naive, ARIMA, LSTM vs Actual)  
5. Residual Diagnostics (Residual plots, ACF, Histogram, QQ-Plot)  
6. 30-Day Forward Forecast (LSTM scenario)  

---

## 🧪 Evaluation Summary
| Model  | RMSE   | MAPE   | Directional Accuracy (%) |
|--------|--------|--------|---------------------------|
| Naive  | 80.8020  | 0.0132 | NaN      |
| ARIMA  | 481.3355 | 0.0869 | NaN      |
| LSTM   | 212.4340 | 0.0360 | 46.2312  |

> Note: Results may vary due to randomness in training process.

---

## 📦 Installation
Clone repository and install dependencies:
```bash
git clone https://github.com/HanifRafiq372/Stock-Forecasting.git
cd stock-forecasting
pip install -r requirements.txt
