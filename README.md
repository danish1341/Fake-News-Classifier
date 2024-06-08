# Fake-News-Classifier-using-Data-analytics

This project aims to build a machine learning model to detect fake news using data analytics. The dataset used in this project consists of news articles labeled as "FAKE" or "REAL". By utilizing text processing techniques and a classification algorithm, we achieve a high accuracy in identifying fake news.

# Table of Contents
1.Overview
2.Dataset
3.Project Steps
4.Results
5.Software Requirements
6.Programming Languages and Modules


# 1.Overview
Fake news detection using Data Analytics method along with python language.In this project, we employ data analytics techniques and machine learning to detect fake news. We use a dataset with news articles and labels indicating whether the news is fake(unreliable (1)) or real(reliale(0)). The project involves text processing using TF-IDF andpredictions are domne  using different algorithms such as Logistic regression , Decision Tree Classifier , Random Forest calssifier and Gradient boost Clasifier.



# 2.Dataset
About the Dataset:

The dataset used for this project is news.csv. Dataset has a shape of 20800*5. The dataset has four columns: first identifies the id, second and third are title and text wheras the fourth one is author and the fifth one is the label denoting FAKE or REAL.

title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
id: unique id for a news article
label: a label that marks whether the news article is real or fake:
1: unreliable 0: reliable

# 3.Project Steps

1.Import Libraries: Import the necessary libraries for data manipulation, text processing, and machine learning.
2.Load Data: Load the dataset into a pandas DataFrame and inspect its shape and contents.
3.Data preprocessing: Extracting the import and data.
4.Seperating Data: Seperating the data and the label.
5.Stemming: Stemming is the process of reducing words to their base or root form to improve text analysis by treating different forms of a word as a single term
5.TF-IDF Vectorization: Convert the text data into TF-IDF features, removing stop words and limiting the maximum document frequency.
6.Splitting data: Splitted the dataset into training and testing sets.
6.Train Classifier: Initialize and trained different classfiers such as Logistic Regression, Decision Tree Classifier , Random Forest calssifier and Gradient Boost calssifier
7.Evaluate Model: Evaluate the model's performance using accuracy score.

# 4.Results

The model achieves very good results as following.
1.Logistic Regression-0.9865985576923076
2.Decision Tree Classifier-0.9927884615384616
3.Random Forest classifier-0.9942307692307693
4.Gradient Boost classifier-0.9675480769230769

# 5.Software Requirements
PyCharm Community Edition (or any other Python IDE)

# 6.Programming Languages and Modules
1.Python 3
2.Numpy
3.Pandas
4.Scikit-learn












