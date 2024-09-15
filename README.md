<h1 style="text-align: center;"> 📧 Email Spam Detection For ISP</h1>

![project logo](/images/spam_logo.png)

# Table Of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](https://github.com/ncmoliver/classification_challenge/blob/main/README.md#dataset-description)
3. [Modeling Approach](https://github.com/ncmoliver/classification_challenge/blob/main/README.md#modeling-approach)
   - [Logistic Regression](https://github.com/ncmoliver/classification_challenge?tab=readme-ov-file#logistical-regression-model)
   - [Random Forest](https://github.com/ncmoliver/classification_challenge?tab=readme-ov-file#random-forest-model)
4. [Results](https://github.com/ncmoliver/classification_challenge?tab=readme-ov-file#results)
5. [Conclusion](https://github.com/ncmoliver/classification_challenge?tab=readme-ov-file#conclusion)
6. [Future Improvements](https://github.com/ncmoliver/classification_challenge?tab=readme-ov-file#future-improvement)
7. [References](https://github.com/ncmoliver/classification_challenge?tab=readme-ov-file#references)

# Project Overview
In today's digital world, email spam is more than just a nuisance—it's a security risk and a productivity drain. This project focuses on improving our existing email filtering system by harnessing the power of supervised machine learning.

Using a dataset containing a mix of spam and non-spam emails, I developed two classification models: Logistic Regression and Random Forest. These models are designed to automatically and accurately identify spam emails, preventing them from cluttering inboxes.

By comparing the performance of these models, we will determine which approach is best suited to enhance our spam filtering system and improve email management for our users.

# Dataset Description
The dataset contains information about emails settings and permissions information to determine whether the email is spam. It ultimately has a column used as the target that classified each as 'spam' or 'not spam', which is the 'Result' column in our dataset. 

# Modeling Approach

### Logistical Regression Model
The **Logistic Regression** model was chosen as one of the classifiers due to its simplicity and effectiveness in binary classification tasks. I scaled the data using **StandardScaler** and then fitted the logistic regression model using the training data. The model was evaluated based on its accuracy in predicting spam from the test set.

### Random Forest Model
The **Random Forest** model was selected as the second classifier because of its ability to handle imbalanced data and complex patterns within the dataset. After scaling the data, I trained the Random Forest model using the training set and predicted spam using the test set.

# Results
The performance of the two models was measured using the accuracy score on the test set. The results showed that both models were effective in classifying emails as spam or not spam, but there wasn't much difference between how the models performed:

| Model | Accuracy Score |
| ----------- | ----------- |
| Logistical Regression Model | 93% |
| Random Forest Model | 94% |

# Conclusion
Through this project, I successfully implemented two supervised machine learning models to improve an ISP's email filtering system. The **Random Forest model** performed better than the **Logistic Regression model**, achieving a higher accuracy in identifying spam emails.
# Future Improvement
### Incorporate Additional Features
Although it is not clear the overall basis of this dataset, whether it is looking at the email's package settings from sender to receiver, however the more relevant data you feed the model to train on the better the chances of the model. 

### Explore Additional Algorithms
We could test more models that are known to  perform well in classification and handle imbalanced data efficiently. 

# References 
[Xpert Learning Assistant](https://bootcampspot.instructure.com/courses/6028/external_tools/313)    
[Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)    
[UNC Archived Assignments](https://bootcampspot.instructure.com)    