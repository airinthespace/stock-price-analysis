# stock-price-analysis

Financial markets are inherently dynamic and unpredictable, attracting keen interest from investors and analysts alike. In the pursuit of understanding and forecasting market trends, machine learning models have emerged as pivotal tools. This project specifically focuses on the Random Forest (RF) algorithm, renowned for its versatility and robustness, making it an excellent choice for predicting stock prices.

The primary objective of this research is to leverage the capabilities of the Random Forest model to analyze and predict stock market dynamics. We utilize a comprehensive dataset comprising the NASDAQ 100, S&P 500, QQQ, and SPY, sourced from Kaggle. This dataset is rich in historical market data, encompassing stock prices, volumes, and various financial indicators.

Datasets Overview

Each dataset included in this project offers unique insights into financial markets:

NASDAQ 100: This dataset primarily represents technology-based stocks, making it valuable for analyzing trends in the technology sector.
S&P 500: This dataset provides a generalized view of the stock market, covering a wide range of industries and reflecting the overall performance of the U.S. economy.
QQQ: This dataset represents an ETF that tracks the NASDAQ 100 index. It is crucial for gauging the performance of influential tech giants.
SPY: This dataset focuses on an ETF that tracks the S&P 500 index, providing a broader perspective on the large-cap U.S. stock market.
The inclusion of ETFs like QQQ and SPY allows for a more comprehensive understanding of market dynamics and investor behavior, as these instruments are widely used for both speculative trading and long-term investment strategies.

Conclusion

Our project demonstrates that the Random Forest technique performs well in predicting stock market trends, particularly for next-day closing prices. Each of the four prediction models achieves an impressive R-squared score above 0.94. Key factors influencing the next-day closing price prediction include the average closing price of the past 20 days and the current closing price.

Furthermore, we reaffirm that R-squared is a more reliable indicator for measuring model performance, as metrics like MAE, MSE, and RMSE can be significantly influenced by the original data, making them unsuitable for comparing the predictive performance across different datasets.

We also found that the performance of Random Forest models can depend on the maximum depth of each tree and the total number of trees in the forest. While increasing the number of trees may enhance performance, it also incurs higher computational costs (Oshiro et al., 2012). Conversely, limiting tree depth can yield excellent results (Zhou & Mentch, 2022). Therefore, the optimal maximum depth and tree count should be determined based on the specific dataset and research question, and it is advisable to retest parameters when encountering new situations.
