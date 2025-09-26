# Bitcoin Sentiment Analysis

This project explores the relationship between Bitcoin market sentiment (Fear & Greed Index) and collective trader performance from Hyperliquid's historical data.

## Project Overview

The primary objective was to uncover hidden patterns and deliver data-driven insights that could inform smarter trading strategies. The analysis focused on answering the question: **"How does trader profitability correlate with the emotional state of the market?"**

### **Key Findings**

* **Contrarian Profitability:** The analysis found that the highest average profits were generated on days when the market was in a state of **Fear** or **Extreme Fear**.
* **Weak Negative Correlation:** There is a weak negative correlation between the numeric Fear & Greed Index value and total daily PnL, reinforcing the idea that traders tend to perform better when the market is pessimistic.

## Data Sources

The analysis utilized two primary datasets:
1.  **Bitcoin Fear & Greed Index:** Daily sentiment data.
2.  **Hyperliquid Historical Trader Data:** Detailed trading logs including PnL, size, and execution price.

## Repository Contents

* `crypto_analysis.ipynb`: The Jupyter Notebook containing all the code for data cleaning, analysis, and visualization.
* `requirements.txt`: A list of all necessary Python libraries to run the analysis.
* `avg_pnl_by_sentiment_bar_chart.png`: A visualization of the key findings.

## How to Run the Analysis

1.  Clone this repository:
    ```bash
    git clone [https://github.com/Aishhj/Bitcoin-Sentiment-Analysis.git](https://github.com/Aishhj/Bitcoin-Sentiment-Analysis.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd Bitcoin-Sentiment-Analysis
    ```
3.  Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```
4.  Open the `crypto_analysis.ipynb` notebook in VS Code or Jupyter and run the cells.

## Author

[Your Name or GitHub Username]
