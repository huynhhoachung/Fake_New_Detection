# <h3 align="center"><font size="15"><b>Fake News Detection Evaluation </b></font></h3> 
</br>

**Task type:** Classification

**Models used:** LinearSVC, MultinomialNB, XGBoost

**Tools used:** NLP preprocessing tools, semi-supervised learning technique, new feature engineering, Word Cloud

# 1. Introduction
## About notebook</br>
- In this notebook, we will EDA dataset with Natural Language Processing (NLP) technique and use classification to identify fake news using different models to evaluate their performance on this task and analyze their effectiveness.</br>
In order to run the notebook, please install the required packages</br>
- **If you use pip**
```pip -r requirements.txt```</br>
- **If you use conda**
```conda install --file requirements.txt```

## About dataset</br>
This dataset has 2 files with total of 44898 entries including 23481 fake news and 21417 real news acknowledge by
1. Ahmed H, Traore I, Saad S. “Detecting opinion spams and fake news using text classification”, Journal of Security and Privacy, Volume 1, Issue 1, Wiley, January/February 2018.
2. 2. Ahmed H, Traore I, Saad S. (2017) “Detection of Online Fake News Using N-Gram Analysis and Machine Learning Techniques. In: Traore I., Woungang I., Awad A. (eds) Intelligent, Secure, and Dependable Systems in Distributed and Cloud Environments. ISDDC 2017. Lecture Notes in Computer Science, vol 10618. Springer, Cham (pp. 127-138).

**Key features**

- ```title:```Title of the news</br>
- ```text:```Article/Content of the news</br>
- ```subject:```The area of news that being published</br>
- ```date:```Pusblished date of the news</br>

**Reference:**
```https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset```


# 2. Use case
Recently, Fake news is becoming increasingly prevalent, and it can have serious implications. NLP can be used to detect and classify fake news to protect society from its damaging effects. Additionally, NLP can be used to identify topics and trends in news articles, which can be beneficial for research and news outlets.
# 3. Result
![alt text](https://github.com/huynhhoachung/Fake_New_Detection/blob/main/Images/SVM_result.png?raw=true) </br>
![alt text](https://github.com/huynhhoachung/Fake_New_Detection/blob/main/Images/MNB_result.png?raw=true) </br>
![alt text](https://github.com/huynhhoachung/Fake_New_Detection/blob/main/Images/XBG_result.png?raw=true) </br>
In terms of accuracy and precision, LinearSVC gives us the best performance with 95.87% accuracy and 95.99% precision on the trained dataset. While with recall, MultinomialNB results in slightly higher performance with 95.57%, followed by LinearSVC with 95.41% and 91.4% of XGBoost
# 4. Conclusion
To conclude, for the best overall performance, LinearSVC has the best result in 3 models
