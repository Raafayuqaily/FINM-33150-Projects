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

