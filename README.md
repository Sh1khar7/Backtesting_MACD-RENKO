# Backtesting_MACD-RENKO

Backtesting a trading strategy based on the technical indicators namely, MACD & Renko on historical data for high performing tech stocks of MICROSOFT, GOOGLE & APPLE and also evaluating the KPIs (Key Performance Indicators)

- **Buy Signal:** Renko bar >= 2; MACD line above Signal line; MACD line’s slope greater than Signal line’s
slope (over last 5 periods).
- **Sell Signal:** Renko bar <= 2; MACD line below Signal line; MACD line’s slope less than Signal line’s
slope (over last 5 periods).

**Useful libraries to be installed:**
- numpy
- pandas
- stocktrends
- statsmodels.api
- alpha_vantage
- copy 
- matplotlib.pyplot 
