# NLP-Projects

"Sentiment Analysis of Trendy Subjects on Twitter in US"

Sentiment Analysis involves Natural Language Processing because it deals with human-written text and a classification task which will classify people’s opinion expressed about different subjects chosen to be evaluated. Sentiment Analysis can help us decipher the mood and emotions of general public and gather insightful information regarding the context. Sentiment Analysis is a process of analyzing data and classifying it based on the need of the research.

Importing the Data

In the project, I will use Twitter data by connecting the Twitter API. I will retrieve 5000 tweets about the subject I will focus with the extended mode. All the tweets will be in English as language. This project will use Streaming API that allows to collect tweets on a real-time basis based on search terms, user ids or locations.

Twitter API stands for Application Programming Interface that makes interaction with computer programs and web services easy. This project will download tweets related to 5 keywords: "Covid", "stimulus", "Trump", "Biden", "vaccine". I intentionaly select these subjects because, these topics are the most popular keywords for last months and still they have more attractions than other issues in the thoughts of public.

In order to access Twitter Streaming API, we need to get 4 pieces of information from Twitter: API key, API secret, Access token and Access token secret.

I will be using a Python library called "Tweepy" to connect to Twitter API and download the data.

Preprocessing

Data Wrangling

Modeling (Sentiment Analysis)

Step 1) Removal of Stop Words (Cleaning)

Step 2) Stemming

Step 3) Lemmatization

Sentiment of Lemmatized Data

Dropping Irrelevant Columns

Let's divide our dataset into feature and label sets.

Representing Text in Numeric Form

Dividing Data into Training and Test Sets

Training the Model

Making Predictions and Evaluating the Model

|     CLASSIFICATION     | ACCURACY |


| LogisticRegression     | 0.729    |


| RandomForest           | 0.731    |


| K-NearestNeighbors     | 0.422    |


| MultinominalNaiveBayes | 0.667    |


| SupportVector          | 0.737    |


Findings

Conclusion


