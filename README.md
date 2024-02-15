# spam-sms-detection
Spam SMS Detection
This project is focused on detecting spam SMS messages using machine learning models. The dataset consists of labeled SMS messages, with the labels 'spam' and 'ham'. The following steps are taken in this project:

1.Data Preprocessing:
Lowercasing
Punctuation removal
Stopword removal
Word length filtering

2.Exploratory Data Analysis:
  Label distribution
  Text length distribution

3.Model Building and Evaluation:
  Naive Bayes
  K-Nearest Neighbors
  Logistic Regression
  Random Forest

4.The evaluation metrics used in this project are:
  Precision
  Recall
  F1 Score

5.The trained models are compared using the following metrics:
  Confusion Matrix
  Receiver Operating Characteristic (ROC) Curve and Area Under the Curve (AUC)
  Requirements
  Python 3.x
  Required packages: re, warnings, pandas, matplotlib, seaborn, numpy, sklearn, string, LabelEncoder, LogisticRegression, RandomForestClassifier, ExtraTreesClassifier, classification_report, confusion_matrix, precision_recall_fscore_support, accuracy_score, TfidfVectorizer, ENGLISH_STOP_WORDS, train_test_split, Pipeline
