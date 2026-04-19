# Prompting Large Language Models for Portfolio Optimization (May 2026)

🎯 Goal

This project studies how Large Language Models construct portfolios under different levels of prompt guidance.

🛠 Methodology

We design a structured experiment with four prompt levels, ranging from no guidance at all to fully specified mean-variance optimization. We then evaluate how increasing prompt sophistication affects portfolio construction.

Using the constituents of the Dow Jones Industrial Average (DJIA) and historical return data (`01-01-2018` to `30-06-2024`), we analyze the following elements:

- feasibility of LLM outputs (constraint satisfaction and formatting)
- similarity to the benchmark portfolio (mean-variance)
- performance metrics (expected return, variance, Sharpe ratio)
- diversification (Herfindahl index)
- robustness across repeated API calls
- semantic consistency of model-generated comments
