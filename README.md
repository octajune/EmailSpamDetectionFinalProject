# EmailSpamDetection 

The website is currently hosted on: https://sejal-spamd.azurewebsites.net/

## Table of Content
  * Abstract
  * Introduction
  * Difference between spam and ham	
  * Problem statement
  * Objective
  * Conclusion

## Abstract
The upsurge in the volume of unwanted emails called spam has created an intense need for the development of more dependable and robust antispam filters. Machine learning methods of recent are being used to successfully detect and filter spam emails. We present a systematic review of some of the popular machine learning based email spam filtering approaches. Our review covers survey of the important concepts, attempts, efficiency, and the research trend in spam filtering. We recommended deep leaning and deep adversarial learning as the future techniques that can effectively handle the menace of spam emails.

## Introduction
Emails are important because they creates a fast, reliable form of communication that is free and easily accessible. They allow people to foster long-lasting, long-distance communication. Spam e-mails can be not only annoying but also dangerous to customers. Spam e-mails can be defined as

* Anonymity
* Mass-Mailing
* Unsolicited

Spam e-mail messages are randomly sent to multiple addresses by all sort of groups , but mainly by lazy advertisers and criminals who wish to lead you to phishing sites

## Difference between Spam and Ham

#### SPAM

![Screenshot (13)](https://user-images.githubusercontent.com/73702888/231462194-c33c796a-b194-44b3-b9e7-02685a61d3b1.png)

#### HAM

![Screenshot (16)](https://user-images.githubusercontent.com/73702888/231462287-0d47ade4-416c-4208-8b85-b2fe6679d4af.png)

## Problem Statement

We have chosen this project because nowadays there are lots of people trying to fool you just by sending you fake e-mails like you have won a 1000 dollars, this much amount is deposited in your account once you open this link and then they will try to hack your information.
 * Unwanted emails irritating internet consumers.
 * Critical e-mail messages are missed and/or delayed.
 * Identity Theft.
 * Spam can crash mail servers and fill up hard drive.
 * Billions of dollars lost worldwide.

## Objective

The objective of identification of spam e-mails are :
 * To give knowledge to the user about the fake e-mails and relevant e-mails.
 * To classify that mail is spam or not.

# Methodology
| METHODOLOGY  |DESCRIPTION |
| ------------- | ------------- |
| Collecting Dataset  | The test data is used to check the accuracy of the model built with the training data. The training data set contains  4137 emails . The test data contains 1435 emails .|
| Data Preprocessing | For achieving better results from the applied model in Machine Learning projects the format of the data has to be in a proper manner. Removed duplicate data ,Lower case, Tokenized, STOP WORDS, Stemming |
| Feature Selection | Extracted tfidf vector (our feature here) of 3000 dimensions for each email of training set. Each tfidf vector contains the frequency of 3000 words in the training file. |
| Model Construction | Logistic Regression, SVC, MultinomialNB, DecisionTreeClassifier, KNeighbourClassifier, RandomForestClassifier, AdaBoostClassifier, BaggingClassfier, ExtraTreesClassifier, GradientBoostingClassifier, XGBClassifier, VotingClassifier, StackingClassifier |

# Bag Of Words
#### Spam

![Screenshot (20)](https://user-images.githubusercontent.com/73702888/231497576-b470fade-7a25-496e-bbf4-6776945d42af.png)

#### Ham

![Screenshot (22)](https://user-images.githubusercontent.com/73702888/231507871-ffe6950d-0a44-4b32-bfc9-f48818489cce.png)

# Installation
The Code is written in Python 3.9.2. If you don't have Python installed you can find it [here](https://www.python.org/downloads/release/python-3913/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

``` pip install -r requirements.txt ```

OR

* Go to EmailSpamDetectionFinalProject/app.py
* Run ``` sudo docker-compose up ``` from the root directory of the application
* The website must be running on localhost:8051 with help of streamlit

# Directory Tree

```
Email_Spam_Detection/
├─ app.py/
├─ encoded-spam.csv/
├─ get-pip.py
├─ model.pkl
├─ requirement.txt
├─ spam_detection.ipynb
├─ spam.csv
├─ vectorizer.pkl
├─ README.md
```

# Technologies Used

![numpy](https://user-images.githubusercontent.com/73702888/231514125-fe638b79-8566-44c6-aebf-d59fcc073c92.png)
![pandas](https://user-images.githubusercontent.com/73702888/231514616-946d436f-cd8e-4413-a3a9-6712a49c22ed.png)
![scikit](https://user-images.githubusercontent.com/73702888/231514997-d8fba16d-6e46-4e31-8bbe-0a54483d73af.png)
![streamlit](https://user-images.githubusercontent.com/73702888/231515302-ca23afa9-ff49-434d-b93e-7b0fdcf99ed6.png)
![download](https://user-images.githubusercontent.com/73702888/231516055-1f8ab8a2-c1b1-460a-8d05-72f91dfd5f23.png)

# Result

| ML MODEL  | ACCURACY_SCORE | PRECISION_SCORE | 
| ------------- | ------------- | ------------- |
| Gaussian NB | 0.86 | 0.50 |
| Multinomial NB | 0.97 | 1.00 |
| Bernoulli NB | 0.98 | 0.99 |
| SVC | 0.97 | 0.97 |
| KNN | 0.90 | 1.00 |
| Decision Tree | 0.93 | 0.83 |
| Logistic Regression | 0.95 | 0.97 |
| Random Forest | 0.97 | 0.98 |
| AdaBoost | 0.96 | 0.92 |
| Bagging | 0.95 | 0.86 |
| Extra Tress | 0.92 | -- |
| xgb | 0.97 | 0.94 |

#### Tabular representation of accuracy and precision of classifiers

![Screenshot (24)](https://user-images.githubusercontent.com/73702888/231507785-c6715e74-6bce-48b1-ae7a-a978f8471877.png)

#### Pictorial representation of accuracy and precision of classifiers

# Conclusion 
 * We were able to classify the e-mails are spam or non-spam. With high number of e-mails lots of people using the system, it will difficult to handle all possible mails as our project deals with only limited amount of corpus.
 * We can now take raw input from the user and classify it as spam or ham.
