# Assignmnet3
Algorithm Trading Assignment3

Bitcoin being extremely volatile makes it harder to predict. I aim to use the Efficient Market Hypothesis (EMH) which states that stock market prices are largely driven by new information and follow a random walk pattern. By incorporating social media as an additional channel of information we can better emulate the speculative patterns of the traders. For example the fall in prices of bitcoin with the Chinese regulator’s decision to bad all virtual currency and its subsequent rise when the government decided to soften it stands. 

The Assigmnet attempts to predict the future value of Bitcoins by identifying the correlation between social media sentiment and market sentiment. I achieve this by collecting user feeds from social media such as twitter, facebook and linkedin. Once I have our corpus I map their associated sentiments using IBM Watson’s Natural Language Understanding API. While mapping sentiments to  corpus I attempt to capture granular level categories namely joy, anger, happiness, etc. I use these as feature vectors to the ML/DL algorithms. Then I compare the results of the different algorithms and choose the one with the best accuracy score.


Data Sources:
1. Twitter Api to get the tweets about BitCoins/Cryptocurrencies.
2. LinkedIn Api to get the corpus on blogs.
3. Web Scraping to get data from News articles.
