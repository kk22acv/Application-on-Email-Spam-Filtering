#Data Source
[Your Link Here](https://www.kaggle.com/datasets/marcelwiechmann/enron-spam-data?select=enron_spam_data.csv)
#Overview
Phishing emails frequently imitate official messages, making it challenging to differentiate them from real communication. Conventional security measures, based on fixed rule systems, struggle to keep up with the advancing complexity of phishing strategies (Areej & Afrah, 2021). This challenge highlights the need for smart, flexible solutions. Introduce ML and NLP, technologies that can learn and adjust to new phishing patterns as time goes on. Machine Learning algorithms can undergo training on large datasets of both phishing and legitimate emails using supervised learning techniques (Benavides-Astudillo, et al., 2023).

#Reading Data:
This process includes reading the Dataset, will extract two target features after reading the dataset they are
1)Message and 2)Spam(Suspicious mail)/Ham(Normal mail)

#Cleaning The Data:
The Datset contains missing values or empty values which leads us to the improper out, so any missing values or empty values in the dataset will be removed.
Text Cleaning:
we will be using "Stopwords" function to remove the unnecessary words in the dataset

#Sampling the Data:
Sampling the data needs to be done because sampling the data increases the number of training samples which can improves model's ability.
After Sampling Data Splitting is done, which splits data into Training set(75%) and testing set(25%)

#Text Preprocessing Techniques:
We will be using CountVectorization and TFIDF(Term Frequency Inverse Document Frequency),These are both techniques used in NLP(Natural Language Processing).
These techniques helps in converting text into numerics which is very helpful in detection of Phishing emails

#Applying Machine Learning Algorithms
We have used RandomForest,LogesticRegression and Naviyes Bayes Algorithms and compare the metrics like confusion matrix,accuracy,precision and F1score.
Comparing the metrics of the Algorithms and choosing the best algorithm.

#Visualizations:
plots shows the accuracy of the model's and results of models we used
