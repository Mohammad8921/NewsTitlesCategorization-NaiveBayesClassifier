# News Titles Categorization using Naive Bayes Classifier
* In this project, I implemented a Naive Bayes text classifier from scratch to categorize the titles of news. The categories are:
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
* All characters except `آ-ی` and `\s` have been removed; Numbers have been replaced by `N`. Zeros have been handled by Laplacian smoothing.
* The `DataPreprocessor` and `NaiveBayesClassifier` classes have been designed for preprocessing the samples and training a Naive Bayes classifier respectively.  
