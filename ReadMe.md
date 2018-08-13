# Twitter Analysis of presidential election
• Extracted tweets and user info with API Tweepy, and stored in MySQL database
<br>• Established language models using TextBlob, PCA, SVM, and Random Forest with Spark MLlib
<br>• Processed training, classifying, and labeling on Spark for distributed computing
<br>• Visualized distributions of sentiment and subjectivity on U.S. maps using Basemap and Matplotlib

This project was constructed on Dec 2016 when the result of presidential election came out. Because the lack of awareness of git/github of author at that time, the project was put on github recently in Aug 2018. So far the prev version of source code is lost due to laptop replacement and the current one is incomplete, the author may rewrite it when free from new-grad job-hunting.

Interestingly, Twitter API is not completely open to public that it requires application of permission, and the author didnt hear back after 2 weeks since the application. Some offline data in JSON was provided for test use.

## Twitter API:
With the accessibility of Twitter API Tweepy, "twitter scape" can be used to acquire tweets data.

## Packages:
• numpy
<br>• scikit-learn for SVM and PCA
<br>• Twitter scape to aquire data
<br>• Spark
<br>• Spark MLlib as training framwork
<br>• textBolb for language polarity and subjectivity as truth data/label for training
<br>• Basemap to provide U.S. map
<br>• Matplotlib for image visualization

### resources:
https://github.com/dataquestio/twitter-scrape
<br>https://developer.twitter.com/en/docs
<br>https://textblob.readthedocs.io