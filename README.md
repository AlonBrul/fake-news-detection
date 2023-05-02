# fake-news-detection
## Introduction
In this project I used machine learning **Transformer** models to classify fake news from real news based on the news text content. The Transformer models were trained and tested on six different data manipulations preformed on the dataset Liar-Liar in order to find the best data embeddings. Two  embedding techiniques were used: BOW (Bag Of Words), feeding the data to a trained Transformer model **Bert** and extracting the embeddings from it.
****
The code is split to two google colab notebooks, the dataset used is in a different repository.<br>
* In 'Fake_news_encoding.ipynb' notebook we produce embedded representations our dataset.
* In 'Fake_news_learning.ipynb' notebook we build ML models on which we train and test our embedded datasets.
* 'Fake news detection.docx' is the project final report where you will find extended description of the project (written in Hebrew).
* link to dataset: https://github.com/AlonBrul/liar-liar-dataset
* about the dataset: https://paperswithcode.com/dataset/liar
