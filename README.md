<h1 style="text-align: center;"> Email Spam Detection For ISP</h1>

![project logo](/images/spam_logo.png)

# Table Of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](https://github.com/ncmoliver/classification_challenge/blob/main/README.md#dataset-description)
3. [Modeling Approach](https://github.com/ncmoliver/classification_challenge/blob/main/README.md#modeling-approach)
   - [Logistic Regression](#logistic-regression)
   - [Random Forest](#random-forest)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [Future Improvements](#future-improvements)
7. [Installation Instructions](#installation-instructions)
8. [References](#references)

# Project Overview
In today's digital world, email spam is more than just a nuisance—it's a security risk and a productivity drain. This project focuses on improving our existing email filtering system by harnessing the power of supervised machine learning.

Using a dataset containing a mix of spam and non-spam emails, I developed two classification models: Logistic Regression and Random Forest. These models are designed to automatically and accurately identify spam emails, preventing them from cluttering inboxes.

By comparing the performance of these models, we will determine which approach is best suited to enhance our spam filtering system and improve email management for our users.

# Dataset Description
The dataset contains information about emails settings and permissions information to determine whether the email is spam. It ultimately has a column used as the target that classified each as 'spam' or 'not spam', which is the 'Result' column in our dataset. 

# Modeling Approach

## Logistical Regression Model

## Random Forest Model

# Results
The performance of the two models was measured using the accuracy score on the test set. The results showed that both models were effective in classifying emails as spam or not spam, but there wasn't much difference between how the models performed:

| Model | Accuracy Score |
| ----------- | ----------- |
| Logistical Regression Model | 93% |
| Random Forest Model | 94% |

# Conclusion
Through this project, I successfully implemented two supervised machine learning models to improve an ISP's email filtering system. The **Random Forest model** performed better than the **Logistic Regression model**, achieving a higher accuracy in identifying spam emails.
# Future Improvement

# Installation Instructions

# References 

