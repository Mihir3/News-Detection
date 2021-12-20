# News-Detection

# Overview 
The main aim of this project is to build a binary classifier to detect fake news and real news.

After employing the 80% data for the training set and the 20% data for the testing set for the model, it could detect fake news with an accuracy of around 95%

Further, I think the dataset can be made dynamic and real-time based while the accuracy of the model can also be improved significantly with new. layers and algorithms.

# Methodology
I have taken two datasets from Kaggle - one for fake news and one for true news. Machine learning data only works with numerical features so we have to convert text data into numerical columns. So, I did this using the NLTK library.

Also, I couldn’t use text data directly because it has some unusable words and special symbols and many more things. So we have to clean the text data first. This is done with the help of RegEx. The data was then split into 80% data for the training set and the remaining 20% data for the testing set.

With the help of sklearn library; I applied Tfidf vectorizer, Multinomial Naïve Bayes, and Classification matrix to make a model that will be able to differentiate between real and fake news. Later, I also calculated the accuracy of the model and it was around 95%

# Technologies Used
Language : Python

Libraries : re, numpy, pandas, matplotib, nltk

Software Tools : Python(3.9), Jupyter Notebook
