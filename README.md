# Supervised Learning: Binary Classfication of Toxic Comments

## Description:
Expressing oneself on online media (such as Facebook, Twitter, and YouTube) is not so easy. It often comes with the threat of abuse and harassment. This may result in people stopping to express themselves or seeking alternative platforms to express their opinions. Similarly, online chat platforms struggle to facilitate conversations which result in completely removing user comments. Thus, a tool which can help improve online conversations is indispensable given the increasingly high number of people on online platforms.

## Objective:
In this project, we perform binary classification of the imbalanced text dataset and eplore the methods which can improve classification metrics such as precision and recall. 

## Methodology:
We obtained the dataset from Kaggle competition (https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview) which contains a large number of Wikipedia comments (~12% comments are toxic). We cleaned, lemmatized, and extracted only nouns and adjectives for text classification. We implemented random oversampling of minority class, synthetic minority oversampling technique (SMOTE), and  adaptive synthetic (ADASYN) sampling technique to optimize precision/recall scores. 

## Results/Conclusions:
In this project, starting from a raw text data or corpus, a significant amount of data cleaning was performed. With random oversampling of the minority class, we can achieve a high accuracy and precision scores of 81% and 75%, respectively. 

## References:

[1] Aurelien Geron, _Hands-On Machine Learning with Scikit-Learn & TensorFlow_, 2017.

[2] Andreas Muller & Sarah Guido, _Introduction to Machine Learning with Python_, 2017.