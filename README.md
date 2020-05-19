# Fake-News-Detection

Nowadays it is very important to distiguish between the authentic news and fake/ sarcastic news with their widespread proliferation on social media. Many big companies would like to have this feature in their platform to help curb the spread of the hoax.

This project was created to analyse dataset described in [this paper](https://arxiv.org/abs/1908.07414). Moreover, this is the part of my assignment submission for one of the modules for my masters.

<img src="https://github.com/shubhamSonarghare/Fake-News-Detection/blob/master/sample%20output/splits.png">

To analyse this dataset two methodologies were employed. First was Bag of words(BoW) and other was word embeddings.  

This dataset was then analysed for stop words, length of fake and real news, etc.

<img src="https://github.com/shubhamSonarghare/Fake-News-Detection/blob/master/sample%20output/freqWords.png">

Following results were obtained using BoW and three different methods including Multinomial Naive Bayes, SVM and logistic regression.

<img src="https://github.com/shubhamSonarghare/Fake-News-Detection/blob/master/sample%20output/BOW.png">

Following results were obtained using Word Embeddings (Word to vector):

<img src="https://github.com/shubhamSonarghare/Fake-News-Detection/blob/master/sample%20output/W2V.png">

For further details visit [this notebook](https://github.com/shubhamSonarghare/Fake-News-Detection/blob/master/Fake_News_detection_Final.ipynb).
