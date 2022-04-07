# Stock Sentiment Analysis using News Headlines and Prediction
We used news headlines to create a model that actually analyzes stock prices.
There are various  news articles and  the stock price fluctuates accordingly.
We used NLP sentiment analysis to analyze news headlines and predict whether stocks will rise or fall.

## Dataset Description
* The dataset in consideration is a combination of the world news and stock price shifts available on kaggle.
* There are 25 columns of top news headlines for each day in data frame.
* Data ranges from 2008 to 2016 and the data from 2000 to 2008 was scraped from Yahoo finance.
* Labels are based on the Dow Jones Industrial average stock index.
  * Class 1 - The stock price increased.
  * Class 2 - The stock price stayed the same or decreased.

## Concepts of NLP Used
* Removing Punctuation and Special Character.

* Renaming columns, Converting the entire text to lower case and Joining all the columns.

* Creating corpus of train and test dataset which includes
  * Tokenizing the news-title by words
  * Removing the stopwords
  * Stemming the words and Joining the stemmed words
  * Building a corpus of news-title

* Creating Bag of Words Model

## Model Building

We have used two Machine Learning model with the use of sklearn Library.
<br />
### Logistic Regression.<br/>
Scores <br/>
![LR Score](https://user-images.githubusercontent.com/65327192/162155813-94f18cb5-882f-4536-a467-8205422d8a36.png)
<br />
<br/> Confusion Matrix <br/>
![LR Confusion Matrix](https://user-images.githubusercontent.com/65327192/162155841-cafc38ed-2641-4bb5-b842-f0c692b0843e.png)
<br />

### Multinomial Naive Bayes.<br/>
Scores <br/>
![image](https://user-images.githubusercontent.com/65327192/162157459-59ddec97-5b22-4675-a987-dba9a8f96f95.png)
<br />
<br/> Confusion Matrix <br/>
![image](https://user-images.githubusercontent.com/65327192/162157502-c8c5d8b9-d12c-46e1-ac17-6c0fbae0a777.png)




