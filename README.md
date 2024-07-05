# SP500_Correlation_CAPM_Crises
Abstract: 

This project explores the behavior of stock correlation and the Capital Asset Pricing Method(CAPM) within the S&P500 during the crisis period from 1980 to 2023. By looking at the daily returns of S&P500 stocks and taking daily index closing into account, we aim to validate the famous financial market saying, "Correlations go to one." We calculate return statistics for bull and bear markets using Python, especially the Pandas, Numpy, and yfinance packages. The study uses the correlation and CAPM beta formula to measure relationships and beta values during different market periods. This investigation assesses the effect of crises on the forecasting power of CAPM betas and emphasizes how closely financial assets move together during market stress. We also discuss our technique's shortcomings. The findings are presented clearly and concisely using bullet points to provide insightful conclusions on the behavior of stock correlations and betas during notable market downturns and recoveries. This helps to enhance our understanding of market dynamics during difficult financial times.

Objectives:

Identify the crisis period for the entire period of the S&P 500
Analyze the behavior of S&P 500 stock correlations throughout times of financial crises.
Examine the S&P 500 stock CAPM beta patterns across similar periods to understand market dynamics under pressure.

Data & Methodology:

Collection Of Data: We combined the closing prices of the S&P 500 index with data on the daily returns of S&P 500 companies from 1980 to 2023. We used a 20% drop from peak to low to identify crises.

Analytical Procedure: We used Python models like Pandas and Numpy to calculate and analyze the CAPM and correlation. The crisis period was identified separately to identify the metrics.


Results and Interpretation:
 
Quarterly Average Correlation from 1980 to 2024
The graph presents a quarterly average correlation trend over approximately 44 years, from 1980 to 2024.
The sharp rises and falls in correlation demonstrate the index's sensitivity to economic events and investor sentiment.
The 1987 Black Monday shows a sharp peak, suggesting a near-one correlation as stocks fell uniformly.
The early 2000s Dot-com Bubble burst resulted in a significant rise in correlation, aligning with a broad market sell-off.
2008, the Financial Crisis spike illustrates how systemic risks can drive stock correlations toward unity.
The peak of COVID-19 in 2020 supports the idea of "correlations going to one" as global economic shutdowns affected all sectors.
Correlation levels vary significantly throughout the period, with several notable peaks above 0.6.
The general trend from 2010 onwards shows more volatility in correlation, with frequent and sharp rises and falls.
The last point on the graph indicates a falling correlation from a peak, suggesting the end of a crisis period or a return to a more stable market phase.
During extreme market events, asset prices can move together more closely, thus causing correlations to approach one.
The sharp rises and falls in correlation demonstrate the index's sensitivity to economic events and investor sentiment.
 

Discussion: 
The behavior of correlations and betas during the crisis period:
Correlations among stocks tend to increase during crisis periods due to systemic risk, flight to quality, liquidity crunches, and negative market sentiment.
Increased correlations during crises reflect the broader impact of market turmoil and risk aversion among investors.
Betas of individual stocks tend to increase during crises due to heightened market volatility, uncertainty, and liquidity effects.
Higher beta values during crises indicate greater sensitivity of stocks to market movements and heightened risk perception among investors.
Understanding the behavior of correlations and betas during crises is essential for risk management, portfolio diversification, and investment decision-making.
Beta values, which measure a stock's sensitivity to market movements, tend to increase as stocks react more strongly to overall market volatility during crises. This results in betas converging towards higher values, indicating that stocks follow the market's turbulent swings more closely.
As correlations increase, the benefits of diversification decrease since assets are moving more similarly. High beta values during these times reflect that stocks are heavily influenced by the broader market, reducing the effectiveness of strategies to spread risk.

Limitations:
Identifying Crises, applying correlation during these periods, and applying capital asset
pricing methods can have a few limitations.

Crisis Identification Limitations:
Identifying the start and end date of the crisis may be difficult; Various experts may have multiple interpretations depending on the economic indicators.
The analysis could not be very accurate when there is a lack of historical data, particularly for emerging markets or during high volatility.

Correlation Limitations:
Correlation measures the linear relationships between variables. However, the dynamics between market movements and asset values may be partially captured by correlation since many interactions in finance, particularly during times of crisis, may not follow a linear pattern.
There is no proof that a high correlation indicates causality. Instead, an invisible element may impact two assets moving together.
The correlation between assets can shift dramatically during times of crisis compared to regular times. This tendency, also known as "correlation breakdown," implies that diversification tactics may not work when required.

CAPM Limitations: 
The Capital Asset Pricing Model (CAPM) uses beta to calculate how sensitive an asset's returns are to market returns. However, beta’s tendency to fluctuate over time, especially during financial instability, diminishes the model's predictive ability.
The CAPM's market efficiency assumption is that all investors have access to all relevant information and that markets are efficient. This assumption is frequently broken during crises when information asymmetry and market state are essential factors.
The CAPM model only considers market risk. It ignores other forms of risk, such as credit, operational, and liquidity risks, which may all intensify during crises.
Finding an asset that is genuinely free of risk can be difficult, particularly in times of financial crisis when even the safest government securities may be subject to some level of risk.

Conclusion:
The project shows the S&P500 stock correlation, CAPM, and Beta’s behavior during the crisis period from 1980 to 2023. 
It demonstrates how closely stocks move in conjunction and how they respond to market conditions in difficult times.
As the 12-month moving average trend shows, stock correlations in the S&P 500 jump dramatically during financial crises, frequently nearing unity.
CAPM beta's increased volatility during these crisis times indicated increased market sensitivity.
We observed that when the market is unstable, CAPM betas, or the risk level of equities compared to the market, becomes more unpredictable. 
Our project has shown that during a financial crisis, CAPM betas—indicators of stock risk behave unpredictably. 
Our data convinces us that correlations between S&P 500 equities rise towards one during financial crises, indicating a collective market movement driven by broad systemic causes instead of individual business performance. Similarly, CAPM betas behave differently during these times, showing more market responsiveness and volatility, which denotes increased systematic risk. 

