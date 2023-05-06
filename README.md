# nidhimani-Twitter_Sentiment_Analysis_Using_Real_Time_Data
By using snscrape scrapped tweets from BarackObama twitter account and created a dataframe with the tweets.
Cleaned the tweets from punctuation marks, multiple white spaces, numbers, alpha-numeric terms, hashtags, mentions etc
Emojis are replaced with text by using emoji package. Also, emoticons are replaced with text.
TreebankWordTokenizer and WordNetLemmatizer to tokenize and then lemmatize the words.
used Vader_lexicon to assign polarity scores for the tweets by creating a separate column called polarity.
created an other column "sentiment' and assigned 2 for the tweets which are positive in nature, 1 for neutral tweets and finally 0 for negative tweets.
CountVectorizer is used to count number of times a word is repeated and then splitted the data into train and test.
used random forest algorithm to create a machine learning model and got an accuracy 0.90
