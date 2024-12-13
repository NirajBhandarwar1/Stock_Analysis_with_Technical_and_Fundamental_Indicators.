
# Stock Analysis with Technical and Fundamental Indicators


## Overview
This project focuses on analyzing stock performance using both technical and fundamental indicators. By leveraging Yahoo Finance data, various technical indicators such as Moving Averages, RSI, Bollinger Bands, and Average True Range are implemented and visualized. Additionally, fundamental indicators like EPS, P/E Ratio, ROE, Debt-to-Equity Ratio, and Dividend Yield are calculated and displayed to provide insights into the stock's financial health. The visualizations are created using Plotly to enable interactive exploration of the data.

## Key Highlights
- Technical Indicators:
  - Moving Averages (SMA, EMA): Analyzed short-term and long-term trends using simple and exponential moving averages.
  - RSI (Relative Strength Index): Calculated the momentum of the stock to identify overbought or oversold conditions.
  - Bollinger Bands: Used to measure volatility and potential price levels.
  - Average True Range (ATR): Assessed market volatility over a specific period.
- Fundamental Indicators:
  - EPS (Earnings Per Share): Measures a company's profitability on a per-share basis.
  - P/E Ratio (Price-to-Earnings): Provides insights into stock valuation.
  - ROE (Return on Equity): Indicates financial performance and efficiency.
  - Debt-to-Equity Ratio: Evaluates a company's financial leverage.
  - Dividend Yield: Shows the return on investment for dividend-paying stocks.
- Visualization:
  - Visualized all indicators using Plotly for interactive charts.
  - Plotted technical indicators (e.g., moving averages, Bollinger Bands) on stock price charts.
  - Displayed fundamental metrics in easy-to-read plots for comparison.

##  Dependencies
Install the following Python libraries to run this project:

- pandas
- numpy
- matplotlib
- seaborn
- yfinance
- plotly
- talib (for technical indicators)
## Methodology
- Data Collection:
  - Stock data (price and volume) was collected using Yahoo Finance via the yfinance library.
  - Calculated key fundamental indicators (EPS, P/E Ratio, etc.) from publicly available financial data.
- Technical Indicators:
  - Calculated SMA, EMA, RSI, Bollinger Bands, and ATR using the talib library or custom functions.
- Fundamental Indicators:
  - Retrieved fundamental data directly from Yahoo Finance for stocks and calculated the metrics such as P/E Ratio and ROE.
- Visualization:
  - Used Plotly to create interactive charts for both technical and fundamental indicators.
  - Visualized stock price trends, moving averages, and volatility indicators.
  - Displayed financial ratios and other fundamental indicators in bar and line charts for better comparison.

## Conclusion
This project provides a comprehensive analysis of stocks using both technical and fundamental indicators. The interactive visualizations created with Plotly allow users to explore different aspects of stock performance, from price trends to financial health. By integrating both types of indicators, investors can make more informed decisions.
## Future Improvements

- More Indicators: Implement additional technical indicators such as MACD, Stochastic Oscillator, etc.
- Multi-Stock Comparison: Extend the project to compare multiple stocks side by side.
- Real-Time Data: Integrate with APIs to provide real-time stock data and dynamic analysis.

##  Dependencies
Install the following Python libraries to run this project:

- pandas
- numpy
- matplotlib
- seaborn
- yfinance
- plotly
- talib (for technical indicators)