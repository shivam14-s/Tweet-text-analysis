# Tweet-text-analysis
Information Retrieval Course Project. Sentiment Analysis on tweet text data

The .ipynb file contains two tries. In the first, I tried to extract actual tweet text data from Tweet IDs using Twitter API for python, but it needed a paid subscription of the API. So, I changed my approach and used a kaggle Dataset which had the tweet text already.

## Steps:
1. ### Data Cleaning and Analysis:
   - Removing Null values
   - Dropping unwanted fields
   - Plotting the data to visualize effectively
2. ### Data Preprocessing
   - Removing hashtags, mentions, URLs, formatting symbols, escape characters, etc.
   - Removing Stop words
   - Applying Stemming and Lemmatization to create two seperate cleaned dataframes for testing
3. ### Applied many classification models for sentiment anaylsis.
   - Models include:- **LSTM** ,**Neural Network**, **Logistic Regression**, **Random Forrest Classifier** and **Decision Tree Classifier**.
