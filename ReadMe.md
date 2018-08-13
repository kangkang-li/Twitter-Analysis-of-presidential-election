# Twitter Analysis of presidential election
• Extracted tweets and user info with API Tweepy, and stored in MySQL database
• Established language models using TextBlob, PCA, SVM, and Random Forest with Spark MLlib
• Processed training, classifying, and labeling on Spark for distributed computing
• Visualized distributions of sentiment and subjectivity on U.S. maps using Basemap and Matplotlib

This project was constructed on Dec 2016 when the result of presidential election came out. Because the lack of awareness of git/github of author at that time, the project was put on github recently in Aug, 2018. 

Interestingly, Twitter API is not completely open to public that it requires application of permission, and the author didnt hear back after 2 weeks since the application. Some offline data in JSON was provided for test use.

## Twitter API
With the accessibility of Twitter API Tweepy, "twitter scape" can be used to acquire tweets data.

### resources:
https://github.com/dataquestio/twitter-scrape
<br>https://developer.twitter.com/en/docs