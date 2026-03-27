#  Trader Behavior vs Market Sentiment Analysis

##  Overview

This project analyzes the relationship between trader performance and market sentiment (Fear/Greed) using real trading data.

The objective is to uncover behavioral patterns, evaluate trading performance across sentiment phases, and derive actionable insights for strategy design.

---

##  Dataset

* Historical Trader Data (trade-level execution details)
* Bitcoin Market Sentiment (Fear & Greed Index)

---

##  Methodology

1. Data Cleaning & Preprocessing

   * Standardized column names
   * Converted timestamps to datetime
   * Merged datasets on common date

2. Exploratory Data Analysis

   * Profitability across sentiment phases
   * Trade frequency and participation
   * Buy vs Sell behavior

3. Advanced Analysis

   * Win rate (consistency of traders)
   * Trader performance scoring
   * Sentiment Efficiency Score (SES)
   * Strategy simulation
   * Risk analysis (volatility & max loss)

---

##  Key Insights

### 1. Contrarian Trading Behavior

Traders allocate more capital during Fear phases and reduce exposure during Extreme Greed, indicating a “buy low, sell high” strategy.

### 2. Profitability Peaks in Extreme Greed

Average profits are highest during Extreme Greed, suggesting strong momentum-driven gains in bullish markets.

### 3. Neutral Markets Are Risky

Loss rates are highest during Neutral sentiment, indicating indecision and inconsistent trading behavior.

### 4. Capital Efficiency Varies by Sentiment

A custom metric, **Sentiment Efficiency Score (SES)**, shows that:

* Extreme Greed delivers the highest return per unit capital
* Extreme Fear is highly inefficient

### 5. Strategy Validation

A sentiment-based strategy (trading during Fear phases) demonstrates strong profitability potential.

### 6. Risk Matters

Higher returns in bullish phases are accompanied by increased volatility, emphasizing the importance of risk management.

---

##  Conclusion

Market sentiment plays a significant role in shaping trader behavior and performance.

The analysis shows that sentiment-driven strategies can be effective, but must be combined with proper risk controls to ensure sustainable returns.

---

##  Key Contribution

This project goes beyond basic analysis by:

* Introducing a custom metric (SES)
* Evaluating trader consistency
* Simulating trading strategies
* Incorporating risk-adjusted insights

---

##  Tools Used

* Python (Pandas, NumPy)
* Data Visualization (Matplotlib, Seaborn)
* Jupyter Notebook

---

##  Deliverables

* Analysis Notebook (`analysis.ipynb`)
* Insights & Strategy Interpretation
