# Fake News Detection using Text Classification and Ensemble Learning

This project uses simple NLP techniques and ensemble machine learning to classify news articles as fake or real.

The text data was cleaned using regex preprocessing, converted into TF-IDF vectors, and trained using:

* Logistic Regression
* Linear SVM
* Multinomial Naive Bayes

GridSearchCV was used to find optimal parameters, and the final prediction was made using a Hard Voting Classifier.

The project also includes:

* PCA visualization
* decision boundary visualization
* class distribution graph
* real-time custom news prediction

Final model accuracy reached around 99% on the dataset.

Dataset Source:

Fake and Real News Dataset on Kaggle: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data
Note : Some visualization and debugging concepts were done with the help of AI tools.
