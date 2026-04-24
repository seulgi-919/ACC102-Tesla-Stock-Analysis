# Tesla Financial & Stock Analysis (2023-2025)

## 1. Problem Definition
The goal of this project is to analyze the relationship between Tesla's quarterly financial performance (Revenue/Deliveries) and its stock price volatility.

- **Target Audience**: Potential retail investors and automotive industry analysts looking to understand Tesla's market trends and make informed investment decisions based on historical stock data and financial metrics.

## 2. Dataset Information
- **Sources**: Data was obtained from Yahoo Finance (stock prices) and Tesla Investor Relations (quarterly financial performance such as revenue, deliveries, etc.).
- **Access Date**: April 2026.
- **Data Types**: 
  - Stock data (Tesla stock price and volume) from Yahoo Finance.
  - Quarterly financial data (Revenue, Deliveries, etc.) from Tesla's Investor Relations page.
  
## 3. Analysis Workflow
This project utilizes Python to:

1. **Data Acquisition**: Fetching Tesla stock data via `yfinance` and financial performance data from Tesla's Investor Relations page.
2. **Data Cleaning**: Handling missing values and formatting dates to ensure compatibility for analysis.
3. **Exploratory Analysis**: 
   - Calculating moving averages to identify long-term trends.
   - Calculating quarterly growth rates to track financial performance.
4. **Visualization**: Creating charts to:
   - Show stock price trends over time.
   - Show trading volume and daily returns distribution.
   - Correlate stock performance with financial performance data.

## 4. Demo Video
Here is the demo video showcasing the analysis:  
[Watch the video](https://youtu.be/Z5FhbIrdliI?feature=shared)

## 5. How to Run
To run the analysis locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tesla-stock-analysis.git
