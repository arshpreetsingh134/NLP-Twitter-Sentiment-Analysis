# NLP: Twitter Sentiment Analysis using Multinomial Naïve-Bayes Classifier

I have trained a **Naive Bayes classifier** to predict sentiment from thousands of Twitter tweets as 'happy' or 'sad'. This project could practically be used by any company with a social media presence to automatically predict customer's sentiment (i.e., whether their customers are happy or not). The process could be done automatically without having humans manually review thousands of tweets and customer reviews.

Dataset used is the famous **Sentiment140** which is freely available to download from [this website.](https://nyc3.digitaloceanspaces.com/ml-files-distro/v1/sentiment-analysis-is-bad/data/training.1600000.processed.noemoticon.csv.zip)

Library used for **NLP Multinomial Naïve-Bayes Classifier**: [scikit-learn v0.23](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html?highlight=multinomial%20naive)

### The NLP Pipeline I have created follows the following steps :-
1. **Step 0:** Importing Libraries & Dataset
2. **Step 1:** Performing Exploratory Data Analysis & Data Visualization
3. **Step 2:** Performing Data Cleaning: Removing usernames, stopwords, punctuation
4. **Step 3:** Performing Count Vectorization (Tokenization) of individual tweets
5. **Step 4:** Splitting the data into Train and Test Sets
6. **Step 5:** Training Naïve-Bayes Classifier
7. **Step 6:** Assessing trained model's performance

The notebook was created in [Colab.](https://colab.research.google.com/)
