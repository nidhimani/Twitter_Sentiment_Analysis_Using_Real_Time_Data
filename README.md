# Twitter_Sentiment_Analysis
![TwitterGIF](https://user-images.githubusercontent.com/117325135/236608698-9d609bbf-32df-424e-9160-488ce21f315f.gif)

## Snscrape
By using snscrape tweets are scraped from BarackObama twitter account between the dates 2023-01-01 and 2023 - 04- 20 and created a dataframe with the tweets.

## Cleaning test🧹🧹🧹
Cleaned the tweets from punctuation marks(.,!?:;-=), multiple white spaces, numbers, alpha-numeric terms, hashtags, mentions, html tags  etc by using regex functions.

## Treating emojis and emoticons 😎
Emojis are replaced with text by using emoji package. A dictionary is created with mostly used emoticons like ":), :(" etc and replace with text.

## Tokenization and Lemmatization
TreebankWordTokenizer is used to convert the tweets  into understandable bits of data that a program can work with. WordNetLemmatizer is used to break a word down to its root meaning.

## Polarity scores
1.used Vader_lexicon to assign polarity scores for the tweets by creating a separate column called polarity.

2.created an other column "sentiment' and assigned 2 for the tweets which are positive😄 in nature, 1 for neutral tweets🙂 and finally 0 for negative tweets😫.

3.CountVectorizer is used to count number of times a word is repeated and then splitted the data into train and test.

## Machine learning model
Finally used random forest🌳🌳🌳🌳🌳 algorithm to create a machine learning model and got an accuracy 0.90 in predicting the sentiment.
