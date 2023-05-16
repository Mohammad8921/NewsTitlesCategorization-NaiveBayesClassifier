# News Titles Categorization using Naive Bayes Classifier
* In this project I implemented a Naive Bayes text classifier from scratch to categorize the titles of news. The categories are:
  * International
  * Sport
  * Political
  * Cultural-artistic
  * Social
  * Scientific-medical
  * Economic
  * Social media
  * Web browsing
  * Video & audio
* All characters execpt `.`, `?`, `آ-ی` have been removed; Numbers have been replaced by `N`. Zeros have been handles by Laplacian smoothing.
* `DataPreprocessor` class has been designed for data preprocessing and the aim of `NaiveBayesClassifier` is training and predicting the Naive Bayes model to do the classification task.  
