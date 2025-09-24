# Trader-Sentiment-Analysis
 
**Project: Trader Behavior Insights Based on Bitcoin Market Sentiment**


**Overview**
This project analyzes the relationship between Bitcoin market sentiment and trader performance using two datasets: Historical Trader Data from Hyperliquid and the Bitcoin Fear/Greed Market Sentiment dataset. Analytical insights and visualizations are provided to understand how market emotions affect trading behavior and profitability.

**Dataset Description**
fear_greed_index.csv: Contains daily Bitcoin market sentiment values and classifications (Fear, Greed, Neutral, etc.) indexed by date.

historical_data.csv: Contains trade-level data including account, coin, execution price, size, trade side, profit/loss, fees, and timestamps.


**Project Structure**
text
ds_<yourname>/
│
├── notebook_1.ipynb              # Main analysis notebook (Google Colab)
├── csv_files/                    # Stores original and processed CSV files
│     ├── fear_greed_index.csv
│     └── historical_data.csv
├── outputs/                     # Visual output images (charts, graphs)
│     ├── win_rate_by_sentiment.png
│     └── avg_fee_by_sentiment.png
├── ds_report.pdf                # Final summarized report document
└── README.md                    # This file
How to Run
