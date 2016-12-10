## Stock Market Prediction Using Deep Learning Techniques
* I have collected daily tweets about 7 stocks (e.g. `$GOOG`) since 2016-08-01: https://zhedongzheng.github.io
* Features
  * numeric data: an array of recent 30 past prices
  * visual data: an image of the plot of the trend of recent 30 past prices
  * Twitter data: predictors from daily tweets searching for a company's stock (e.g. `$AAPL`)
    * volume predictors
      * posting volume: total number of tweets posted per day about a stock
      * endorsing volume: total number of tweets clicked "liked" by users per day about a stock
    * sentiment predictors: (the sentiment score is graded by "Vader" algorithm)
      * positive scores: the average positive sentiment score of all the tweets about a stock per day
      * negative scores: the average negative sentiment score of all the tweets about a stock per day
