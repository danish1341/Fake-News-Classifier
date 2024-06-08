# Fake-News-Classifier-using-Data-analytics

This project aims to build a machine learning model to detect fake news using data analytics. The dataset used in this project consists of news articles labeled as "FAKE" or "REAL". By utilizing text processing techniques and a classification algorithm, we achieve a high accuracy in identifying fake news.

# Table of Contents
1.Overview
2.Dataset
3.Installation
4.Usage
5.Project Steps
6.Results
7.Software Requirements
8.Programming Languages and Modules
9.Contributing
10.License
11.Acknowledgements

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

# 3.Installation

git clone https://github.com/danish1341/Fake-News-Classifier-using-Data-analytics.git
cd Fake-News-Classifier-using-Data-analytics

python3 -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`

pip install -r requirements.txt








