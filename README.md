# Artificial-Neural-Network-Project-1

This project, undertaken over two weeks as part of the Artificial Neural Networks course at the NTNU, explores the application of Long Short-Term Memory (LSTM) networks in predicting the near-term stock price movements of 0050.TW, a Taiwanese index ETF.

The investigation began with an LSTM model trained on historical stock prices. The analysis revealed a significant challenge: the inherent non-stationarity of stock prices resulted in considerable predictive inaccuracies, particularly when stock prices escalated beyond the historical range observed in the training set. To address this limitation, the study expanded its scope by incorporating additional, predictive features extracted from a diverse array of data sources. These included options market data, which provides insights into market expectations of future price volatility; key macroeconomic indicators such as the 10-year interest rates and the VIX index, reflecting broader economic sentiment; and transaction data from the leading constituents of the 0050.TW index, offering a granular view of market dynamics. The augmented model demonstrated markedly improved performance, particularly when employing a Lasso regression loss function, known for its ability to enhance model generalization by penalizing large coefficients. Despite these advances, the study acknowledged a critical benchmark: the predictive capability of the model did not surpass that expected under the martingale hypothesis, which posits that future price movements are fundamentally unpredictable based on past prices alone. 

This research underscores the burgeoning interest in leveraging advanced machine learning and deep learning methodologies within asset pricing. The quintessence of these efforts lies in employing cross-sectional data to model conditional expected returns, providing a sophisticated analytical lens through which financial markets can be deciphered. Looking ahead, the project proposes an intriguing avenue for future research: harnessing Taiwan's cross-sectional stock market data to further refine and validate the predictive prowess of machine learning models in financial analysis, charting new frontiers in the confluence of artificial intelligence and financial market forecasting.












