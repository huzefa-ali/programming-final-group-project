#  Technical Trading Strategy Backtesting Project

This project evaluates the performance of multiple **algorithmic technical trading strategies** applied to a technology-focused portfolio and benchmarked against **ZQQ (BMO NASDAQ-100 ETF)**. The goal is to determine whether active technical strategies can outperform a passive benchmark on a **risk-adjusted basis**.

A total of **12 trading strategies** were implemented, backtested over a 10-year period, and evaluated using standardized performance metrics including **total return, Sharpe ratio, volatility, and maximum drawdown**.

---

## Setup Instructions

Follow these steps to run the project locally:

###  Clone the Repository

```bash
git clone <your-repo-url>
cd <your-repo-name>
```

###  Install Required Dependencies

Ensure you are using **Python 3.8+**, then install the required libraries:

```bash
pip install numpy pandas matplotlib yfinance great-tables nltk scikit-learn
```

If using Jupyter:

```bash
pip install notebook
```

---

###  Launch the Notebook

```bash
jupyter notebook
```

Open the main compiled strategy notebook from the project directory.

---

### 4️ Run the Full Backtest

Run all cells from top to bottom to:

* Load ETF and stock data
* Generate trading signals
* Compute daily returns
* Plot equity curves
* Generate performance tables

---

##  Performance Metrics Used

Each strategy is evaluated using:

* **Total Return**
* **Annualized Return**
* **Annualized Volatility**
* **Sharpe Ratio**
* **Maximum Drawdown**
* **Calmar Ratio**
* **Daily Win Rate**
* **Monthly Win Rate**

All strategies were standardized using a **common plotting and evaluation framework** for fair comparison.

---

##  Team Contributions

Each group member contributed actively to **coding, debugging, presentation delivery, and report writing**, as outlined below.

---

##  **Huzefa’s Contributions**

### **Coding & Debugging**

* Set up and structured the project **GitHub repository**
* Guided team members on proper **Git workflows** (clone, branch, push, pull, merge conflict resolution)
* Helped team members **navigate and integrate their individual strategy files** into the unified framework
* Researched, selected, and implemented three strategies:

  * SMA Crossover
  * Z-Score Mean Reversion
  * SMA + VADER Sentiment
* Fully implemented and backtested all three strategies using the shared **functional backtesting framework**
* Ensured all strategies followed:

  * Correct signal generation
  * Proper position logic
  * Look-ahead bias prevention
* Debugged incorrect signals, performance inconsistencies, and plotting errors across multiple strategy files
* Fixed evaluation metric mismatches between strategy outputs and benchmark results
* Compiled **all individual members’ strategy implementations into one unified notebook**
* Standardized **all 12 strategies** to use:

  * A **common equity curve plotting function**
  * A **single performance evaluation function**
* Cleaned code formatting, comments, and documentation for **consistency and readability**
* Verified that all strategies were:

  * Correctly implemented
  * Properly aligned with the benchmark
  * Producing clean, comparable outputs

---

### **Presentation Preparation & Delivery**

* Designed and delivered slides for:

  * SMA Crossover
  * Z-Score Mean Reversion
  * SMA + VADER Sentiment
* Delivered the **final conclusion** during the presentation
* Led and coordinated multiple **team practice sessions**
* Helped teammates refine:

  * Strategy explanations
  * Market intuition
  * Risk-adjusted performance interpretation

---

### **Report Writing & Academic Contribution**

* Wrote three Data Analysis strategy sections:

  * SMA Crossover
  * Z-Score Mean Reversion
  * SMA + VADER Sentiment
* Added summary sentences to the **Abstract**
* Fully authored the **Discussion section**
* Fully authored the **Conclusion section**
* Helped refine academic tone and formatting consistency
* Built and finalized this **GitHub README.md**

---

##  **Brennan’s Contributions**

### **Coding & Debugging**

* Researched and selected **ZQQ** as the Canadian ETF benchmark
* Pulled ETF and stock data using **yfinance**
* Performed EDA on:

  * ZQQ price history (10 years)
  * Current top holdings
  * Small-multiples price visualizations
* Implemented:

  * EMA Crossover
  * Filter System
  * Comparative Relative Strength
* Identified and fixed **look-ahead bias**
* Defined:

  * Equity curve plotting function
  * Key performance metric evaluation function
* Implemented **great_tables** for evaluation display
* Added **risk-adjusted results EDA**

---

### **Presentation**

* Delivered slides for:

  * Project introduction
  * Dataset overview
  * EDA & limitations
  * EMA, Filter System, and CRS strategies

---

### **Report Writing**

* Formatted report in **APA 7**
* Wrote:

  * Introduction
  * Literature Review
  * Methodology
  * Strategy 1–3 sections
* Added figures to appendix
* Wrote initial **Abstract** sentences

---

##  **Jay’s Contributions**

### **Coding & Debugging**

* Implemented:

  * RSI Oversold/Overbought
  * Donchian Channel Breakout
  * Bollinger Band Reversal
* Verified cumulative performance charts and evaluation metrics
* Ensured consistency across strategy structure
* Assisted with debugging and visual clarity

---

### **Presentation**

* Created slides for:

  * RSI
  * Donchian
  * Bollinger
* Edited slides for:

  * Supertrend
  * ROC
  * Volume-Weighted Momentum
* Presented six strategies total

---

### **Analysis & Interpretation**

* Wrote performance explanations
* Helped compare strategies vs. benchmark
* Contributed to results interpretation

---

### **General Support**

* Helped organize the final notebook
* Performed final consistency and quality checks

---

##  **Shayan’s Contributions**

### **Coding & Debugging**

* Built full backtesting systems for:

  * Supertrend
  * Rate of Change (ROC)
  * Volume-Weighted Momentum (VWM)
* Debugged ATR alignment, volume issues, overlapping outputs
* Built daily return computation and benchmark comparison
* Refactored plotting visuals for clarity

---

### **Data Analysis**

* Conducted full performance evaluation:

  * Total return
  * Sharpe ratio
  * Volatility
  * Max drawdown
* Identified that all three strategies outperformed ZQQ
* Interpreted similar behaviors between ROC and VWM

---

### **Visualization & Presentation**

* Designed combined and individual performance charts
* Simplified strategy explanations for presentation delivery

---

### **Report Writing**

* Wrote academic sections for:

  * Supertrend
  * ROC
  * VWM
* Added detailed interpretations and Investopedia citations
* Polished writing for clarity and consistency

---

## Final Notes

* All strategies were evaluated using a **common standardized framework**
* The project emphasizes **risk-adjusted performance**
* Real-world limitations such as transaction costs and taxes were addressed in the report

