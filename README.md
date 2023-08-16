# stock-trading
# Simple Moving Average Crossover Strategy:
In the moving average crosser file, I implemented the well-known trading strategy, which calls Simple Moving Average Crossover, 
using the Python libraries Numpy and Pandas. 
The moving average crossover is making predictions through the history data. In the calculation, we have two 
different moving averages, the smaller one tells us the recent trend of the stock's price, and the larger one tells us the 
long trend of the stock's price. Once the smaller moving average price is higher than the larger one, we can ask the
machine to buy stock for us.

# predict model for stock:
in this file, I collect data from the internet, which includes the time attribute. The data is collected day by day.
In data processing, we create two new attributes. The first is return, which is the log of the value of today/ the value of 
tomorrow. And we have another attribute direction, which means the positive or negative of the data. Then, we apply the linear 
regression model to make predictions. We can see these the predictions based on those two attributes are different. 
So, we used backtesting to check which prediction is better. Here, from the graph, we can conclude that the first preidction is better.
