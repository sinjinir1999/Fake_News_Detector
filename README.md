# FAKE NEWS DETECTOR
Analysed a dataset to predict whether a news is "Fake" or "Real".
1. Used PorterStemmer for Stemming and applied CountVectorizer for Bag of Words representation. Trained using Multinomial Naive Bayes Classifier model with a Test Accuracy score of 90.14%.
2. Used WordNetLemmatizer for Lemmatization and applied TfidfVectorizer for Term Frequency Inverse Document Frequency (TFIDF) representation. Trained using Multinomial Naive Bayes Classifier model with a Test Accuracy score of 88.36%.
3. Used PorterStemmer for Stemming and applied WordEmbedding for featurewise representation. Trained using Long Short Term Memory (LSTM) model with a Test Accuracy score of 91.47%.
4. Used PorterStemmer for Stemming and applied WordEmbedding for featurewise representation. Trained using Bidirectional Recurrent Neural Network model with a Test Accuracy score of 90.98%.
# DATA
The data is from Kaggle, can be downloaded from:
https://www.kaggle.com/c/fake-news/data
