# Brazil-Elections-Twitter-Sentiment 

# Twitter Sentiment Analysis using sklearn 

# Description:
- Program that collects data from Twitter API and classify it into sentiment categories based on positive and negative Amazon reviews
# Model Type 
### Ensemble Model - Decision Tree Classifier, Logistic Regression, Random Forest, KNN
# 20/10/2022

# Version - V1.3

# Goals:
- To build a ML model that is able to predict the sentiment from twitter hashtags, posts and profiles

# Key Insights and Notes
- Since this is an Election sentiment prediction, values can be affect everyday by new information
- We are translating the tweets from Portuguese to English, this can affect the model's accuracy
- The ensemble model was able to improve the accuracy by 5% comparing it to the previous model 
- An ensemble model is not necessarily better than any other model, you should be able to read the results and pick the best model
- Repeated tweets might be affecting the performance, you can choose to remove it 
- Hyperparameters Optimization was not done yet 
 
# Fixes
- Translation to Portuguese Added


# Version Updates:
- Ensemble Model added
- API connections
- Classify by hashtags
- Sklearn implemented 
- Amazon reviews database
- Save the model 
- Statistics
- Added sentiment database
- Comparisons added 
- Language translation added
- Remove duplicates 


# Future Implementations: 
- Plot Analytical charts 
- Add start_time and end_time parameters
- Create a list with market symbol and their sentiment
- Add time period analysis(select period option)
- Create sentiment dictionaries from web studies 
- Hyperparameters Optimization 
- Train and test with the Brazilian dataset
- Analyze use of prepositions 
- Create a Market Checker were it indicates the sentiment on the period and Prints the Chart Bullish or Bearish 

# Author - Luiz Gabriel Bongiolo

# Credits & References 
- https://developer.twitter.com/en/docs/tutorials/five-ways-to-convert-a-json-object-to-csv
- https://developer.twitter.com/en/docs/twitter-api/v1/tweets/search/api-reference/get-search-tweets
- Computer Science youtube channel - https://www.youtube.com/watch?v=ujId4ipkBio&t=280s
- Keith Galli - https://www.youtube.com/watch?v=M9Itm95JzL0
- http://jmcauley.ucsd.edu/data/amazon/
- Daniel Ellis Research - https://towardsdatascience.com/language-translation-using-python-bd8020772ccc
- Leandro Guerra - https://www.outspokenmarket.com/ - Instagram @leandrowar
