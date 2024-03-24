# FINM-33150-Projects
FINM 33150 (Winter 2024) Quantitative Trading Strategies Projects

## Futures Spread Dynamics

**Objective:** Explore and characterize dynamics between two pairs in futures markets, focusing on their individual behaviors and mutual relationships.

**Key Components:**
- Data Collection: Obtain second-month quarterly futures prices from Quandl OWF database for specified pairs.
- Spread Formation: Calculate spreads by subtracting futures prices of one asset from another.
- Analysis: Perform statistical analysis on the spreads, such as calculating median, standard deviation, and examining quantiles and tails. Explore correlations between spreads and their patterns over time.

---

## Spread Trading Simulation

**Objective:** Implement a spread-reversion trading strategy based on the displacement between two related financial instruments.

**Key Components:**
- Data Assembly: Acquire adjusted closing prices and daily Fama-French factor returns.
- Strategy Coding: Create a trading algorithm that initiates and closes positions based on specified conditions, maintaining equal-sized dollar amounts in each trade.
- Analysis: Evaluate the strategy's performance varying parameters like stop-loss levels and trading costs, and study its relation to market factors.

---

## Quantile Trading Strategy

**Objective:** Investigate the profit potential of a long-short trading scheme based on financial accounting ratios and quantile analysis.

**Key Components:**
- Data Preparation: Compile data on selected financial ratios for a set of at least 200 US equities.
- Strategy Formulation: Develop weekly or monthly quantile trading strategies, employing single ratios and combinations thereof.
- Analysis: Assess the strategy's effectiveness through performance metrics like Sharpe ratio, drawdowns, and compare PL to traded notional. Explore the impact of different position sizing based on rank.

---

## Trade Flow Strategy

**Objective:** Evaluate trade flow as a predictor for profit opportunities in cryptocurrency markets.

**Key Components:**
- Data Handling: Process level 3 exchange messages into a digestible format and divide into training and test sets.
- Strategy Implementation: Construct a model to predict returns based on trade flow data prior to each trade, setting appropriate thresholds for trade execution.
- Analysis: Measure the effectiveness of return predictions in generating trading opportunities, considering aspects like Sharpe ratios, drawdowns, and the stability of the regression coefficient.

---

## FX Carry Strategy

**Objective:** Implement and evaluate an FX carry strategy, which involves borrowing in a currency with low interest rates and lending in another currency with higher interest rates, typically through a cross-currency swap.

**Key Components:**
- Data Collection: Acquire data on UK overnight index swaps (OIS) rates, spot FX rates for the dollar versus pound, and swap yield curves along with FX rates for the Egyptian Pound, Hungarian Forint, Costa Rican Colon, and Romanian Leu.
- Exercise Procedure: Simulate an approximate P&L for weekly-traded cross-currency fixed-float swaps using OIS rates and swap curves, with a normalized notional of US$10MM at the start of each week.
- Strategy Details: In the borrowing currency, assume a rate of OIS+50bp on 4/5 the notional amount. In the lending currency, assume quarterly coupons at the 5Y swap rate or the 5Y treasury rate, engaging only when the 5Y swap rate of the lending currency is at least 50bp higher than that of the funding currency.
- Analysis: Convert all flows to USD to track cash flows effectively, and evaluate the strategy's performance, focusing on correlations between different currency pairs and market risk factors.

---
