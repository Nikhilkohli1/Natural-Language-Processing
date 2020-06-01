## Sarcasm Detection in News Headlines (Kaggle)

### Can you identify Sarcastic sentences?
### Can you distinguish between Fake news and Legitimate news?

Since news headlines are written by professionals in a formal manner, there are no spelling mistakes and informal usage. This reduces the sparsity and also increases the chance of finding pre-trained embeddings.

Furthermore, since the sole purpose of TheOnion is to publish sarcastic news, we get high-quality labels with much less noise as compared to Twitter datasets.

### Dataset

The dataset can be found at the below Kaggle Link - 

https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection

Each record consists of three attributes:

is_sarcastic: 1 if the record is sarcastic otherwise 0

headline: the headline of the news article

article_link: link to the original news article. Useful in collecting supplementary data

### Deep Learning Framework
I will be using Tensorflow to implement the Deep Learning Models for this Project.