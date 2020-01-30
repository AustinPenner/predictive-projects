# Projects

## Predict Restaurant Rating From Review

### Approach: 
Yelp's restaurant dataset dataset has reviews and ratings for many restaurants. I will use NLP and some form of regression to predict the 5 star rating that a user provides based on their text rating only. Models: I'll start with Linear Regression as a benchmark before trying Naive Bayes, Decision Trees, and Random Forest. (See [this](https://towardsdatascience.com/review-rating-prediction-a-combined-approach-538c617c495c) article for a related project and [this](https://arxiv.org/ftp/arxiv/papers/1904/1904.04096.pdf) article for a Neural Network-based approach.)

If time permits, I'll also use some unsupervised algorithm to cluster Yelp users.

### Interaction: 
Present findings in Jupyter Notebook/Github/Slides as the model won't be interactive. 

### Data Sources: 
[Yelp reviews dataset](https://www.yelp.com/dataset/download) of restaurants in 10 cities (3.6 gigs). This contains data about the business, user reviews, and user data.

## Predicting Winning Team in Rocket League

### Approach: 
Rocket League is a video game where cars play soccer. I will use the plethora of data provided at [ballchasing.com](https://ballchasing.com/) to do EDA and make a model to predict the winning team. There is an astounding amount of data available in each replay, which should make predicting the winner relatively easy. Assuming this is the case, I'd like to see what features are most important and try and train a good model on minimal features. I may start with a random forest and try a few other classifiers from there.

### Interaction: 
Present findings in Jupyter Notebook/Github/Slides as the model won't be interactive.

### Data Sources: 
I will utilize the API from [ballchasing.com](https://ballchasing.com/), a repository of community-uploaded replays. Each replay has a good deal of statistics from the match.


## Effect of President Trump's Twitter Feed on the Stock Market

### Approach: 
Use time series analysis and sentiment analysis to compare Trump's twitter feed against the stock market. The goal is to find some relationship where Trump's twitter feed predicts stock market prices based on the NLP analysis of his tweet (positive, negative, angry, etc). I would look at overall stock market, S&P 500, and specific industries (tech, energy, etc). This project would take the longest due to the complex nature of the subject and the types of analysis required. 

Similar studies have been done [here](https://www.nottingham.ac.uk/economics/documents/research-first/krishan-rayarel.pdf) and [here](https://www.fxcm.com/uk/insights/president-trumps-twitter-impact-forex-markets-stocks/).

### Interaction: 
Present findings in Jupyter Notebook/Github/Slides as the model won't be interactive.

### Data Sources: 
1. All Donald Trump tweets since his inauguration. 
2. Stock market data since Trump's inauguration, including company industry and whether or not company belongs to S&P 500.
