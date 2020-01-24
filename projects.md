# Projects

## Analyze what effect President Trump's Twitter feed has on the stock market

Approach: Use time series analysis and sentiment analysis to compare Trump's twitter feed against the stock market. The goal is to find some relationship where Trump's twitter feed predicts stock market prices based on the NLP analysis of his tweet (positive, negative, angry, etc). I would look at overall stock market, S&P 500, and specific industries (tech, energy, etc).

Interaction: Present findings in Jupyter Notebook/Github/Slides as the model won't be interactive.

Data Sources: 1) All Donald Trump tweets since his inauguration. 2) Stock market data since Trump's inauguration, including company industry and whether or not company belongs to S&P 500.


## Analyze how the general populace's tweets about a company affect their stock price

Approach: Gather a large amount of twitter user data where company X was mentioned. Use time series analysis and sentiment analysis to see if aggregated user sentiment is predictive of stock prices for some company. 

Interaction: Create interactive web app that visualizes user mentions of company and the relationship between them. This could be filtered on company and sentiment.

Data Sources: 1) 10,000+ tweets per company where this company is mentioned. 2) Recent stock market data including company industry and whether or not company belongs to S&P 500.

## Song lyric analysis

Approach: Pull top listened to albums either from Billboard or Spotify, grab song lyrics for these albums, then predict critic ratings based on song lyrics.

Interaction: Create interactive web app that visualizes data, allowing user to look at albums by year.

Data Sources: 1) Either a) Billboard top 100 songs for last 40 years or b) top Spotify songs for last X years. 2) Web scrape song lyrics from google or a song lyrics website. 3) Web scrape critic album ratings

## Capstone project prediction

Approach: Look at all past Galvanize capstones on Youtube, transcribe the audio, and grab their github pages. Then feed this data into GPT2 and simulate Galvanize capstone projects from this data. Just kidding.
