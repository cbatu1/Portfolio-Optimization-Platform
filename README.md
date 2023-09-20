# Portfolio-Optimization-Platform

This platform implements a few commonly used assets allocation
strategies, including: 

1. Equally-weighted Portfolio (EW)
2. Inverse Volatility Portfolio (InVol)
3. Risk Contribution Parity Portfolio (RCP)
4. Minimum Variance Portfolio (MV)
5. Maximum Diversification Ratio Portfolio (MD)
7. Minimum Conditional Value-at-Risk Portfolio (Min CVaR)

Based on their differences and similarities I divide them into two types,
a diversify-oriented portfolio and a risk-oriented portfolio. It was determined that by adding a regularization term, setting weight upper
bound, or adjusting other optional parameters, we can diversify the investment and lower
the risk at the same time, in this way, we can take a step further in portfolio optimization.

These strategies are applied to the investable set consisting of 28 Shenwan first-level
industry indices, the weight distribution of different strategies corresponds to the type it
belongs to. 

In addition, several indicators are included to measure the performance of these
portfolios, in general, MV performs relatively better in our problem. However, faced with
different investable sets the performance of the same strategy differs greatly.
