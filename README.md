# fake-news-detection
## Introduction
In this project I used machine learning **Transformer** models to classify fake and non-fake news based on the news' text content. The Transformer models were trained and tested on six different data manipulations preformed on the dataset **Liar-Liar** in order to find the best data embeddings. Two  embedding techiniques were used: 1) BOW (Bag Of Words) and 2) feeding the data to a trained Transformer model **Bert** and extracting the embeddings from it. Using BOW embeddings with positional encoding on binary labels only, (the dataset itself is multiclass labeled), achived the best accuracy of 0.695. Refernce accuracies are provided in the 'Fake news detection' document.
****
The code is split to two google Colab Notebooks, the dataset used is in a different repository (link below).<br>
* In the 'Fake_news_encoding.ipynb' notebook we produce embedded representations of our dataset.
* In the 'Fake_news_learning.ipynb' notebook we build ML models on which we train and test our embedded datasets.
* 'Fake news detection.docx' is the project report where you will find extended description of the project (written in Hebrew).
* Link to the **Liar-Liar** dataset: https://github.com/AlonBrul/liar-liar-dataset
* About the dataset: https://paperswithcode.com/dataset/liar
