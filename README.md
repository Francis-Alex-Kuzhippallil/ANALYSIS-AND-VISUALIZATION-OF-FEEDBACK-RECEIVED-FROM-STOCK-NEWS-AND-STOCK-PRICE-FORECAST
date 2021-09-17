# ANALYSIS-AND-VISUALIZATION-OF-FEEDBACK-RECEIVED-FROM-STOCK-NEWS-AND-STOCK-PRICE-FORECAST
In Big Data driven world Stock Price Prediction has been favorite topic for both analyst and researchers. Several factors contribute towards the prediction namely physical factors, political and economic factors. Sentiment analysis of stock data based on historical data or textual information has been less precise. Existing studies in sentiment analysis have depicted high correlation between news articles based on organization and their respective stock prices. Hence it’s a daunting tasks to decide the trend of stock price based on news. Hence machine learning based prediction has become pivotal. This project focuses on building a script that analyzes the feedback based on news articles of stocks on Finviz and forecasting the stock price from various sources using ML techniques. Followed by visualizing the results obtained with various tools.

Stock market commonly known as fortune-maker has been the mantra to successfully predict the stock
prices. With the introduction of artificial intelligence and increased computational capabilities,
programmed methods of prediction have proved to be more efficient in predicting stock prices. It is
extremely difficult for investors to decide trend of stock prices based on the amount of news obtained. The
viable options to do stock market predictions is Technical analysis and Fundamental Analysis. Technical
analysis makes future predictions based on past prices and volume of stocks. Fundamental analysis involves
analyzing financial data for gaining insights. This research opts both analysis techniques. Fundamental
analysis is used to discover sentiments of news articles from Finviz stock screener for several organizations.
Further news are classified as positive, negative or neutral or combination of two or more sentiments. This
research uses technical analysis to predict stock prices and further forecast stock price for next few days
using machine learning techniques namely linear regression, KNN, Decision Tree Regressor, FBProphet,
Lasso, Elastic Net and LSTM. Visualization of forecast using each technique is done and comparison of
stock prediction accuracy of various algorithms is analyzed as well. Yahoo finance is source used for stock
price prediction and based on the data provided from yahoo finance, forecast of stock price is being done
as well. The data collected from Yahoo finance is already pre-processed which includes the most common
terms like ‘Date, Open, High, Low, Close, Adj Close, Volume, these features are best to fit into models and
make them to train on these features which turns out to be very beneficial. Using the learning curve of 1
year stock market data the model will be able to predict the coming 30 days for a particular scrip. The main 
solution is that making this one model to learn from the data of any given stock, is in itself one complete
new feat achieved. The stocks can be from any index, they can be from NSE, BSE, NYSE, S&P 500,
NASDAQ, etc. But the learning curve will be predicted through one single model.
