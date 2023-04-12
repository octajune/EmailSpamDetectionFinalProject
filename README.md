# EmailSpamDetection 

## Table of Content
  * Abstract
  * Introduction
  * Difference between spam and ham	
  * Problem statement
  * Objective
  * Conclusion

## Abstract
The upsurge in the volume of unwanted emails called spam has created an intense need for the development of more dependable and robust antispam filters. Machine learning methods of recent are being used to successfully detect and filter spam emails. We present a systematic review of some of the popular machine learning based email spam filtering approaches. Our review covers survey of the important concepts, attempts, efficiency, and the research trend in spam filtering.I recommended deep leaning and deep adversarial learning as the future techniques that can effectively handle the menace of spam emails.

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

I have chosen this project because nowadays there are lots of people trying to fool you just by sending you fake e-mails like you have won a 1000 dollars, this much amount is deposited in your account once you open this link and then they will try to hack your information.
 - Unwanted emails irritating internet consumers.
 - Critical e-mail messages are missed and/or delayed.
 - Identity Theft.
 - Spam can crash mail servers and fill up hard drive.
 - Billions of dollars lost worldwide.

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







