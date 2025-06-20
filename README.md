# IMDB Sentiment Analysis

This project performs sentiment analysis on the **IMDB movie reviews dataset**. Using Natural Language Processing (NLP) techniques, the model classifies movie reviews into **positive** or **negative** sentiment categories based on the text content.

## Key Features:
- **Dataset**: Utilizes the IMDB dataset, containing 50,000 movie reviews labeled as either positive or negative.
- **Preprocessing**: Data is cleaned and tokenized, with stopwords removed and text normalized.
- **Modeling**: Implements a machine learning model using a **TF-IDF** vectorizer to convert text into numerical features, followed by training a classification model.
- **Evaluation**: The performance is evaluated on a test set and validated on a validation set. Each of the classifiers investigated has specific hyperparameters that can be tuned, and we will explore how those hyperparameters affect the model performance using several metrics: (1) classification accuracy, (2) confusion matrix, and (3) precision and recall.


## Techniques Used:
- **Text preprocessing** (removing stop words, tokenization, lemmatization)
- **TF-IDF** vectorization
- Model evaluation using **accuracy**, **precision**, **recall**, and **F1 score**

## Classifiers:
- KNN
- Logistic regression
- Neural Network
- Multinomial Naive Bayes
  
## Objective:
For the project, we analyzed the performance of different classifiers on the IMDB Movie Reviews dataset, which contains 50,000 reviews from the Internet Movie Database that are labeled positive or negative. The classification methods that we utilized are K Nearest Neighbor, Logistic, Neural Networks, and multinomial Naive Bayes. From employing a variety of different models, we can conclude that the logistic classifier performed the best in predicting whether a review is positive or negative, with the highest testing accuracy of 84.68%. Multinomial Naive Bayes and Feedforward Neural Networks had high testing accuracies with 82.70% and 83.27%, respectively. The K Nearest Neighbor classifier could not adjust as well to the data and only had a testing accuracy of 73.08%.

