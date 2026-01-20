Trader Behavior Insights Based on Market Sentiment

Overview:
This project analyzes how Bitcoin market sentiment (Fear & Greed Index) influences trader behavior using Hyperliquid trading data.

Datasets:
1. Bitcoin Fear & Greed Index – provides market sentiment classification.
2. Hyperliquid Historical Trader Data – provides trader activity and performance.

Methodology:
- Cleaned and processed both datasets using Python.
- Aligned trader data with sentiment data using date.
- Analyzed profitability, win rate, trade size, and trade activity.
- Visualized profit distribution by sentiment.

Key Insights:
- Highest profitability and win rate during Extreme Greed phases.
- Fear phases show higher trading activity but lower efficiency.
- Trade size used as a proxy for risk exposure.

Data Limitation:
Leverage information was not available in the dataset, so trade size (USD) was used as a proxy.

Outputs:
- notebook_1.ipynb: Full analysis
- ds_report.pdf: Summary report
- outputs/: Visualizations
- csv_files/: Processed data

Tools:
Python, Pandas, Matplotlib, Google Colab

Author:
Dhakshayani Reddypalli
