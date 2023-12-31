Sentiment Analysis of E-Commerce Website Reviews
Overview
This project focuses on sentiment analysis of customer reviews from an e-commerce website, aiming to classify reviews into positive and negative sentiments. Two machine learning classifiers, Logistic Regression and Naive Bayes, were implemented to achieve this task. The project leverages Natural Language Processing (NLP) techniques and achieved a recall score of 93.6% with Naive Bayes and 86.4% with Logistic Regression using TF-IDF vectorization.

Motivation
Understanding customer sentiments from reviews is crucial for e-commerce businesses. As the volume of reviews increases, manual analysis becomes time-consuming. This project explores the application of AI tools to transform lengthy reviews into concise summaries, enabling businesses to quickly grasp customer preferences.

Dataset
The dataset used in this project was obtained from Kaggle and contains 23,000+ customer reviews from a women's clothing e-commerce website. The dataset includes 10 features such as customer ID, age, title, review text, rating, and recommend index.

Project Workflow
Data Preprocessing:

Handling missing values and outliers.
Addressing class imbalance in the target variable.
Feature Selection:

Variance thresholding to remove irrelevant features.
Exploratory Data Analysis (EDA) using a heatmap to visualize feature relationships.
NLP Techniques:

Text preprocessing steps including removing punctuation, URLs, stop words, and applying lower casing, tokenization, stemming, and lemmatization.
Vectorization:

Utilizing Bag of Words (BOW) and TF-IDF approaches for text vectorization.
Addressing sparsity issues with TF-IDF.
Modeling:

Implementing Logistic Regression and Naive Bayes classifiers.
Evaluating model performance using recall scores.
Results:

Logistic Regression: Recall score of 86.4%.
Naive Bayes: Recall score of 93.6%.
Challenges and Considerations
Handling missing values, outliers, and class imbalance.
Addressing feature independence assumptions in Naive Bayes.
Dealing with correlated features resulting from word embedding techniques.
Recommendations
Use Naive Bayes for its efficiency with large datasets, robustness to outliers, and interpretability.
Consider the impact of correlated features on model performance.
Future Work
Explore additional NLP techniques like word embeddings.
Investigate methods to address correlated features.
