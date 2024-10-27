# TASK1NEW
Load Dataset Data Import: Load OHLC data for backtesting. Initialize Columns: Add placeholders for signals and returns for each strategy.
Strategy Development We design three distinct strategies:
Trend-Following: Uses short and long moving averages to identify buy (crossover) and sell (cross-under) signals. Mean-Reversion: Looks for price deviations from a rolling mean to trigger buy/sell signals. Momentum: Buys when recent returns are positive and sells when negative. Each strategy has clear entry/exit signals, and we calculate returns based on these signals.

Backtesting Transaction Costs: Deduct transaction costs per trade to simulate realistic conditions. Cumulative Returns: Calculate cumulative returns for each strategy to track performance over time.
Performance Metrics For each strategy, calculate:
Sharpe & Sortino Ratios: Measure risk-adjusted performance. Max Drawdown & Annualized Return: Indicate downside risk and annual performance. Cumulative Return: Shows overall return across the backtest period. 5. Portfolio Analysis Equal-Weighted Portfolio: Combine all three strategies to analyze performance with equal weight. Metrics & Correlation: Calculate portfolio metrics and check correlations to assess diversification benefits.
6. Visualizations Cumulative Returns: Plot growth over time for each strategy and the portfolio. Drawdowns & Correlation Matrix: Show risk and inter-strategy correlations for better risk assessment. 
7. Trade Log Record individual trades for each strategy, including entry/exit points and profit/loss.
