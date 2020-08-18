# Sentiment-Analysis-Movie-Review
Sentiment analysis of the movie reviews using NLTK and SCIKIT learner

## About

In this repository, I have used **NLTK** library to get the **Movie Review** dataset.

Various function have been used for processing the dataset.

For extracting the word feature from the dataset, two appraoches have been used:

* Firstly,**TOP-N-WORD** appraoch is used for creating the feature dataset which uses the top N **Here, N=2500** words from the dataset.

***Freqency Distribution of Top 100 words is shown below which is used in the feature dataset creation***

<img src="Frequency Distribution.png">

* The second appraocah is **BAG OF WORD** feature appraoch, in this appraoach **Unigram** method is used




For classification and predicting the sentiment of the reviews various algorithms are used :

* **Naive Bayes Classifier**
* **Bernoulli Bayes Classifier**
* **Multinomial Bayes Classifier**
* **Logistic Regression**
* **Stochastic Gradient Descent Learning Classifier**
* **Support Vector Classifer**
* **Linear SVC**
* **Nu-Support Vector** 



### Note

* **Out of these two functio  **BAG OF WORD** function is able to perform better for this implmentation.**
* **For implemnting various machine learning algorithm for the analysis, SCIKIT is being integrated with NLTK**
