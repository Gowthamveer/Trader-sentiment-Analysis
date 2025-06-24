📊 Trader Behavior vs Market Sentiment – Insights

1. Objective

To analyze how market sentiment, represented by the Bitcoin Fear-Greed Index, influences trading behavior and performance. We use historical trader data from Hyperliquid and sentiment data to uncover patterns that can inform trading strategies.

2. Data Overview

Fear-Greed Index: Contains daily market sentiment values (0-100) and classifications (e.g., Fear, Greed).

Trader Data: Includes trade-level records with execution price, side (buy/sell), closed PnL, size, leverage, fees, and timestamp.

3. Methodology

Preprocessed timestamps and merged both datasets on daily basis.

Calculated aggregate metrics per day: total PnL, average PnL, total trade count, total volume, average fee.

Correlated sentiment values with trader performance.

Segmented analysis by sentiment classification.

Visualized time-series and distributions.

4. Key Findings

✅ Positive correlation between sentiment and trading volume: Greed periods see increased trading activity.

✅ Slight positive correlation between sentiment and total PnL: Traders tend to perform better when sentiment is higher.

⚠️ Extreme Fear periods show lower average PnL: Possible hesitation or panic-driven decisions.

✅ Fees remain stable across sentiment classifications.

5. Recommendations

Reduce leverage or avoid overtrading during Extreme Fear.

Consider using sentiment value as a feature in predictive trading models.

Design different strategies based on sentiment regime (momentum in Greed, hedging in Fear).

6. Visual Highlights

Correlation matrix between sentiment and performance metrics.

Scatter plot of Total PnL vs Sentiment Value.

Time-series of sentiment vs trader performance.

Boxplots comparing PnL distributions across sentiment types.

7. Tools Used

Python, Pandas, Seaborn, Matplotlib

Jupyter Notebook for analysis

8. Directory Structure

/Trader-Sentiment-Analysis
├── /data/
│   ├── fear_greed_index.csv
│   ├── historical_data.csv
├── /notebooks/
│   └── analysis.ipynb
├── README.md

9. Authors

Prepared by: Gowtham Veer

Role: Junior Data Scientist Candidate

Contact: gowthamveer005@gmail.com

10. Submission

Sent to:

saami@bajarangs.com

nagasai@bajarangs.com

CC: sonika@primetrade.ai

Subject: "Junior Data Scientist – Trader Behavior Insights"

