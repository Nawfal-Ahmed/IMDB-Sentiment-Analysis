# IMDB-Sentiment-Analysis
IMDB movie review sentiment analysis using python libraries to predict the nature of review

Libraries used:

Data handling: pandas, numpy

Visualization: matplotlib, seaborn, wordcloud

NLP preprocessing: nltk (tokenize, stopwords, PorterStemmer)

Feature extraction: TfidfVectorizer

Models: LogisticRegression, LinearSVC

Evaluation: accuracy_score, classification_report, confusion_matrix

Utilities: GridSearchCV, Counter, re, warnings

Dataset: IMDB movie review with sentiment 

Workflow:

Load dataset with Pandas

Clean & preprocess text (tokenization, stopword removal, stemming)

Generate word clouds & data distribution plots

Convert text → vectors using TF-IDF

Train classification models: Logistic Regression, Linear SVM , Tuned Linear SVM

Evaluate using accuracy, classification reports, confusion matrix

Some parameter tuning with GridSearchCV for better accuracy
