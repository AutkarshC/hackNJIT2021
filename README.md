# hackNJIT2021
NJIT hackathon 2021 (Bank of America challenge)

## Inspiration : 
To be able to build a machine learning model that could predict the sentiment of twitter data

## What it does :
 We get 5000 random tweets about USbanks using twitter API and analyze the sentiment whether it's a positive, negative or neutral tweets for the banks. 

## How we built it :
 After get the tweets from Twitter API, we preprocess the data by removing  punctuations from the tweets, converting tweet strings to lowercase, tokenizing the tweets, removing stopwords and Lemmatizing the tweets using POS tags. 
Getting the polarity of the tweets by vader sentiment analysis to get the target variable(prediction). Polarity divides the tweets into positive, negative and neutral tweets. 
Then we convert strings to vectors and then applying TF-IDF to vectors to check how relevant are the words. 
By applying naive bayes multinomial classifier we got the accuracy of 80.11 percent, by random forest classifier we got the accuracy of 84.24 percent. 

## Challenges we ran into : 
We did not have a label dataset on which we could train and then test our model so we create the target by using vader sentiment. However this is not the best approach. We could have analyzed more could have used clustering algorithms for unsupervised data. 

## Accomplishments that we're proud of :
This is the very basic model. We think to start with NLP we are good to go but in real time project we need to dive in more advance methods such as RNN or LSTM.

## What we learned : 
This was our first hackathon event so it was overwhelming experience, knowing people, exchanging ideas, learning from different teams and at last applying and testing our knowledge what we know and how much more we could do.

## What's next for Sentiment Analysis for Bank of America :
We think since we have got a start from here on we would like to learn advance NLP technique and build a RNN model that could be used in real time
