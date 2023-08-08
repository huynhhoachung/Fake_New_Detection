# <h3 align="center"><font size="15"><b>Fake News Detection Evaluation </b></font></h3> 
</br>

**Task type:** Classification

**Models used:** LinearSVC, MultinomialNB, XGBoost

**Tools used:** NLP preprocessing tools, semi-supervised learning technique, new feature engineering, Word Cloud
# 1. Introduction
**In this notebook, we will EDA dataset with Natural Language Processing (NLP) technique and use classification to identify fake news using different models to evaluate their performance on this task and analyze their effectiveness.**
# 2. Use case
**Recently, Fake news is becoming increasingly prevalent, and it can have serious implications. NLP can be used to detect and classify fake news to protect society from its damaging effects. Additionally, NLP can be used to identify topics and trends in news articles, which can be beneficial for research and news outlets.**
# 3. Result
![alt text](https://github.com/huynhhoachung/Fake_New_Detection/blob/main/Images/SVM_result.png?raw=true) </br>
![alt text](https://github.com/huynhhoachung/Fake_New_Detection/blob/main/Images/MNB_result.png?raw=true) </br>
![alt text](https://github.com/huynhhoachung/Fake_New_Detection/blob/main/Images/XBG_result.png?raw=true) </br>
In terms of accuracy and precision, LinearSVC gives us the best performance with 95.87% accuracy and 95.99% precision on the trained dataset. While with recall, MultinomialNB results in slightly higher performance with 95.57%, followed by LinearSVC with 95.41% and 91.4% of XGBoost
# 4. Conclusion
To conclude, for the best overall performance, LinearSVC has the best result in 3 models
