# Quantitative Risk Analysis for Hedge Funds

## Objective  
Evaluate portfolio risks and predict volatility to support hedge fund strategies.

## Dataset  
- Source: Yahoo Finance API (5 years of historical data for S&P 500).

## Metrics  
- **Sharpe Ratio**
- **Value at Risk (VaR)**
- **Portfolio Diversification**

## Approach  
1. **Data Collection**: Downloaded stock prices and computed daily returns.  
2. **Monte Carlo Simulation**: Modeled future portfolio scenarios.  
3. **Time-Series Analysis**: Forecasted volatility using ARIMA.

## Results  
- Portfolio VaR: $X at 95% confidence.  
- Sharpe Ratio: 1.2 (indicative of moderate risk-adjusted returns).  

## Visualizations  
- Rolling Volatility [Insert chart]  
- Correlation Heatmap [Insert image]  

## Tools  
Python, NumPy, pandas, scikit-learn, Tableau/Power BI.

## How to Run  
1. Clone the repository.  
2. Install dependencies: `pip install -r requirements.txt`.  
3. Run the script: `python risk_analysis.py`.  
